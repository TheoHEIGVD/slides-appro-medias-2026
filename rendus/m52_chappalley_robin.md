# M52-1/2 Chappalley Robin - Mise en place d'un agent IA

# ETAT INITIAL ET OBJECTIFS À RENDRE POUR LE 23 FEVRIER 23h59

## Mon sujet d'étude est le développement d'agents IA autonomes basés sur des LLM Open Source en local.

L'objectif est de concevoir un agent capable de raisonner et d'utiliser des outils (fonctions Python par exemple) en utilisant des modèles gratuits exécutés localement, via Ollama.

## Contexte

Mon sujet de Travail de Bachelor n'étant pas encore arrêté, j'ai choisi de monter en compétence sur une technologie  à laquelle je m'intéresse depuis un certain temps, sans jamais avoir pris le temps d'y consacrer du temps. 

L'architecture "Agentique" (où l'IA **agit** au lieu de seulement parler) représente probablement le futur de l'interaction logicielle.

Apprendre à maîtriser ces outils dans un environnement Open Source et gratuit (Local First) me donnera une flexibilité totale pour l'utiliser dans mon travail de Bachelor, et certainement dans ma vie professionnelle future   .

## État initial

Connaissances théoriques : Compréhension basique du fonctionnement des LLM (texte complétion).

Connaissances techniques : Niveau 1% en Python. J'ai déjà écrit un peu de python, mais rien de très abouti, sauf quelques scripts de scraping. 

Expérience Agents : J'ai téléchargé Ollama et installé Llama 3 sur mon ancien ordinateur, mais les réponses étaient très lentes et j'ai abandonné.

## Objectifs SMART

**Spécifique** : Créer un assistant IA local capable de combler ses lacunes de connaissances en utilisant des outils externes. Il utilisera Ollama pour le raisonnement et disposera d'un outil de recherche web (ex: DuckDuckGo) et d'un outil de calcul mathématique

**Mesurable** : L'agent devra répondre correctement à une question d'actualité récente (que le modèle ne connaît pas nativement) en effectuant une recherche autonome, puis effectuer un traitement sur cette information (ex: "Quelle est la population actuelle de la Suisse et quel est ce chiffre divisé par 26 cantons ?")

**Atteignable** : Utilisation de la librairie langchain-community qui intègre déjà des outils de recherche gratuits, facilitant l'intégration en 36h.

**Réaliste** : Le projet reste en console (CLI), permettant de se concentrer sur la logique de décision de l'agent plutôt que sur l'interface

**Temporel** : Code fonctionnel et rapport d'analyse livrés pour le 6 mars 2026.

## Démarches et expérimentation (Plan 36h)

**Bloc 1 - Infrastructure & Découverte (10h)** :
Installation et configuration de Ollama.
Tests des différents modèles gratuits (Llama 3, Mistral, Gemma) pour voir lequel est le plus rapide/cohérent sur ma machine.
Prise en main des librairies Python pour connecter le modèle local.


**Bloc 2 - Développement de l'Agent (16h)** :
Implémentation de l'outil de recherche web (via DuckDuckGo Search - gratuit).
Implémentation d'un outil de calcul (pour éviter que le LLM ne fasse des erreurs de maths).
Création de la boucle "ReAct" (Reasoning + Acting) : forcer le modèle local à dire "Je dois chercher sur internet" avant de répondre.

**Bloc 3 - Tests & Analyse (6h)** :
Tests de robustesse : est-ce que le modèle local "hallucine" des outils qui n'existent pas ?
Comparaison de la rapidité d'exécution selon les modèles.


**Bloc 4 - Documentation (4h)** :
Rédaction du rapport final et nettoyage du code.

## 5 Questions 

1. Qu'est-ce qu'un "tool" (outil) dans le contexte d'un agent IA, et comment le LLM sait-il quel outil utiliser ?

2. Quelle est la différence entre un LLM qui "invente" une réponse (hallucination) et un LLM qui va chercher l'information via un outil ? Comment forcer le deuxième comportement ?

3. Comment se déroule, étape par étape, le trajet technique d'une requête utilisateur jusqu'à la réponse finale de l'agent ?

4. Quelles sont les limites concrètes rencontrées avec un modèle local (Ollama) par rapport à un modèle en ligne, et comment les contourner ?

5. S'il fallait ajouter un nouvel outil à l'agent (ex: lire un PDF, envoyer un email), quelles étapes faudrait-il suivre dans son code ?

# RAPPORT FINAL À RENDRE POUR LE 6 MARS 23h59

## Retour sur l'état initial


Mon avis sur le résultat de cette auto-formation est mitigé. Je n'avais pas d'attentes; mon projet n'était pas de remplacer les agents des entreprises par du full-local, ma machine n'est pas assez puissante pour cela. Je voulais juste comprendre comment les agents fonctionnaient et comment les utiliser. J'estime que l'object est à moitié atteint: j'ai bidouillé un peu, j'ai pu avoir une réponse de mon ordinateur (le sentiment est assez génial), mais je ne dirai pas que j'ai réussi à mettre en place un agent "complet". Le temps que j'ai réussi à accorder à cette auto-fomation n'était pas suffisant pour aller plus loin.

## Réponses aux 5 questions

1. Qu'est-ce qu'un "tool" (outil) dans le contexte d'un agent IA, et comment le LLM sait-il quel outil utiliser ?

Un tool est une fonction Python qui peut être appelée par l'agent IA. L'agent IA utilise un outil pour effectuer une action spécifique. Par exemple, un outil peut être utilisé pour effectuer une recherche sur internet, envoyer un email, lire un fichier, etc. Par exemple, voici un outil de recherche web et une calculatrice :

```python
recherche_web = DuckDuckGoSearchRun()

@tool
def calculatrice(expression: str) -> str:
    """Calcule une expression mathématique simple. Exemple: 234 * 45"""
    try:
        return str(eval(expression))
    except Exception as e:
        return f"Erreur de calcul: {e}"

mes_outils = [recherche_web, calculatrice]
```

Lorsqu'un utilisateur pose une question, le LLM analyse sa requête. S'il estime que sa propre base de connaissances ne suffit pas et que le besoin correspond à la description d'un outil disponible (ex: faire une multiplication), il choisit de générer une commande spécifique pour demander l'exécution de cet outil

2. Quelle est la différence entre un LLM qui "invente" une réponse (hallucination) et un LLM qui va chercher l'information via un outil ? Comment forcer le deuxième comportement ?

Une hallucination se produit quand le LLM tente de répondre à une question factuelle ou mathématique en se basant uniquement sur des probabilités statistiques de mots, ce qui mène souvent à des réponses fausses (ex: inventer le résultat d'un calcul complexe). L'utilisation d'un outil délègue la tâche à un système déterministe et exact (comme l'interpréteur mathématique de Python), garantissant une réponse 100% fiable.

Pour éviter qu'un LLM n'essaie de répondre de tête, on peut "forcer" l'outil de deux manières : soit via le "System Prompt" en lui donnant un ordre strict ("Tu dois toujours utiliser la calculatrice pour les chiffres"), soit au niveau du code via le framework (ex: LangChain permet de configurer le paramètre `tool_choice="nom_de_l_outil"` pour obliger le modèle à passer par cette fonction). C'est ce que j'ai choisi de faire lors de ce test; pour m'assurer que le LLM utilise bien l'outil de calcul, j'ai rajouté le log suivant :

```python
if msg.tool_calls:
    for tool in msg.tool_calls:
        print(f"🤖 L'IA décide d'utiliser l'outil : [{tool['name']}] avec les arguments {tool['args']}")
```

3. Comment se déroule, étape par étape, le trajet technique d'une requête utilisateur jusqu'à la réponse finale de l'agent ?
    1. Input:  L'utilisateur pose une question (ex: "Combien font 234 * 45 ?")
    2. Reasoning: Le LLM analyse la question et décide d'utiliser un outil (ex: la calculatrice citée ci-dessus)
    3. Action: Le LLM génère un "Tool Call" (appel d'outil) avec les arguments 234 et 45.
    4. Observation (Exécution) : Le script Python intercepte cet appel, met le LLM en pause, exécute la fonction Python calculatrice(234, 45), et récupère le résultat (10530)
    5. Synthèse finale : Le résultat de l'outil est renvoyé au LLM comme un nouveau message de contexte. Le LLM lit ce résultat et génère une réponse naturelle à l'utilisateur ("Le résultat est 10 530")

4. Quelles sont les limites concrètes rencontrées avec un modèle local (Ollama) par rapport à un modèle en ligne, et comment les contourner ?

Les modèles locaux sont restreints par le matériel de la machine, notamment la mémoire vive RAM. Les 16 GB de ma machine sont limitantes. J'imagine qu'un Macbook plus récent, avec un processueus plus pensé pour faire tourner des modèles en local, aurait été plus adapté On ne peut faire tourner que des "petits" modèles (ex: 8 milliards de paramètres avec le Qwen3 que j'ai choisi) 

```python
llm = ChatOllama(model="qwen3:8b", temperature=0)
```

Comparé aux modèles Cloud massifs (comme Gemini 3.1 Pro ou Claude Opus 4.6), c'est surtout la différence de vitesse qui est notable. Pour faire une tâche simple comme celle de la calculatrice, je n'ai pas ressenti de "manque de puissance". 

J'ai aussi choisi Qwen car c'est un modèle quantifié, ce qui signifie qu'il prend moins de RAM. L'intérêt réside surtout dans le fait que le modèle n'a pas besoin de tout savoir, il a juste besoin de savoir quel outil utiliser

5. S'il fallait ajouter un nouvel outil à l'agent (ex: lire un PDF, envoyer un email), quelles étapes faudrait-il suivre dans son code ?
    1. Créer une nouvelle fonction Python (ex: `lire_pdf(chemin_fichier)`) utilisant une librairie adaptée (comme PyPDF2) pour extraire le texte d'un document.
    2. Transformer cette fonction en "Tool" pour le LLM (ex: via le décorateur @tool de LangChain) en rédigeant une description très claire (docstring) pour que le LLM comprenne à quoi sert la fonction.
    3. Ajouter ce nouvel outil dans la liste des outils autorisés lors de l'initialisation de l'Agent (`llm.bind_tools([calculatrice, lire_pdf])`).


## Résultat de l'expérimentation

Pour m'aider, j'ai créé un agent à l'aide d'un prompt system. Cet agent était expert dans la mise en place d'agent pour les débutants. Il m'a aidé à mettre en place l'environnement et à comprendre comment marchaient les briques ensemble. L'expérience a été formatrice, puisque je suis arrivé à mes fins en faisant en sorte que mon ordinateur a fait des calculs pour répondre à une question que je lui ai posée. J'ai aussi compris l'importance de l'environement pour lancer un script Python, point qui m'a posé problème à plusieurs reprises.

## Investissement

_Détaillez le temps passé et les écarts avec l'investissement imaginé au départ, expliquez pourquoi._
J'ai passé environ 4h sur cette auto-formation. Un décès survenu dans ma famille à la fin du mois de février a un peu changé le calendrier prévu. J'ai aussi accordé plus du temps que nécessire au cours de réalité virtuelle qui m'a beaucoup intéressé et j'ai un peu hésité à me lancer, faute de place suffisante sur mon ordinateur. J'ai du faire un peu de tri avant de commencer, ce qui a encore rallongé le processus et ne me motivait pas à commencer.


## Réflexion sur la méthode d'auto-formation

J'ai constaté que l'auto-formation est un processus qui me convient, tant que je suis dans de bonnes dispositions. La période n'étant pas idéale pour moi, je ne tire pas de réelle conclusion de cette expérience. Je sais que si le sujet m'intéresse, je n'ai pas de difficulté à persévérer. Dans le cadre de ce sujet, je pense qu'essayer d'éprouver mon agent lors d'une journée de développement aurait été une bonne idée pour évaluer si les connaissances acquises étaient efficaces.

Je le savais, mais j'ai fait face à un agent IA (celui en ligne qui m'a aidé) qui m'a fourni du code d'une ancienne librairie langchain, ce qui m'a posé problème. D'où l'importance de savoir bien lire la documentation et de bien comprendre les librairies utilisées.

## Conclusion

J'ai appris à mettre en place un agent IA local en utilisant Ollama et LangChain. Je compte relancer cette expérience dans un environnement plus idéal pour moi, avec plus de temps et plus de motivation. J'ai aussi appris à me servir d'un agent IA pour aider à mettre en place un autre agent IA.

Je pense que dans le cadre du travail de Bachelor, je pourrai utiliser un agent IA en local, mais que cela représenterait un défi, surtout en terme de temps et de fine tuning. Là, mon agent sait qu'il faut utiliser la calculatrice quand on lui demande de calculer quelque chose, mais dans le cadre de l'intégration d'un outil au workflow d'une entreprise, je ne suis pas sûr de maîtriser suffisamment le sujet pour créer un agent pertinent qui m'aide vraiment

### Prompt système pour aider à mettre en place un agent dans le cadre de ce cours

Rôle et Identité
Tu es "Agent-Mentor", un ingénieur logiciel senior spécialisé dans l'Intelligence Artificielle, l'architecture "Agentique" (ReAct) et le déploiement de LLM en local (Local-First). Tu es également un excellent pédagogue, habitué à encadrer des étudiants en Bachelor.
Le Contexte de l'Utilisateur
Je suis un étudiant en Bachelor. J'ai un niveau débutant en Python (1%) mais une bonne compréhension théorique des LLM. Je dois réaliser un projet d'auto-formation de 36h dont l'objectif est de :
"Créer un assistant IA local (Ollama) capable de combler ses lacunes de connaissances en utilisant des outils externes (recherche web DuckDuckGo et calcul mathématique) en console (CLI)."
Ta Mission
Tu dois m'accompagner de A à Z pour réussir ce devoir et rendre mon "Rapport Final" pour le 6 mars 2026. Tes tâches se divisent en 3 axes :
Axe 1 : Accompagnement Technique (Code & Ollama)

Guide-moi pas à pas pour écrire le code Python. Puisque je suis débutant, ne me donne pas juste des blocs de code complexes. Explique-moi la logique, les librairies utilisées (comme langchain-community), et comment construire la boucle "Reasoning + Acting" (ReAct).
Aide-moi à configurer Ollama et à choisir le bon modèle (ex: Llama 3, Mistral) pour ma machine.
Aide-moi à déboguer les erreurs fréquentes (hallucinations d'outils, lenteur, format de sortie JSON incorrect).

Axe 2 : Réponses aux 5 Questions Théoriques
Je dois répondre à 5 questions précises dans mon rapport. Tu m'aideras à formuler des réponses claires, académiques et techniquement exactes pour :

Ce qu'est un "tool" et comment le LLM le choisit.
La différence entre hallucination et utilisation d'outil, et comment forcer l'outil.
Le trajet technique d'une requête (étape par étape).
Les limites des modèles locaux (Ollama) vs Cloud, et les solutions.
La procédure pour ajouter un nouvel outil (ex: lire un PDF).

Axe 3 : Rédaction du Rapport Final
À la fin du projet, tu m'aideras à structurer et rédiger mon rapport final qui doit contenir :

Retour sur l'état initial (bilan attentes/réalité).
Réponses aux 5 questions.
Résultat de l'expérimentation (aspects formateurs).
Investissement (temps passé, écarts avec le plan des 36h).
Réflexion sur la méthode d'auto-formation.
Conclusion (leçons apprises et implications pour mon Travail de Bachelor).

Règles de comportement :

Sois encourageant, didactique et patient.
Garde toujours à l'esprit que mon environnement est Local (Ollama) et gratuit.
Pose-moi des questions pour t'assurer que je comprends ce que je fais.
Demande-moi par quelle étape de mon plan de 36h je souhaite commencer aujourd'hui !
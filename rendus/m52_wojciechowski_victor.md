# M52-2 Wojciechowski Victor - Stack technique liée à la création d'un agent vocal IA

# ETAT INITIAL ET OBJECTIFS À RENDRE POUR LE 23 FEVRIER 23h59

## Mon sujet d'étude est l'étude de la stack technique d'un agent vocal IA.

**_Décrire le sujet_**

L'étude de la stack technique utile à la création d'un agent vocal IA est directement liée à mon travail de bachelor, car mon travail de bachelor se base sur la création de cet agent vocal. L'objectif est de réaliser un agent vocal qui réalise les premiers entretiens de sélection à partir de données. La solution doit permettre d'automatiser les entretiens clients, structurer les données récoltées et réduire la charge de travail humaine.

### Contexte

J'ai choisi ce sujet, car il est directement lié à ce que je vais devoir effectuer durant mon travail de bachelor. L'entreprise pour laquelle je vais réaliser mon travail de bachelor évolue dans le monde des services aux personnes, précisément dans le nettoyage. Batmaid souhaite prototyper une solution automatisée pour réaliser les premiers entretiens avec les leads qu'ils ont acquis. C'est dans cette optique qu'ils ont pris contact avec moi. La formation d'ingénieur des médias semble être le meilleur mix des compétences requises pour appréhender cette problématique et pour créer une solution technique sur le meilleur support possible pour atteindre l'objectif final.  
C'est intéressant pour mon futur professionnel en premier lieu, car c'est le proof of concept de mes compétences. Deuxièmement, le monde des MarTech est en pleine expansion grâce à la démocratisation des IA au début des années 2020 et développer mes compétences dans ce sujet représente un réel avantage par rapport aux autres candidats sur le marché du travail.

## État initial

Pour l'instant je n'ai réalisé qu'un petit agent IA, développé sur n8n. Je n'ai pas encore réellement exploré les agents vocaux IA bien que j'aie une vague idée de la manière dont ils sont créés. Cela veut dire que je vais partir pratiquement de zéro en termes de know-how technique. Donc je vais devoir me baser sur des articles ou des tutoriels qui vont m'aider à orienter ma démarche d'apprentissage.

## Objectifs

---

## Objectif 1 — Cartographier les composants techniques d’un agent vocal IA

### Description
Identifier et comprendre les composants techniques nécessaires à la création d’un agent vocal IA multilingue (FR/DE/IT/EN) destiné à automatiser les premiers entretiens de sélection.

### SMART

- **S (Spécifique)**  
  Identifier précisément les briques suivantes :  
  STT (Speech-to-Text), LLM, TTS (Text-to-Speech), orchestration, stockage des données, intégration ERP, hébergement.

- **M (Mesurable)**  
  - Rédiger une synthèse structurée du résultat des recherches  
  - Identifier au moins 3 solutions technologiques par composant  
  - Produire un schéma d’architecture complet et annoté

- **A (Atteignable)**  
  Basé sur recherche documentaire (articles techniques, documentations officielles, publications académiques).

- **R (Réaliste)**  
  Aucun développement requis, uniquement analyse et modélisation.

- **T (Temporel)**  
  Cartographie finalisée pour le 6 mars.

### Validation
- Document structuré remis  
- Schéma d’architecture clair et cohérent  
- Références citées et comparées

---

## Objectif 2 — Comparer les architectures techniques possibles

### Description
Comparer différentes architectures d’agent vocal (cloud API, open-source auto-hébergée, architecture hybride) afin d’identifier la solution la plus pertinente pour le travail de bachelor.

### SMART

- **S (Spécifique)**  
  Analyser au minimum 3 architectures complètes.

- **M (Mesurable)**  
  - Comparaison selon au moins 8 critères (latence, coût, complexité, multilingue, sécurité, dépendance API, scalabilité, intégration ERP)  
  - Production d’un tableau comparatif formalisé  
  - Rédaction d’une synthèse argumentative (2–3 pages)

- **A (Atteignable)**  
  Basé sur documentation technique et retours d’expérience existants.

- **R (Réaliste)**  
  Étude théorique sans implémentation.

- **T (Temporel)**  
  Analyse finalisée pour le 6 mars.

### Validation
- Tableau comparatif complété  
- Argumentation justifiée  
- Conclusion claire sur l’architecture la plus adaptée

---

## Objectif 3 — Étudier la structuration des données et l’intégration ERP

### Description
Analyser les méthodes permettant de transformer une conversation vocale en données structurées exploitables et intégrables dans un ERP.

### SMART

- **S (Spécifique)**  
  Étudier les mécanismes de transcription, structuration, scoring et export des données.

- **M (Mesurable)**  
  - Identifier au moins 2 modèles de structuration des réponses  
  - Proposer un schéma de données théorique  
  - Identifier les contraintes légales principales (RGPD)

- **A (Atteignable)**  
  Recherche documentaire + analyse de cas existants.

- **R (Réaliste)**  
  Modélisation théorique sans intégration réelle.

- **T (Temporel)**  
  Schéma et analyse finalisés pour le 6 mars.

### Validation
- Schéma de données documenté  
- Description claire du pipeline théorique  
- Identification des enjeux juridiques

---

## Objectif 4 — Identifier les principes UX spécifiques aux agents vocaux

### Description
Analyser les bonnes pratiques UX propres aux interactions vocales dans un contexte d’entretien automatisé.

### SMART

- **S (Spécifique)**  
  Identifier les principes liés à l’activation, au feedback, à la gestion des erreurs et au multilinguisme.

- **M (Mesurable)**  
  - Identifier au moins 5 bonnes pratiques UX vocales  
  - Citer au minimum 3 sources académiques ou techniques  
  - Proposer une trame d’entretien théorique

- **A (Atteignable)**  
  Basé sur recherche UX et études existantes.

- **R (Réaliste)**  
  Pas de test utilisateur requis à ce stade.

- **T (Temporel)**  
  Analyse finalisée pour le 6 mars.

### Validation
- Synthèse écrite argumentée  
- Références documentées  
- Proposition de structure d’entretien cohérente

## Démarche

L’objectif de cette auto-formation est de structurer l’apprentissage de la stack technique d’un agent vocal IA en vue du travail de bachelor.  
Les 36 heures seront réparties de manière progressive entre exploration, analyse critique et formalisation.

## Répartition prévisionnelle du temps

| Étape | Description | Temps estimé |
|--------|-------------|--------------|
| 1. Exploration générale | Recherche introductive sur les agents vocaux IA (fonctionnement global, architecture type, cas d’usage RH) | 6h |
| 2. Étude des composants techniques | Analyse détaillée des solutions STT, LLM, TTS, orchestration et stockage | 8h |
| 3. Analyse comparative des architectures | Étude des architectures cloud, open-source et hybrides + création d’un tableau comparatif | 7h |
| 4. Structuration des données & ERP | Recherche sur la transformation conversation → données structurées + contraintes RGPD | 6h |
| 5. UX vocale | Étude des principes UX propres aux agents vocaux (erreurs, interruptions, multilingue) | 4h |
| 6. Formalisation et rédaction | Structuration des résultats, schémas, synthèses et références | 5h |
| **Total** |  | **36h** |

Cette planification pourra être ajustée en fonction des difficultés rencontrées ou de la profondeur nécessaire sur certains aspects.

## 5 questions

Ces questions permettront d’évaluer l’acquisition réelle des connaissances techniques à l’issue de l’auto-formation.

1. Quels sont les composants indispensables d’un agent vocal IA et comment interagissent-ils entre eux dans une architecture complète ?

2. Quelles différences techniques et stratégiques existent entre une architecture cloud API, une solution open-source auto-hébergée et une architecture hybride ?

3. Quels sont les principaux défis techniques liés au multilinguisme (FR/DE/IT/EN) dans un agent vocal ?

4. Comment transformer une conversation vocale libre en données structurées exploitables dans un système ERP ?

5. Quelles sont les principales contraintes légales (notamment RGPD) liées à l’automatisation d’entretiens vocaux ?

Ces questions serviront de base à l’évaluation finale du travail réalisé.

## Expérimentation

L’expérimentation ne consistera pas en la création d’un produit final, mais en une validation conceptuelle de la compréhension technique acquise.

Elle prendra la forme de :

- La modélisation d’une architecture complète d’agent vocal IA adaptée au contexte du travail de bachelor.
- La création d’un schéma technique détaillé illustrant les flux entre :
  - l’ERP
  - le module STT
  - le modèle IA (LLM)
  - le module TTS
  - le système de stockage des données
- Une simulation théorique du pipeline de traitement des données (conversation → transcription → structuration → export).

Si nécessaire, de courts tests exploratoires d’API pourront être réalisés afin de vérifier la compréhension du fonctionnement de certaines briques techniques (sans développement d’un prototype complet).

L’objectif de cette expérimentation est de démontrer :
- la compréhension globale de l’architecture,
- la capacité à relier la théorie à une implémentation possible,
- la réduction des incertitudes techniques avant le travail de bachelor.

---

# RAPPORT FINAL À RENDRE POUR LE 6 MARS 23h59

## Retour sur l'état initial

Au début de cette auto-formation, je partais avec très peu de connaissances concrètes sur les agents vocaux IA. J'avais déjà réalisé un petit agent IA sur n8n, mais cela restait très éloigné d'une vraie réflexion sur une stack technique complète pour un agent vocal capable de gérer des entretiens. Mon objectif principal était donc de comprendre de quelles briques techniques un tel système est composé et de pouvoir comparer plusieurs approches possibles.

Avec le recul, les attentes de départ étaient cohérentes, mais j'ai constaté que le sujet est plus large que ce que j'imaginais. Je pensais surtout devoir identifier des outils, alors qu'en réalité il a aussi fallu comprendre comment ces outils s'articulent entre eux, comment les données circulent, quelles contraintes existent au niveau du multilinguisme, et quels enjeux se posent au niveau de l'intégration ERP et de la structuration des données. Mon état initial était donc juste, mais j'avais sous-estimé la complexité du sujet.

Dans l'ensemble, cette auto-formation m'a permis de passer d'une compréhension assez vague à une vision plus structurée de ce qu'implique la création d'un agent vocal IA dans un contexte réel d'entreprise.

## Réponses aux 5 questions

### 1. Quels sont les composants indispensables d’un agent vocal IA et comment interagissent-ils entre eux dans une architecture complète ?

Un agent vocal IA repose sur plusieurs composants qui travaillent ensemble. Le premier est le module de reconnaissance vocale, ou STT, qui transforme la voix de l'utilisateur en texte. Ce texte est ensuite transmis à un modèle de langage, ou LLM, qui interprète la demande, génère une réponse et peut aussi structurer certaines informations utiles. Ensuite, un module TTS transforme la réponse textuelle en voix. En parallèle, il faut aussi prévoir une couche d'orchestration qui gère la logique du dialogue, les appels API, les enchaînements entre les services et les éventuelles erreurs. Enfin, il faut un système de stockage ou d'export des données pour conserver les réponses, les résumés et les éléments utiles à l'entreprise.

Dans une architecture complète, l'utilisateur parle, le STT transcrit, le LLM traite, le TTS restitue, puis les données sont sauvegardées ou envoyées dans un système tiers comme un ERP. Ce fonctionnement paraît simple en apparence, mais il dépend en réalité de nombreux choix techniques.

### 2. Quelles différences techniques et stratégiques existent entre une architecture cloud API, une solution open-source auto-hébergée et une architecture hybride ?

Une architecture cloud API repose sur des services externes déjà prêts à l'emploi. Elle permet d'aller vite, de tester facilement et d'obtenir souvent de très bonnes performances dès le départ. En contrepartie, elle crée une dépendance vis-à-vis de fournisseurs externes, des coûts variables, et parfois des limites sur la personnalisation ou sur la gestion des données sensibles.

Une solution open-source auto-hébergée offre plus de contrôle. Elle permet de mieux maîtriser l'infrastructure, les traitements et parfois les données. En revanche, elle demande davantage de compétences techniques, plus de temps d'intégration, plus de maintenance et potentiellement plus de ressources matérielles. Ce n'est donc pas forcément la meilleure option pour un projet qui doit d'abord valider une faisabilité.

L'architecture hybride combine les avantages des deux. Elle permet par exemple d'utiliser des API externes pour certaines briques comme le STT ou le TTS, tout en gardant une partie de la logique ou du traitement sur une infrastructure maîtrisée. Stratégiquement, cette approche semble souvent plus pertinente pour un prototype avancé ou un POC réaliste, car elle permet de limiter certains risques tout en conservant de la souplesse.

### 3. Quels sont les principaux défis techniques liés au multilinguisme (FR/DE/IT/EN) dans un agent vocal ?

Le premier défi est la qualité de reconnaissance vocale selon la langue. Tous les moteurs STT ne performent pas de manière identique en français, allemand, italien et anglais. Il faut donc s'assurer que la transcription reste fiable dans les quatre langues ciblées.

Le deuxième défi concerne la génération de réponses. Un modèle de langage peut être performant dans plusieurs langues, mais la qualité varie selon la langue, le contexte et la précision attendue. Dans le cas d'un entretien de sélection, il faut que les questions soient claires, cohérentes et comparables d'une langue à l'autre.

Le troisième défi concerne la voix générée. Le TTS doit être compréhensible, naturel et adapté à la langue utilisée. Une mauvaise voix ou une voix peu fluide peut nuire à l'expérience globale.

Enfin, il y a un défi de cohérence globale. Il ne suffit pas qu'un système soit multilingue sur le papier. Il faut que la logique d'entretien, les informations récoltées, les catégories de réponses et les exports finaux restent comparables entre les langues. C'est un point important si l'entreprise veut ensuite exploiter les données de manière uniforme.

### 4. Comment transformer une conversation vocale libre en données structurées exploitables dans un système ERP ?

La première étape consiste à transcrire correctement la conversation. Une fois que le texte est disponible, il faut ensuite identifier les éléments utiles à extraire. Dans le cadre d'un premier entretien, cela peut être par exemple le nom, la langue parlée, la disponibilité, la zone géographique, certains critères de qualification ou encore des réponses à des questions précises.

Pour transformer cela en données structurées, il faut définir à l'avance un modèle de données. Cela veut dire décider quels champs doivent être remplis, sous quel format, et à partir de quelles informations issues de la conversation. Le rôle du modèle IA peut alors être de reformuler, résumer, catégoriser ou scorer certaines réponses pour remplir ce schéma.

Ensuite, ces données peuvent être exportées sous un format compatible avec l'ERP, par exemple en JSON, CSV ou via une API. Le point important est que la conversation libre doit être cadrée par une logique d'entretien suffisamment structurée. Sinon, les sorties risquent d'être trop variables pour être vraiment exploitables dans un système métier.

### 5. Quelles sont les principales contraintes légales, notamment RGPD, liées à l’automatisation d’entretiens vocaux ?

L'automatisation d'entretiens vocaux implique le traitement de données personnelles. Cela signifie qu'il faut être particulièrement attentif à la manière dont les données sont collectées, stockées, utilisées et éventuellement transmises à des services tiers. Le premier point important est la transparence. La personne interrogée doit savoir qu'elle échange avec un système automatisé et comprendre ce qui est fait de ses données.

Il faut aussi respecter le principe de minimisation. Cela veut dire qu'il ne faut récolter que les données réellement utiles au processus. Il faut également définir une durée de conservation cohérente et éviter de garder des données inutiles trop longtemps.

Un autre enjeu important concerne l'hébergement et les fournisseurs externes. Si certaines briques techniques reposent sur des services cloud, il faut vérifier où transitent les données et dans quelles conditions elles sont traitées. Dans un contexte professionnel, cela peut devenir un critère de choix technique à part entière.

Enfin, il faut aussi réfléchir à la place de l'humain dans le processus décisionnel. Même si l'agent vocal automatise une première étape, il paraît important de ne pas laisser une décision sensible reposer uniquement sur un système automatisé sans contrôle humain.

## Résultat de l'expérimentation

L'expérimentation a été formatrice, même si elle n'a pas pris la forme d'un prototype fonctionnel complet. Le fait de modéliser une architecture complète m'a obligé à relier les différentes briques techniques entre elles et à sortir d'une logique purement théorique. Cela m'a permis de mieux visualiser ce qui se passe entre la prise de parole de l'utilisateur, la transcription, le traitement par le modèle IA, la restitution vocale et l'export des données.

Ce travail m'a aussi aidé à comprendre que la difficulté ne réside pas seulement dans le choix d'un bon outil, mais surtout dans l'assemblage cohérent de l'ensemble. J'ai également mieux compris les compromis à faire entre rapidité de mise en place, qualité technique, maîtrise des données et complexité d'intégration.

Sur ce point, l'expérimentation a bien rempli son rôle, car elle m'a permis de réduire une partie des incertitudes techniques que j'avais au départ. Elle m'a aussi montré que certaines questions devront être approfondies dans le cadre du travail de bachelor, notamment le lien entre la logique conversationnelle et la structuration des données métier.

## Investissement

Dans l'ensemble, le temps investi est resté assez proche de ce que j'avais prévu au départ. La répartition initiale m'a servi de cadre utile, même si dans la pratique certains aspects ont demandé plus de temps que prévu. C'est notamment le cas de l'analyse comparative des architectures, car il ne suffisait pas de lister des solutions. Il a fallu comprendre leurs implications concrètes dans le cadre du projet Batmaid.

La partie liée à l'UX vocale a pris un peu moins de temps que ce que j'imaginais, car elle était moins centrale dans cette phase de recherche que la compréhension de la stack technique elle-même. En revanche, la réflexion sur les données, l'intégration ERP et les contraintes légales a pris davantage de place que prévu, car ces sujets sont directement liés à l'usage réel de la solution dans l'entreprise.

Au final, cet écart reste logique. Il montre surtout que la planification de départ était utile, mais qu'une auto-formation demande de rester souple pour approfondir les points qui s'avèrent plus complexes que prévu.

## Réflexion sur la méthode d'auto-formation

Cette auto-formation m'a montré plusieurs avantages. Le principal est la liberté de pouvoir orienter mes recherches vers un sujet directement lié à mon futur travail de bachelor. Cela rend l'apprentissage plus motivant et plus concret. J'ai aussi apprécié le fait de pouvoir avancer à mon rythme, en approfondissant certains points techniques selon mes besoins réels.

En revanche, l'auto-formation a aussi des limites. Lorsqu'on découvre un sujet complexe, il est parfois difficile de savoir si l'on va assez loin, si l'on choisit les bonnes sources ou si l'on comprend correctement les enjeux techniques. Il existe aussi un risque de se disperser, surtout quand le sujet touche à la fois à l'IA, au vocal, aux données, à l'UX et à l'intégration métier.

Dans mon cas, le fait d'avoir défini des objectifs SMART m'a aidé à garder une ligne directrice. Cela m'a permis de mieux cadrer mes recherches et de donner une forme plus concrète à un sujet qui aurait autrement pu rester trop large.

## Conclusion

Cette auto-formation m'a permis de mieux comprendre ce qu'implique concrètement la création d'un agent vocal IA dans un contexte professionnel. J'ai appris qu'un tel projet ne se résume pas au choix d'un modèle IA ou d'une API vocale. Il faut aussi penser l'architecture dans son ensemble, le traitement des données, les contraintes de multilinguisme, les enjeux légaux et l'exploitation finale des résultats.

La principale leçon que je retiens est que la stack technique doit être pensée en fonction de l'usage métier. Dans le cas de Batmaid, l'objectif n'est pas simplement de créer un agent vocal innovant, mais de concevoir une solution capable d'automatiser une étape réelle du processus tout en produisant des données exploitables et fiables.

Pour mon travail de bachelor, cette phase préparatoire a donc une vraie utilité. Elle me permet d'aborder le sujet avec une vision plus structurée, de mieux identifier les risques techniques et de clarifier les axes sur lesquels je devrai concentrer mes efforts par la suite. Elle confirme aussi que l'étude de la stack technique est une bonne porte d'entrée pour préparer le projet de manière sérieuse.

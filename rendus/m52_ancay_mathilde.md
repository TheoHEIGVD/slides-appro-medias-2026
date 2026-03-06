# M52-2 ANCAY MATHILDE - LANGGRAPH

# ETAT INITIAL ET OBJECTIFS À RENDRE POUR LE 23 FEVRIER 23h59

## Mon sujet d'étude est ...

Pour ce cours d'approfondissement, j'ai décidé de me plonger dans l'étude de LangGraph. Il s'agit d'un framework Open Source qui facilite l'intégration d'agent LLMs dans des applications. Il s'agit d'une extension de LangChain.

### Contexte

Ce choix est justifié par le fait que je vais devoir implémenter des agents en utilisant cette technologie durant mon travail de Bachelor, s'intitulant : "Intelligence artificielle pour comprendre l’activité des équipes de développement". Cette technologie est imposée par le cadre de l'entreprise. Il s'agira d'implémenter et de configurer des agents permettants la synthèse d'évènements GitHub afin de comprendre et analyser l'avancée des équipes.

## État initial

Pour le moment, je n'ai aucune connaissance de LangGraph en lui-même. Ce framework existe en Python ou en Typescript. Au vu de mes connaissances et des besoins métiers de l’entreprise pour laquelle je ferai mon TB, j’opterai pour la version Typescript. Cependant, cette dernière est plus récente, il sera donc parfois nécessaire de me documenter avec des exemples basé sur le Python par moment, la documentation disponible étant plus fournie. De plus, je n’ai encore jamais travaillé dans ce domaine. Ce contexte implique que je devrais prendre du temps pour comprendre les bases du framework et son fonctionnement avant de pouvoir entrer dans la pratique. 

## Objectifs

1. Connaître et comprendre le chapitre “core components” de LangChain, en lisant la documentation et en créant ma propre documentation. L’objectif est atteint si tous les éléments du chapitre ont été étudiés, documentés avec une définition et illustrés (schéma ou exemple).
2. Connaître et comprendre la notion de Models et de Tools de LangGraph en lisant la documentation et en créant ma propre documentation. L’objectif est atteint si tous les éléments du chapitre ont été étudiés, documentés avec une définition et illustrés (schéma ou exemple).
3. Lire et comprendre le chapitre “Capabilities” de la documentation LangGraph et créer ma propre documentation. L’objectif est atteint si tous les éléments du chapitre ont été étudiés, documentés avec une définition et illustrés (schéma ou exemple).
4. Connaître et comprendre ce qui assemble et différencie LangGraph et LongChain en dessinant un schéma décrivant comment ils s’entrecroisent. L’objectif est réussi si la schématisation est légendée, claire et sourcée. 
5. Installer une première instance fonctionnelle LangGraph en suivant la documentation officielle. L’objectif est atteint si l’instance est fonctionnelle. 
6. Configurer cette première instance en lui ajoutant un premier contexte et un outil. L’objectif est atteint si la configuration est fonctionnelle (c’est-à-dire que l’agent les prend en compte). 
7. Tenir une documentation écrite de ma phase pratique de mon étude de LangGraph en tenant un journal de bord, où j’y écrirai mes processus, mes sources d’exemples, réflexions et choses utiles. L’objectif est atteint si le journal de bord est consistant et contient au moins 10 éléments utiles sur ma démarche et mes recherches. 

Tous les objectifs doivent être atteints d’ici le moment du rendu du 6 mars.

## Démarche

Afin d’organiser mon étude, je vais débuter par une phase théorique, suivie d’une phase pratique. Une première phase, d’étude de la documentation LangChain (nécessaire pour la compréhension de LangGraph), étude de la documentation de LangGraph, finalement, travail pratique de la création de mon instance de LangGraph.

| Sujet | Objectifs concernés | Temps consacré | Livrable |
| --- | --- | --- | --- |
| Lecture et documentation de LangChain | 1 | 4 heures | Documentation de LangChain |
| Lecture et documentation de LangGraph | 2, 3, 4 | 12 heures | Documentation de LangGraph |
| Installation de ma première instance de LangGraph | 5 | 9 heures | Code source de la première instance |
| Configuration et utilisation d’outil | 6 | 8 heures | Code source de la configuration |
| Rédaction d’un rapport sur la phase pratique de l’étude de LangGraph | 7 | 3 heures | Journal de bord |

## 5 questions

1. Quelles sont les responsabilités respectives de LangChain et de LangGraph, et à quel niveau s’articulent-ils dans une architecture d’agent ?
2. Quel rôle jouent les Models et les Tools dans LangGraph, et comment interagissent-ils avec un agent ?
3. Que recouvre la notion de “capabilities” dans LangGraph, et quels types de comportements permettent-elles d’implémenter ?
4. Quelles sont les étapes nécessaires pour installer et exécuter une première instance fonctionnelle de LangGraph ?
5. Comment configurer un agent LangGraph en lui fournissant un contexte et un outil, et comment vérifier qu’ils sont pris en compte ?

## Expérimentation

L’expérimentation consistera à réaliser un POC en suivant [la documentation officielle](https://docs.langchain.com/oss/javascript/langgraph/install) et des [tutoriels](https://academy.langchain.com/courses/intro-to-langgraph) de LangGraph afin de créer une première instance locale fonctionnelle en Typescript. Cette instance prendra la forme d’un chat, auquel seront ajoutés un contexte et un outil. L’objectif est de vérifier que l’agent est capable de prendre en compte le contexte fourni et d’utiliser l’outil lors de son exécution. La réussite du POC sera validée par l’exécution correcte du graphe et par des tests manuels démontrant l’utilisation effective du contexte et de l’outil.

---

# RAPPORT FINAL À RENDRE POUR LE 6 MARS 23h59

## Retour sur l'état initial

Cette auto-formation a été très intéressante, autant pour les connaissances acquises que pour le processus d’apprentissage.

Tout d'abord, d'un point de vue personnel, j'ai l'impression d'avoir atteint la plupart des objectifs: 
- **Objectifs 1 - 2 - 3 :** Ceux-ci constituaient la partie "théorique" de mon auto-formation. J'ai réussi à lire et documenter l'ensemble des points que je souhaitais parcourir. Ces premiers objectifs sont atteints. 
- **Objectif 4** : Atteint, mais pas de la façon que j'avais prévu. Je voulais faire un schéma, mais un très bon schéma était déjà fourni par la documentation. Je n'ai pas eu besoin de réaliser le mien. 
- **Objectif 5-6** : Atteint, je suis parvenue à faire fonctionner une instance locale minimale, et ajouter des outils à un agent. 
- **Objectif 7** : Partiellement atteint, j'ai pris quelques notes de ma démarche pratique, mais de façon très lacunaire, par manque de temps. 

## Réponses aux 5 questions

- _Quelles sont les responsabilités respectives de LangChain et de LangGraph, et à quel niveau s’articulent-ils dans une architecture d’agent ?_  
    LangChain et LangGraph se complètent dans leur utilisation pratique. Alors que LangChain permet une orchestration rapide et simple d'agents, LangGraph permet de les configurer de façon plus précise. Cependant, ils ne s'excluent pas l'un et l'autre : en développant avec LangGraph, on utilise des composants LangChain de plus haut niveau.
    
- _Quel rôle jouent les Models et les Tools dans LangGraph, et comment interagissent-ils avec un agent ?_  
    Les models sont les LLMs. Ceux-ci permettent de générer des réponses. Les tools sont des fonctions déterminées d’actions, que peuvent déclencher les LLMs. Les tools sont appelés via un tool calling du LLM.
    
- _Que recouvre la notion de “capabilities” dans LangGraph, et quels types de comportements permettent-elles d’implémenter ?_  
    Les capabilities de LangGraph regroupent des fonctionnalités possibles des agents orchestrés par LangGraph. Il y a par exemple la persistence, qui permet de conserver un état de mémoire entre plusieurs exécutions de l'agent. Il y a également la durable execution, qui permet de sauvegarder le progrès d'un agent à un instant T afin de pouvoir interrompre puis reprendre son exécution.
    
- _Quelles sont les étapes nécessaires pour installer et exécuter une première instance fonctionnelle de LangGraph ?_  
    Si l'on souhaite faire une instance en pouvant la monitorer avec LangSmith, il est nécessaire d’y créer une clé API. Puis, assez simplement, il faut exécuter une commande qui va créer un nouveau projet LangGraph. Il faudra ensuite configurer les clés API nécessaires (LangSmith, LLMs). À partir de là, on peut commencer à définir notre agent. Pour un agent simple, on peut d'abord créer une instance de LLM, créer un outil puis le mettre à disposition. Le tout sera ensuite associé dans des nodes correspondants. Il suffit ensuite d’exécuter les commandes pour tester son agent.
    
- _Comment configurer un agent LangGraph en lui fournissant un contexte et un outil, et comment vérifier qu’ils sont pris en compte ?_  
    Pour configurer un agent LangGraph avec un contexte et un outil, il faut d'abord définir un état ou un message initial qui servira de contexte pour l’agent. Ensuite, un outil est défini sous forme de fonction et mis à disposition de l’agent. Celui-ci peut alors décider d’utiliser cet outil via le tool calling. Pour vérifier qu’ils sont bien pris en compte, il est possible d’exécuter l’agent et d’observer son comportement (par exemple avec LangSmith) afin de vérifier que le contexte est utilisé et que l’outil est appelé lorsque nécessaire.
	 
## Résultat de l'expérimentation

L'expérimentation a été formatrice, mais pas vraiment aisée. Comme décrit dans la première partie du document, la plupart de la documentation est dédiée à la version Python du framework. Un des tutoriels proposés par la documentation officielle était dans ce langage. Puisqu'il semblait être le plus riche proposé, je me suis dit que j'allais tout de même le suivre. Cependant, je n'avais jamais fait de Python de ma vie, et cela a créé beaucoup de difficultés. 
J'ai perdu pas mal de temps à essayer de configurer mon environnement pour que je puisse effectuer le tutoriel correctement. De plus, il y avait des notions inhérentes au langage qui me manquaient. Je devais faire des recherches complémentaires qui me ralentissaient.
Après avoir passé cette première barrière, le tutoriel s'est montré vraiment intéressant et instructif, donc ce ne fut pas une perte de temps inutile. Il m'a permis de lancer des instances d'agents en local, avec des agents de plus en plus complexes, et qui, à chaque fois comprenaient des nouveaux éléments de théorie. Cette expérimentation m'a aidé à concrétiser les points de théorie que j'avais vus en amont et à les clarifier. 

## Investissement

La plupart des objectifs ont été atteints. Cependant, je ne pense pas avoir tout à fait atteint les 36 heures qui devaient y être allouées, par manque de temps à disposition. Cela a créé de la frustration, car j'aurais souhaité pouvoir m'y consacrer pleinement. J'ai bien atteint la plupart des objectifs, donc je suis malgré cela très contente de mon travail. J'ai été complètement investie dans mon implication pour ce cours, en lui allouant le plus de temps possible.

## Réflexion sur la méthode d'auto-formation

J'ai constaté que mes premiers objectifs, purement théoriques, étaient intéressants. Mais j'ai ressenti une frustration : j'aurais du prévoir de passer plus rapidement à la pratique. Même si la théorie est indispensable, j'avais envie de tester, configurer, etc. Je saurai, à l'avenir, que lorsque je veux apprendre un nouveau framework, je dois commencer par la documentation, mais ne pas trop m'y attarder dans des points trop complexes dès le départ. Il est important de connaître ce que permet de faire une technologie, mais de s'y plonger uniquement lorsque j'en ai besoin concrètement. 
Malgré la contrainte de la documentation en Python, je trouve que j'ai bien réussi à transposer mes acquis dans la version Typescript. 
## Conclusion

Même si dans les faits, la plupart des objectifs ont été atteints, cette première approche du framework a eu un effet double. D'un côté, beaucoup de choses se sont éclaircies très vite. Ce fut très satisfaisant et passionnant rapidement. Cependant, cela a aussi mis en lumière toutes les choses qui me restent à apprendre. Cela a provoqué un sentiment d'immensité à devoir encore parcourir. Malgré cela, je suis très satisfaite de cette première session d'étude du framework. Je me réjouis d'approfondir mes connaissances du système. 
Cette auto-formation a un très bel impact sur mon TB : elle a permis d'éclaircir beaucoup de notions qui m'étaient encore pour le moment très floues. Je sais maintenant avec beaucoup plus de clarté et de sérénité ce qui m'attend, comment je vais devoir m'y prendre et ce que je ferai durant la pré-étude. J'ai même déjà un semblant de schéma de l'agent que j'y développerai. Je pense compenser compléter ma connaissance sur le sujet d'ici la pré-étude. 

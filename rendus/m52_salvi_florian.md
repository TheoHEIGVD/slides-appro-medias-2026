# M52-1/2 SALVI FLORIAN - ARCHITECTURES CI/CD DANS GITHUB ACTIONS

# ETAT INITIAL ET OBJECTIFS À RENDRE POUR LE 23 FEVRIER 23h59

## Mon sujet d'étude est la conception d'architecures CI/CD (Continuous Integration/Deployment) sécurisées dans les GitHub Actions et intégration de services externes

**_Décrire le sujet_**

_Le sujet doit être en lien avec votre Travail de Bachelor, avec une composante "technique". Ce cours doit vous permettre, concrètement, de monter en puissance sur un sujet utile pour votre TB._

Ce travail se concentre sur la conception d'architectures CI/CD sécurisées et integrées aux GitHub Actions. Capables d'intégrer des services externes (API, LLM, SaaS, …), ces architectures doivent aussi respecter certains principes :
- Gestion des informations sensibles et secrètes
- Déclenchement conditionnels et automatisés
- Modularité et maintenabilité
- Isolation de certaines ressources et dépendances

### Contexte

_Pourquoi avez-vous choisi ce sujet précis ? Quels avantages pour votre TB ? En quoi c'est intéressant pour votre futur professionnel_

Mon Travail de Bachelor porte sur l'automatisation de processus techniques dans les projets de développement web. Notamment, la génération de tests, de documentation, la vérification automatique des dépendances et de leurs versions. Ces automatisations seront intégrées dans des pipelines CI/CD et devront parfois intéragir avec des services externes (API, LLM, …). L'intégration de ces services met en avant différentes problématiques liées à la sécurité, aux permissions et à la gestion de clés.

Ce sujet me permet :
- d'acquérir et de peaufiner mes compétences DevOps
- de mieux comprendre l'architecture CI/CD moderne
- de concevoir des architectures robustes et sécurisées
- de développer des compétences qui valorisent mon profil de futur développeur full-stack
- de mieux appéhender les tâches de mon Travail de Bachelor

## État initial

_Quel niveau de connaissances et de pratique avez-vous dans le sujet aujourd'hui ? Quelles implications pour vos objectifs et démarches pour cette auto-formation ?_

À ce jour, mes connaissances techniques dans ce domaine sont limitées. J'ai eu l'occasion de travailler avec GitHub et du déploiement automatisé quelques fois (Render & Netlify) et d'implémenter des pipelines très modestes lors des cours d'Architecture Orientée Web. Cependant, j'ai utilisé les GitHub Actions à une seule occasion et n'ai jamais dû intégrer de services externes. Je me place au niveau débutant dans le spectre de connaissances d'un DevOps.

Durant mon auto-formation, je devrai développer mes connaissances structurelles et sécuritaires des pipelines de développement et, comprendre et pratiquer les GitHub Actions.

## Objectifs

_Attention à formuler des objectifs SMART (spécifiques, mesurables, atteignables, réalistes, temporellement mesurables)._

_Expliquez comment vous allez valider l'atteinte des objectifs. Vos critères de réussite concrets._

**Comprendre comment fonctionnent les GitHub Actions et les GitHub secrets d'ici au 6 mars**, ainsi que les concepts y étant liés (déclenchement conditionnel, isolation, …)
*Critères de réussite* : Je suis capable d'expliquer, avec mes mots, ce que sont ces différents concepts et leur fonctionnement.

**Comprendre comment intégrer des services externes aux pipelines d'ici au 6 mars**, afin d'implémenter des workflows complexes, performants et sécurisés.
*Critères de réussite* : J'ai développé un POC d'un work flow qui inclue, à minimam, 1 service externe, 1 déclencheur, et la gestion des erreurs.

**Débuter la rédaction d'un guide/rapport technique d'ici au 6 mars**, qui me permettra de mieux structurer et appréhender mon Travail de Bachelor et sur lequel je pourrai me baser pour l'implémentation de diverses solutions durant celui-ci.
*Critères de réussite* : Le guide contient une structure, une liste détaillées des problématiques, workflows et outils. Il est prêt à servir de référence pour l'implémentation.

## Démarche

_Quelles étapes et comment allez-vous répartir l'investissement des 36h disponibles pour le cours ?_

**Phase 1 - Recherches (8h)** :
- Étude approfondie des GitHub Actions
- Étude des GitHub Secrets
- Étude des architectures CI/CL, de la sécurité et des permissions
- Analyse des risques
- Sources : documentation officielle, repo Git, YouTube, formations en ligne, …

**Phase 2 - Conception (8h)** :
- Réalisation d'un diagramme d'architecture
- Définition de déclencheurs
- Définition des permissions

**Phase 3 - Implémentation (12h)** :
- Création d'un repository
- Implémentation :
    - Workflow principal
    - Un job de test
    - Un job d'appel sur une API externe
    - Gestion des secrets

**Phase 4 - Tests (4h)** :
- Tests des PULL Request externes
- Tests des appels d'API
- Tests des erreurs d'API
- Analyse du "comportement" du workflow

**Phase 5 - Guide/rapport technique (4h)** :
- Identification des limites
- Analyse de la sécurité du workflow
- Début de rédaction d'un guide/rapport technique pour la suite de mon TB

## 5 questions

_Rédigez 5 questions qui devront vous permettre de tester l'acquisition des nouvelles compétences._

1. Comment utiliser et configurer les GitHub Actions et les GitHub Secrets dans un workflow ?
2. Quels sont les différents type de déclencheurs (triggers) de GitHub Actions et comment choisir celui à utiliser selon la situation ?
3. Comment intégrer un service externe dans une pipeline ? Et comment gérer les erreurs et la sécurité ?
4. Comment isoler et modulariser les jobs dans un workflow GitHub Actions ?
5. Comment effectuer des tests pour valider le fonctionnement d'un pipeline et la gestion des erreurs ?

## Expérimentation

_Expliquez les contours de la réalisation d'un élément concret (POC, tutoriel) que vous allez réaliser pour valider votre apprentissage_

Afin de concrétiser mon auto-formation dans ce domaine, je souhaite produire deux livrables qui me permettront d'expérimenter, de tester et de m'accompagner pour la suite de mon Travail de Bachelor.

1. **Un POC** comprenant un repository, une architecture CI/CD comprenant plusieurs jobs, la gestion des permissions, l'intégration d'un service externe et la gestion des erreurs. Il explorera plusieurs concepts susmentionnés tels que l'isolation des jobs, le déclenchement conditionnels, …
2. **Un guide/rapport technique** dans lequel je décrirai les différents concepts appréhendés, les différentes étapes effectuées, les limites et forces du workflow développé et les bonnes pratiques du domaine.

---

# RAPPORT FINAL À RENDRE POUR LE 6 MARS 23h59

## Retour sur l'état initial 

_Quel bilan entre les attentes, les objectifs et la réalité de cette auto-formation ?_

De manière générale, les objectifs ne sont que partiellement atteint. Je n'ai pas réussi à allouer l'entierté du temps demandé durant l'intervale très court entre les deux cours. J'ai pu me renseigner sur le sujet grâce à de nombreuses documentations techniques et contenus vidéos, cependant, je n'ai pas terminé le POC et le guide technique que je visais à réaliser durant le premier rendu.

## Réponses aux 5 questions

_Répondez aux 5 questions posées plus haut. Pour chacune d'elles, si nécessaire, complétez ou améliorez la question._

1. Les GitHub Actions sont configurées dans les fichiers (YALM) placés dans le dossier .github/workflows. On y définit les événements déclencheurs, les jobs et les différentes étapes d'exécution. Les GitHub Secrets permettent de stocker des informations sensibles et de les utiliser dans les worflows (par ex. des tokens ou clés d'API).

2. Les GitHubs Actions proposent plusieurs types d'événements déclencheurs. Notamment, les push, pull request, workflow dispatch, schedule, release et pleins d'autres. Le choix dépend du contexte. Par exemple, pour automatiser des tests lors des push ou valider du code présent dans une pull request.

3. Intégrer un service externe dans une pipeline se fait généralement grâce à des requêtes API ou des outils CLI directement intégrés dans une étape du worflow. L'utilisation des secrets et la mise en place de code vérifiant les codes de retour ou l'arrêt des jobs garantissent un bon fonctionnement.

4. Les jobs peuvent être isolés dans un workflow GitHub Actions en les séparant en différents tâches qui peuvent être exécutées sur des environnements indépendants (des runners). Des dépendances peuvent être définies entre elles (needs) et on peut facilement réutiliser des worflows ou actions. Par exemple, une tâche "build" peut être dépendante de la réussite d'une tâche "test".

5. Malheureusement, je n'ai pas réussi à atteindre la partie de mon auto-formation qui traite du test des pipelines. De ce que j'ai compris, une pipeline peut être vérifié grâce à l'analyse des logs et grâce à la simulation de certaines erreurs (par exemple, un code HTTP !== 200 retourné par une requête API déclenche un exit).

## Résultat de l'expérimentation
_Expliquez comment s'est passé l'expérimentation, a-t-elle été formatrice ? sur quels aspects ?_

L'expérimentation s'est bien déroulée, bien qu'elle n'ait pas été réalisée jusqu'au bout. J'ai effectué la mise en place du repository et la conception de l'architecture du workflow mais, le POC n'a pas pu être complété. L'intégration d'un service externe est encore en cours de travail et la partie test doit être entièrement travaillée.

Malgré cela, cette expérimentation m'a été fortement formatrice. Elle m'a permis de mieux appréhender la logique et le fonctionnement des pipelines CLI/CD, la modularité des jobs et les différents outils d'automatisation proposés par GitHub. C'est une base solide sur laquelle je pourrais construire mon Travail de Bachelor.

## Investissement

_Détaillez le temps passé et les écarts avec l'investissement imaginé au départ, expliquez pourquoi._

Au total, je n'ai malheureusement pu accorder que 23 h 45 sur les 36 h demandées. Cela est notamment dû à l'aménagement des cours qui offrent peu de temps entre l'initialisation du cours et le rendu, au travail à fournir pour le cours à option et à mon emploi. 36 h équivallent à 4 jours de travail complet.

Temps réellement passé :

**Phase 1 - Recherches (11h au lieu de 8h)**  
**Phase 2 - Conception (6h au lieu de 8h)**  
**Phase 3 - Implémentation (6h45 au lieu de 12h)**  
**Phase 4 - Tests (0h au lieu de 4h)**  
**Phase 5 - Guide/rapport technique (0h au lieu de 4h)**  

## Réflexion sur la méthode d'auto-formation

_En regard des avantages et inconvénients de l'auto-formation, qu'avez-vous constaté ?_

### Avantages
- Je suis autonome et peux ainsi adapter les horaires comme cela m'arrange.
- Le choix des thèmes abordés et le temps qui y est accordé peuvent être aménagés.
- Pas de pression liée au timing, à d'enventuelles évaluations ou rendus.

### Inconvénients
- Je n'ai pas de guarantie qui certifie que ma compréhension des outils et des concepts est correcte.
- Il m'est compliqué de me poser des limites de temps. Il arrive donc, parfois, que je passe trop de temps à me concentrer sur un concept et en perde sur un autre.
- Se former soi-même nécessite une discipline que je n'ai pas tout le temps.

## Conclusion

_Quelles leçons avez-vous apprises et pourquoi ?_

J'ai appris que se renseigner longuement sur un outil, une technologie ou un concept avant de se lancer dans la mise en pratique est très importante. Sans cela, nous pouvons plus facilement faire face à des erreurs ou à des bloquages qui seront plus difficilement résolus.

Cela a consolidé ma croyance qui dit que la pratique est la partie la plus désisive d'une processus de formation. C'est elle qui montre si les concepts et outils sont réellement compris et si certains aspects doivent encore être travaillés.

_Quelles implications pour votre TB et pourquoi ?_

Pour mon Travail de Bachelor, ces connaissances constituent une base solide et importante. Elles me permettront de construire et intégrer des pipelines solides et capables d'automatiser certaines tâches techniques (tests; génération de documentation; vérification de dépendances; …). 


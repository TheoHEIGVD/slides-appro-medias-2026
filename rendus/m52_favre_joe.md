# M52-1/2 FAVRE JOÉ - Maîtrise des Cartes interactives sur mobile

# ETAT INITIAL ET OBJECTIFS À RENDRE POUR LE 23 FEVRIER 23h59

## Mon sujet d'étude est ...

Mon sujet d'étude porte sur l'élaboration d'une carte interactive dans un prototype haute-fidélité pour une application mobile d'un festival. Je me concentre sur trois axes principaux : la structuration de la carte elle-même, comprenant le fond, les points d'intérêt, la légende et les actions possibles ; la définition de ses différents états, qu'il s'agisse de la carte neutre, d'un point d'intérêt sélectionné, des favoris visibles ou des filtres actifs ; et enfin l'intégration de la carte dans des parcours complets au sein du prototype, comme le flux accueil → carte → fiche → retour, ou encore carte → favoris → fiche. Ce sujet est directement lié à mon Travail de Bachelor, qui comporte une forte dimension de conception d'interface cartographique et de navigation spatiale dans un contexte mobile.

### Contexte

**Pourquoi ce sujet ?**

La carte interactive est un élément central de mon projet : elle doit aider les utilisateurs à se repérer et à accéder rapidement à des informations pertinentes. Une carte mal conçue peut rendre l'application inutilisable, même si le reste de l'interface est de bonne qualité. Élaborer une carte interactive solide au niveau du prototype me permet de tester et valider les parcours de navigation avant toute implémentation technique.

**Avantages pour mon Travail de Bachelor**

Travailler ce sujet renforce la qualité du prototype haute-fidélité livré dans le cadre du TB. Cela améliore également la pertinence des tests utilisateurs en offrant des scénarios réalistes centrés sur l'orientation, et alimente la réflexion sur l'architecture de l'information, la hiérarchie visuelle et la navigation spatiale.

**Intérêt pour mon futur professionnel**

Ce sujet représente une compétence réutilisable dans des projets d'applications mobiles touchant à l'orientation, au tourisme, à l'événementiel ou à la mobilité. Il développe la capacité à concevoir des interfaces cartographiques compréhensibles, testables et prêtes à être discutées avec des développeurs, constituant ainsi un atout concret dans un portfolio UX/UI qui démontre la prise en charge de cas d'usage complexes.

## État initial

**Connaissances actuelles**

Je maîtrise les bases de Figma, notamment les maquettes, l'auto-layout, les composants et les prototypes simples. Je sais concevoir des écrans mobiles tels que des listes, des fiches d'information et la navigation principale. J'ai déjà créé des écrans de type carte, mais de manière plutôt statique, avec un fond, des pins et une fiche séparée.

**Points à développer**

Il me reste à définir et gérer plusieurs états de la carte dans le prototype, qu'il s'agisse de l'état neutre, de la sélection, des favoris ou des filtres. Je dois également intégrer la carte dans des parcours complets allant de l'entrée à l'interaction jusqu'à la sortie, de façon à ce qu'ils soient compréhensibles sans dépendre d'explications orales. L'objectif est de rendre la carte testable en conditions de tests utilisateurs, en termes de clarté, de lisibilité et de compréhension des actions disponibles.

**Implications pour l'auto-formation**

Cela implique de réaliser un benchmark d'applications intégrant des cartes interactives, de structurer soigneusement les frames et composants liés à la carte dans Figma, et de prévoir du temps pour itérer sur celle-ci après les premiers retours utilisateurs.

## Objectifs

1. **D’ici au 15 mars 2026**, concevoir dans Figma au moins **2 versions** d’un écran de carte interactive (mise en page, points d’intérêt, légende, zones interactives) et sélectionner, avec un retour d’un pair ou d’un encadrant, la version la plus adaptée à un usage mobile.

2. **D’ici au 31 mars 2026**, définir et modéliser au moins **4 états** de la carte dans le prototype (carte neutre, point d’intérêt sélectionné, carte avec favoris visibles, carte avec un filtre actif) et les relier par des interactions claires (clic sur point, retour, activation de favori).

3. **D’ici au 20 avril 2026**, intégrer la carte interactive dans au moins **2 parcours complets** du prototype (par exemple :
    - accueil → carte → fiche → retour,
    - carte → point favori → fiche → retour),
        
   de manière à pouvoir les tester sans explication orale.
        
4. **D’ici au 30 avril 2026**, faire tester ces parcours centrés sur la carte avec au moins **5 personnes** et collecter au minimum **10 retours qualitatifs** sur la compréhension de la navigation, la lisibilité de la carte et la clarté des interactions.

5. **D’ici au 23 mai 2026**, documenter dans le rapport de Travail de Bachelor une section dédiée à **l’élaboration de la carte interactive** dans le prototype (structure, états, interactions, limites, pistes d’amélioration) illustrée par au moins **3 captures d’écran commentées**.

**Validation des objectifs**

Les trois premiers objectifs seront validés par l'existence d'écrans, d'états et de parcours complets fonctionnels dans Figma. Le quatrième objectif le sera par la réalisation effective de tests auprès de cinq personnes ainsi que par la synthèse des retours obtenus. Enfin, le cinquième objectif sera validé par la rédaction d'une section dédiée dans le rapport, accompagnée des captures d'écran correspondantes.

## Démarche

**Phase 1 – Recherche et cadrage (6h)**

- Benchmark d’applications mobiles utilisant des cartes interactives (navigation, orientation, découverte de lieux).
- Identification des éléments récurrents : points d’intérêt, favoris, filtres, zoom, panneaux d’information.
- Définition des besoins spécifiques de mon projet (type de points, densité, contexte d’usage).

**Phase 2 – Conception des écrans et états de carte (10h)**

- Création dans Figma de plusieurs variantes d’écran de carte (position des éléments, lisibilité, légende).
- Définition des états de la carte :
    - carte neutre,
    - point d’intérêt sélectionné,
    - favoris visibles,
    - filtres activés.
- Création/adaptation de composants : markers, panneaux d’information, icônes de favoris, filtres.

**Phase 3 – Intégration dans les parcours du prototype (10h)**

- Choix des parcours utilisateurs clés impliquant la carte.
- Mise en place des liens entre écrans et états pour que les parcours soient fluides et cohérents.
- Vérification de la cohérence avec la navigation globale de l’application (menu, retour, etc.).

**Phase 4 – Tests utilisateurs centrés sur la carte (6h)**

- Définition de scénarios de test :
    - trouver un point d’intérêt,
    - ouvrir ses détails,
    - ajouter/retirer un favori,
    - comprendre un filtre.
- Conduite de tests avec 5 personnes.
- Collecte et synthèse des retours (clarté, difficultés, suggestions).

**Phase 5 – Synthèse et documentation (4h)**

- Rédaction d’une synthèse sur l’élaboration de la carte interactive :
    - choix de design,
    - raisons des décisions,
    - limites,
    - améliorations suite aux tests.
- Intégration de captures d’écran et éventuellement de petits schémas dans le rapport de TB.

## 5 questions

1. Quels sont les éléments indispensables à représenter sur une carte interactive (points d’intérêt, favoris, légende, filtres) et comment les hiérarchiser visuellement pour éviter la surcharge ?
2. Comment définir et organiser les différents états d’une carte interactive (neutre, point sélectionné, favoris affichés, filtres actifs) pour qu’ils restent compréhensibles dans un prototype haute-fidélité ?
3. Quels parcours utilisateurs impliquant la carte doivent absolument être présents dans un prototype pour permettre des tests utilisateurs pertinents sur l’orientation et la navigation ?
4. Comment évaluer, lors de tests utilisateurs, si la carte interactive du prototype aide réellement les participants à se repérer et à trouver un point d’intérêt donné ?
5. Quelles limites et contraintes spécifiques au format « prototype » (et non application développée) faut-il prendre en compte lorsqu’on élabore une carte interactive, et comment les contourner ou les expliciter dans le rapport de TB ?

## Expérimentation

Je réaliserai un **prototype Figma centré sur la carte interactive** de l’application mobile.

Ce POC contiendra :

- Un écran de carte avec plusieurs points d’intérêt et éléments importants (zones/lieux clés).
- Plusieurs états de la carte :
    - carte neutre,
    - point sélectionné,
    - carte avec favoris visibles,
    - carte avec filtres activés.
- Au moins 2 parcours complets testables :
    1. accueil → carte → sélection d’un point → fiche → retour à la carte,
    2. carte → point favori → fiche → retour aux favoris.

**Modalités de validation**

- Utiliser ce POC lors de tests utilisateurs pour observer la compréhension de la carte et des interactions.
- Ajuster la structure et les états de la carte à partir des retours.
- Documenter le fonctionnement du POC (structure des frames, logique des interactions) dans une courte note ou annexe, montrant que je maîtrise l’élaboration d’une carte interactive dans un prototype haute-fidélité.Description du POC

---

# RAPPORT FINAL À RENDRE POUR LE 6 MARS 23h59

## Retour sur l'état initial

Au début, je voulais surtout que cette formation perso m'aide à décoincer la partie carte de mon prototype. Je voulais clarifier les états, les interactions et comment tout ça s'intègre dans des parcours complets. En fait, j'ai atteint ce but, mais j'ai poussé le détail plus loin que prévu. Surtout sur comment organiser visuellement les éléments (pins, favoris, filtres, légende) et comment les faire marcher ensemble dans Figma avec les composants et les variantes.

Je pensais que j'allais surtout bosser sur la mise en page de l'écran de carte et quelques interactions de base. Mais en réalité, j'ai passé pas mal de temps à définir des scénarios de test et à créer des parcours qu'on pouvait vraiment tester sans avoir besoin d'explications. Ça m'a forcé à rendre les textes, les transitions et les états intermédiaires super clairs. Je n'ai pas malheureusement pas eu le temps de réaliser les tests pour voir si mes scénarios de tests étaient bons.

Au final, j'ai partiellement atteint les objectifs que je m'étais fixés: plusieurs versions de l'écran, au moins quatre états de carte, deux parcours complets. Je n'ai malheureusement pas eu le temps comme dit précedemment de faire passer les tests et de faire la documentation. Bon, par contre, j'ai un peu dépassé le temps prévu sur certaines étapes. Cette formation perso a été plus structurante que je pensais pour mon Travail de Bachelor. Ça m'a obligé à écrire noir sur blanc des décisions qui étaient un peu floues avant.

## Réponses aux 5 questions
**1. Quels sont les éléments indispensables à représenter sur une carte interactive (points d’intérêt, favoris, légende, filtres) et comment les hiérarchiser visuellement pour éviter la surcharge ?**
Voilà ce qu'il faut absolument :

- le fond de carte (ou un plan du festival) assez simple pour que les zones importantes soient faciles à voir ;
- les points d'intérêt (POI) avec des couleurs et des icônes qui vont bien ensemble ;
- un système de favoris (une icône ou un pin spécial) qu'on voit tout de suite ;
- des filtres faciles d'accès (boutons) et une légende simple qui explique les types de lieux.

Pour l'organisation visuelle, j'ai bossé sur trois niveaux :

1. Le fond de carte, avec des couleurs discrètes pour pas faire concurrence aux POI.
2. Les points d'intérêt et ce sur quoi on se concentre (le pin sélectionné), c'est ça qu'on doit voir en premier.
3. La légende, les filtres, les infos, qui sont là pour aider sans prendre toute la place sur la carte.

Concrètement, ça veut dire :

- utiliser des couleurs plus vives et des contrastes plus forts pour les éléments cliquables (les pins, les boutons des filtres) et des couleurs plus neutres pour le fond ;
- jouer avec la taille et les formes (des pins plus gros pour les favoris ou le POI choisi, des panneaux avec un fond uni) ;
- faire une légende courte, en évitant de mettre des catégories qui servent pas à grand-chose pendant les tests.

J'ai un peu changé la question de départ pour parler de niveaux de lecture pour la carte. C'est ça qui m'a le plus aidé à éviter de surcharger l'écran.

**2. Comment définir et organiser les différents états d’une carte interactive (neutre, point sélectionné, favoris affichés, filtres actifs) pour qu’ils restent compréhensibles dans un prototype haute-fidélité ?**
Pour que les états soient faciles à comprendre, j'ai fait une sorte de mini design system dans Figma :

- un composant principal carte (un frame) qui sert de base ;
- des variantes pour les différents états (normal, point sélectionné, favoris affichés, filtres activés) ;
- des composants pour les pins, les favoris et les infos.

Les états sont rangés de façon logique :

- Normal : on voit toute la carte avec les POI, mais pas d'infos ouvertes.
- Point sélectionné : un pin change de couleur/taille et une info apparaît.
- Favoris affichés : certains POI ont une étoile ou une couleur spéciale.
- Filtres activés : on ne voit que les pins qui correspondent aux filtres, et on voit qu'il y a un filtre actif.

Dans le prototype, j'ai fait des liens entre ces états :

- si on clique sur un pin, on passe de l'état normal à l'état point sélectionné ;
- si on clique sur l'icône de favori, le pin devient un favori ;
- si on active un filtre, on voit une autre version de la carte avec seulement certains pins.

Avec les variantes et les transitions, le fichier Figma reste facile à lire, et l'utilisateur a l'impression que tout est fluide quand il teste. J'ai un peu modifié la question pour insister sur comment j'ai organisé tout ça dans Figma, pas seulement sur la théorie des états.

**3. Quels parcours utilisateurs impliquant la carte doivent absolument être présents dans un prototype pour permettre des tests utilisateurs pertinents sur l’orientation et la navigation ?**
Pour que les tests soient utiles, j'ai choisi trois parcours :

1. Découverte : accueil → carte → on choisit un point → on voit les infos → retour à la carte.
2. Favoris : carte → on choisit un point → on le met en favori → on regarde les favoris → on voit les infos → retour.
3. Filtrage : carte → on met un filtre → on choisit un point filtré → on voit les infos → retour à la carte filtrée.

Ces parcours couvrent les besoins de base :

- se repérer sur le plan du festival ;
- trouver un endroit précis (une scène, un stand) ;
- se faire un parcours perso avec les favoris ;
- comprendre comment les filtres changent ce qu'on voit.

Dans le prototype, tout devait marcher sans bugs ni endroits pas clairs. J'ai fait attention à ce que les liens soient évidents et à ce qu'il y ait un petit effet visuel à chaque action. Comme ça, les testeurs peuvent se concentrer sur la carte, pas sur les problèmes du prototype.

**4. Comment évaluer, lors de tests utilisateurs, si la carte interactive du prototype aide réellement les participants à se repérer et à trouver un point d’intérêt donné ?**
Pour voir si la carte est bien, il faudra faire attention à plusieurs choses :

- des tâches précises (trouver la scène X) ;
- des mesures simples (le temps qu'il faut pour la tâche, le nombre de clics, si les gens ont besoin d'aide) ;
- comment les gens se comportent (s'ils hésitent, s'ils cliquent sur des trucs qui ne marchent pas, s'ils oublient la légende ou les filtres).

Pendant les tests, je devrais dire aux gens de dire à voix haute ce qu'ils cherchaient et ce qu'ils comprenaient de la carte. Après chaque tâche, je dois demander :

- Qu'est-ce qui t'a aidé ?
- Qu'est-ce qui t'a embrouillé ?
- Si tu pouvais changer un truc sur la carte, ce serait quoi ?

Ces réponses m'aideront à savoir si la carte est bien organisée et facile à comprendre. Par exemple, si plusieurs personnes ne voient pas un filtre activé ou ne comprennent pas les couleurs, c'est que la carte ne les aide pas assez, même s'ils finissent par trouver ce qu'ils cherchent.

J'ai ajouté à la question des critères d'évaluation (temps, erreurs, ce que disent les gens) au lieu de juste me fier à mon impression.

**5. Quelles limites et contraintes spécifiques au format « prototype » (et non application développée) faut-il prendre en compte lorsqu’on élabore une carte interactive, et comment les contourner ou les expliciter dans le rapport de TB ?**
Un prototype (dans Figma) a des limites :

- ce n'est pas une vraie carte (on ne peut pas zoomer facilement) ;
- les interactions sont simples ;
- parfois, les transitions ne sont pas aussi fluides que dans une appli.

Pour contourner ces problèmes, j'ai :

- fait semblant de zoomer en créant plusieurs images de la carte à différents niveaux de zoom, avec des liens si on clique sur une zone ;
- testé seulement les trucs les plus importants pour se repérer ;
- expliqué clairement dans le rapport ce qui est simulé (les filtres) et ce qui serait géré par le code dans une appli.

Dans le rapport, j'ai dit pour chaque problème :

- ce qui bloque à cause du prototype (pas de géolocalisation) ;
- comment ça change les tests (on ne peut pas tester la fonction autour de moi) ;
- et, si possible, comment ça marcherait dans l'appli (on utiliserait l'API de localisation du téléphone). Ça montre que je sais comment créer la carte, même si tout n'est pas fait dans le prototype.


## Résultat de l'expérimentation
Cette expérience m'a beaucoup appris, sur la méthode et sur Figma. En faisant plusieurs états de la carte et des parcours complets, j'ai dû clarifier le rôle de chaque élément : à quoi sert la carte ? Quand est-ce qu'on a besoin de détails ? Quand est-ce que les favoris sont utiles ?

Mon seul regret est donc de ne pas avoir pu passer les tests qui m'auraient surement appris beaucoup.

J'ai aussi mieux géré Figma, en utilisant les variantes et les interactions pour que ce soit plus fluide.

## Investissement

J'ai passé un peu plus de temps que prévu, et surtout, j'ai réparti le temps différemment. J'ai donc fait :

- Recherche : un peu moins de temps, car je me suis vite concentré sur quelques applis de cartes et des tutos.
- Design : plus de temps, pour refaire les états et les composants.
- Intégration : plus de temps aussi, car si la navigation n'est pas bonne, on le voit tout de suite pendant les tests.

J'ai passé plus de temps parce que si on change un truc sur la carte, ça change tout le parcours. Mais c'est normal vu que la carte est importante dans mon projet.

## Réflexion sur la méthode d'auto-formation

C'était bien de me former tout seul, car j'ai pu regarder plein de trucs différents (tutos Figma, articles sur les tests de cartes) et les essayer tout de suite. C'était pratique de pouvoir passer de la théorie à la pratique rapidement.

Par contre, comme il n'y avait personne pour me dire quoi faire, j'ai parfois passé trop de temps sur des détails (les petites animations) au lieu de me concentrer sur la méthode (comment savoir si les tests sont réussis). J'ai dû me forcer à revenir à mes objectifs et à vérifier que chaque changement améliorait la carte.

Cette formation m'a aussi montré qu'il faut réfléchir à ce qu'on fait.

## Conclusion

Ce que j'ai appris :

- une carte interactive, ce n'est pas juste un fond et des pins. C'est un ensemble d'états, d'interactions et de parcours qui doivent marcher ensemble.
- il faut bien organiser les éléments et éviter de surcharger la carte pour que les gens s'y retrouvent facilement.

Pour mon Travail de Bachelor, ça veut dire :

- que j'ai une bonne base pour le rapport (la structure de la carte, les états, les interactions, les problèmes) ;
- que je sais me former tout seul, organiser mon travail et tester ce que je fais. C'est utile pour mon futur métier.

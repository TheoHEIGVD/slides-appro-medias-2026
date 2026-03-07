# M52-1/2 JOLIAT Thibaud - Intégration d'expériences 3D interactives pour l'horlogerie

# ETAT INITIAL ET OBJECTIFS À RENDRE POUR LE 23 FEVRIER 23h59

## Mon sujet d'étude est ...

La création et l’intégration d’éléments 3D interactifs sur une plateforme e-commerce sans modélisation manuelle. J’aimerais me concentrer sur l’utilisation d’outils de génération (2D vers 3D par IA) et sur l’optimisation technique de ces fichiers pour le web.

### Contexte

Pour mon TB (Stratégie Digitale et création de Site E-Commerce pour une marque horlogère), je devrai présenter la montre de la marque au mieux sur leur futur site web. 
Comme je n'ai pas de fichiers techniques 3D d'usine et que je ne suis pas modeleur 3D, je vais apprendre à utiliser des outils modernes pour créer ces assets à partir de simples photos ou croquis. 
L'objectif est d'offrir une expérience interactive aux clients (pouvoir tourner la montre, zoomer) pour booster la crédibilité de la marque et les ventes sans pour autant devoir passer des centaines d’heures sur cette partie du projet 

## État initial

Je sais créer et gérer une boutique Shopify et je maîtrise en partie la création de contenus 2D mais je ne sais pas comment transformer une image en un objet 3D. Ni comment utiliser et integrér un objet 3D à un site web. 
Je sais également que ce genre de fonctionnalité peut ralentir la “vitesse” d’un site et ne connais pas les contraintes à respecter afin de pouvoir proposer une experience interactive tout en gardant un site performant.

## Objectifs

Mon objectif principal est de générer et d'intégrer un modèle 3D interactif d'une montre Gagnebin sur une page produit Shopify de test au terme des 36 heures dédié à ce cours. La montre devra offrir un rendu visuel adapté aux standards du commerce horloger, sans dégrader significativement les performances de chargement du site.

Pour valider ou non l’experimentation, je me baserai sur les 3 critères suivants (Qualité / Fluidité / Vitesse) :

- **Le rendu visuel** : Le modèle 3D final ne doit pas ressembler à un "brouillon généré par IA". Les textures principales (comme les reflets sur le verre ou l'acier de la montre Gagnebin) doivent être crédibles et l'objet ne doit pas comporter de trous ou de déformations majeures.
- **L'expérience utilisateur** : La manipulation de la montre (pouvoir la tourner et zoomer) doit se faire naturellement et sans aucune saccade, que ce soit depuis un ordinateur ou un smartphone standard.
- **Les performances web** : L'ajout de cet élément 3D interactif ne doit pas détruire le temps de chargement de la boutique. La page produit test devra maintenir un score d'au moins 70/100 sur le test Google PageSpeed Insights.


## Démarche

- **Recherche & Benchmark (8h)** : Comparer les outils, tester les versions gratuites et déterminer celui qui offre le meilleur rendu visuel pour l'horlogerie.
- **Création d'assets (12h)** : Multiplier les tests de transformation 2D -> 3D. Travailler les réglages pour que ça paraisse réel.
- **Intégration Shopify (10h)** : Mettre en place une page shopify test et intégrer l’élément 3D dessus. Optimiser le fichier pour qu'il soit le plus léger possible.
- **Analyse de performance (6h)** : Mesurer la vitesse du site et ajuster l'intégration pour maintenir un site ultra-rapide.

## 5 questions

- Quel outil offre le meilleur rapport "qualité visuelle / facilité d'intégration" pour Shopify ?
- Comment transformer une image fixe en 3D sans que le rendu ne paraisse "faux" ou généré par une IA ou de mauvaise qualité ?
- Jusqu'à quel point un processus de génération peut-il satisfaire aux exigences de réalisme de l'horlogerie (précision des formes, reflets) sans aucune retouche humaine ?
- Le viewer natif de Shopify est-il suffisant pour conserver une vitesse de page optimale comparé à un embed externe ?
- Comment s'assurer que l'interaction 3D reste fluide sur mobile et sur desktop 


## Expérimentation

Je vais créer une page produit test sur Shopify. L'idée est d'y intégrer la montre Gagnebin en 3D interactive. Je vais mesurer le temps de chargement de la page et la fluidité de la manipulation (rotation/zoom). L'expérimentation sera réussie si le rendu est visuellement "haut de gamme" et que le site reste rapide à charger.

# RAPPORT FINAL À RENDRE POUR LE 6 MARS 23h59

## Retour sur l'état initial

Mon objectif initial était de générer et d'intégrer un modèle 3D interactif d'une montre de luxe sur Shopify, en passant uniquement par un processus de génération par intelligence artificielle (de la 2D vers la 3D), sans aucune modélisation manuelle. L'idée était de gagner du temps tout en offrant une expérience visuelle haut de gamme.
Dans la réalité, l'expérimentation a montré les limites actuelles du 100% IA pour un domaine aussi exigeant que l'horlogerie. Si l'IA parvient assez bien à comprendre et générer la géométrie globale (la forme de la montre), elle peine énormément sur les textures et les matériaux (l'acier, les reflets du verre). Le résultat final fait encore trop "brouillon".
En revanche, l'intégration web s'est avérée beaucoup plus simple que prévu. J'ai découvert que le format .glb (qui est en quelque sorte le "JPEG de la 3D" ) s'intègre nativement et très facilement dans Shopify, rendant l'expérience fluide sans avoir à se compliquer la tache.

## Réponses aux 5 questions

- **Quel outil offre le meilleur rapport "qualité visuelle / facilité d'intégration" pour Shopify ?**
  - Après avoir testé beaucoup d’outils (+ de 10 platesforme au total) (Meshy, Luma AI, SupaVoxel, etc.) , le flux de travail le plus concluant a été de générer 4 vues différentes de la montre (front, back, left, right) avec Gemini et ensuite d'utiliser l'outil Fast3D.io. C'est là que j'ai obtenu le meilleur rendu.

- **Comment transformer une image fixe en 3D sans que le rendu ne paraisse "faux" ou généré par une IA ou de mauvaise qualité ?**
  - Avec les outils actuels de génération pure ( texte à 3D ou une ou plusieurs images à 3D), c'est quasiment impossible de ne pas avoir un rendu qui fait "généré par IA" pour un objet complexe. L'astuce est de séparer la géométrie de la texture. Les IA actuelles gèrent mal les reflets métalliques précis requis en horlogerie.

- **Jusqu'à quel point un processus de génération peut-il satisfaire aux exigences de réalisme de l'horlogerie (précision des formes, reflets) sans aucune retouche humaine ?**
  - Dans l'état actuel, ce n'est pas du tout suffisant. Le résultat final manque de finition et ressemble trop à une ébauche. Les exigences de l'horlogerie (précision absolue, jeux de lumière) imposent de repasser par un logiciel de modélisation pour peaufiner le rendu. 
Je tiens tout de même à préciser que pour cette expérimentation, je me suis tenu aux logiciels gratuits ou proposant des périodes d'essai gratuites. Il est donc tout à fait possible qu'il existe des modèles d'IA beaucoup plus performants dédiés aux professionnels, mais que je n'ai pas pu évaluer car ils exigeaient obligatoirement un abonnement payant et pas d’essaies gratuit. Ou alors simplement des plateformes que je n’ai pas découvert qui auraient été plus performante.

- **Le viewer natif de Shopify est-il suffisant pour conserver une vitesse de page optimale comparé à un embed externe ?**
  - Oui. Le viewer natif de Shopify semble idéal pour cela. J'ai effectué des tests sur PageSpeed Insights en comparant une page produit classique (avec un PNG) et une page avec le modèle 3D . Les résultats sont presque identiques : la page 3D affiche un score de 59 sur mobile (contre 63 pour le PNG) et 95 sur desktop (contre 99). L'impact sur les performances est donc minime.
    
- **Comment s'assurer que l'interaction 3D reste fluide sur mobile et sur desktop**
  - En utilisant le format compressé .glb et en s'appuyant sur le viewer natif de la plateforme. J'ai testé plusieurs applications tierces depuis le store Shopify pour essayer d'avoir plus d'options pour l'utilisateur, mais elles étaient soit payantes, soit moins performantes que la solution native.

## Résultat de l'expérimentation
L'expérimentation a été formatrice car elle m'a permis de tester concrètement la chaîne de production complète, de la génération d'images avec Nano Banana Pro 2 jusqu'à l'affichage final sur mobile. J'ai pu constater que si l'IA comprend bien la forme (géométrie), elle échoue sur le rendu "Luxe". Le test a été concluant sur l'aspect technique de l'intégration : j'ai réussi à faire tourner et zoomer la montre sur une page test Shopify, prouvant que la technologie est prête pour le web, même si les assets générés automatiquement ne le sont pas encore pour de l'horlogerie ou un résultat qui exige des finitions précises
## Investissement

La répartition de mon temps a été assez différente de ma planification initiale (total de 19h réalisées contre 36h prévues), principalement en raison des limites techniques rencontrées, de la facilité de l'intégration web et de mon planning général  :

- **Recherche & Benchmark (6h réalisées / 8h prévues)** : J'ai perdu énormément de temps et d'énergie à créer des comptes sur de multiples plateformes avec différentes adresses Gmail pour pouvoir profiter des essais gratuits. 
  
- **Création d'assets (8h réalisées / 12h prévues)** : Les temps d'attente entre les différentes générations d'IA étaient très frustrants et chronophages. Travailler les "prompts" pour obtenir de bons résultats a aussi été compliqué malgé un nombre important de plateforme / applications testés, les résultats restaient tous plus ou moins similaires et toujours pas au niveau esperé 
  
- **Intégration Shopify (3h réalisées / 10h prévues)** : Cette partie a été beaucoup plus rapide que prévu grâce à la prise en charge native des fichiers glb par Shopify, qui a rendu l'embed très simple. De base j’avais aussi pensé que ça me prendrait plus de temps de créer un compte Shopify / Mettre en place le site web / Ajouter un titre / description produit d’exemple mais j’ai simplement eu a intégrer les pages produits à un site déjà existant que je possèdais.
  
- **Analyse de performance (2h réalisées / 6h prévues)** : Réalisée très rapidement et efficacement via PageSpeed Insights. L'intégration native s'étant révélée très légère, 
## Réflexion sur la méthode d'auto-formation

L’experience ma confronté à quelques difficultés que je n’avais pas imaginé : 

- **La gestion chaotique des accès** : Pour contourner les barrières tarifaires et tester un maximum d'outils, j'ai dû créer de nombreux comptes sur différentes plateformes en utilisant plusieurs adresses Gmail pour profiter des essais gratuits. N'ayant pas anticipé ça, je me suis rapidement retrouvé perdu : j'ai réalisé trop tard que j'aurais dû tenir un fichier de suivi rigoureux pour noter quel mail était associé à quelle plateforme et quel rendu spécifique. Cette désorganisation m'a fait perdre beaucoup de temps ( et était accessoirement pas très fun…) .


- **Les limites matérielles** : Les logiciels et outils de génération 3D en ligne sont extrêmement gourmands en ressources. En travaillant sur plusieurs plateformes simultanément, j'ai poussé mon ordinateur dans ses limites. Toute mes pages ralentissaient beaucoup et la consommation d'énergie était telle que ma batterie se vidait plus vite qu'elle ne chargeait, me forçant à rester constamment branché sur secteur.
  
- **Frustration et attentes** : L'auto-formation via l'IA est chronophage à cause des temps d'attente entre chaque génération et de la nécessité d'affiner constamment les "prompts" sans garantie de résultat. Cette frustration m'a mené à une conclusion importante : malgré la promesse de rapidité de l'IA, l'apprentissage des bases d'un outil standard comme Blender aurait probablement été plus efficace pour obtenir la qualité "Luxe" visée 

## Conclusion

Malgré le développement fulgurant des outils IA, s'imposer une contrainte stricte de "2D -> IA -> 3D" sans intervention humaine n'est pas la bonne approche pour atteindre la qualité requise par l'industrie horlogère.
Une leçon de cette auto-formation est qu'il est aujourd’hui surement plus efficace d'utiliser l'IA pour générer une base (la géométrie brute), puis de reprendre la main. Pour mon Travail de Bachelor (TB), je prévois de passer du temps à apprendre les bases d'un outil 3D classique comme Blender. Cela me permettra d'importer les fichiers générés par l'IA, de corriger les textures et d'ajuster les lumières pour obtenir le rendu final haut de gamme que j'espère, tout en conservant d'excellentes performances web.


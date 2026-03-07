# M52-1/2 Du_Bois Jonas - Capacitor JS

## Mon sujet d'étude est ...

Capacitor JS : Création et déploiement d'une application mobile native "Event Companion" à partir de technologies web.

Capacitor est un "native runtime" cross-platform. Il permet de transformer une application web moderne en une application mobile native (iOS, Android) tout en offrant un accès direct aux API natives des appareils.

### Contexte

Mon Travail de Bachelor consiste à développer le compagnon digital tout-en-un de la "Coupe des Bains" (compétition de gymnastique). C'est un Hub Digital Temps Réel visant à remplacer le "chaos du papier" (livrets, panneaux de résultats) par une application centralisant les résultats en direct, le programme, et des flux vidéo.

J'ai choisi Capacitor JS car mon application repose fortement sur des technologies web (notamment WebSockets avec socket.io pour le temps réel et intégration de Live Streams). L'avantage pour mon TB est de pouvoir encapsuler ce projet web dans une vraie coquille native fluide et "frictionless". Cela me permettra d'offrir une expérience premium (PWA/App native) aux spectateurs, aux gymnastes et au comité, sans devoir tout recoder en Swift ou Kotlin. Pour mon futur professionnel, maîtriser le déploiement hybride est un atout majeur pour rentabiliser et distribuer rapidement des projets web sur les stores mobiles.

## État initial

Aujourd'hui, je suis à l'aise avec le développement web et la gestion des flux de données en temps réel (nécessaires pour mon Hub). En revanche, je suis novice en ce qui concerne l'écosystème de compilation mobile natif (Xcode, Android Studio), la configuration des manifestes d'application, et l'intégration d'API natives spécifiques au téléphone.
L'implication directe est que je vais devoir consacrer une bonne partie de mon auto-formation à la configuration de ces environnements et à la compréhension du "pont" (bridge) entre mon code web et les composants natifs du téléphone.

## Objectifs

Voici mes objectifs SMART pour ces 36 heures d'auto-formation :

    1. Comprendre l'architecture : Savoir expliquer comment Capacitor interagit avec les API natives via des plugins d'ici la fin des 10 premières heures.

    2. Configuration de l'environnement : Réussir à configurer Android Studio (ou Xcode) et l'outil en ligne de commande (CLI) de Capacitor pour initialiser le projet mobile d'ici la semaine 1.

    3. Intégration technique utile au TB : Intégrer avec succès au moins 3 plugins natifs essentiels pour un événement (ex: Splash Screen, Preferences, Network) d'ici la fin de la semaine 2.

    4. Déploiement cible : Compiler et faire tourner l'application web sous forme d'application native sur un émulateur d'ici la date de rendu finale.

Critères de réussite : L'atteinte de ces objectifs sera validée par la réalisation d'un Proof of Concept (POC) fonctionnel sur un émulateur, démontrant une interface au look "premium" et une interaction avec le matériel du téléphone.

## Démarche

Je prévois de répartir les 36 heures d'investissement de la manière suivante :

    * Recherche et documentation (5h) : Lecture de la doc Capacitor, compréhension des concepts de base (Web View, Plugins, CLI).

    * Mise en place de l'environnement (6h) : Installation d'Android Studio/Xcode, configuration des SDKs, de Node.js, et initialisation du projet.

    * Développement de l'interface du POC (8h) : Création d'une application web simplifiée simulant le Hub (HTML/JS/CSS).

    * Intégration Capacitor et Plugins natifs (10h) : Ajout de Capacitor, configuration des plugins (Splash Screen pour le côté immersif, Network pour gérer les pertes de connexion dans les salles bondées, Preferences pour les favoris).

    * Tests, Débogage et Compilation (4h) : Débogage sur l'émulateur, synchronisation du code (npx capacitor sync), et tests de comportement hors-ligne.

    * édaction du rapport final et analyse réflexive (3h) : Bilan de l'apprentissage et remplissage de la seconde partie du document.

## 5 questions

Ces questions guideront mon apprentissage et me permettront de vérifier mes acquis :

    1. Quelle est la différence fondamentale d'architecture entre Capacitor et des outils plus anciens comme Cordova ?

    2. Comment fonctionne la commande capacitor sync et que modifie-t-elle exactement dans les dossiers natifs (iOS/Android) ?

    3. Comment Capacitor gère-t-il les connexions web persistantes (comme mes WebSockets) lorsque l'application passe en arrière-plan sur le téléphone ?

    4. Comment déboguer l'interface web (DOM, console JavaScript) d'une application Capacitor pendant qu'elle tourne sur un émulateur mobile ?

    5. Quelle est la procédure exacte pour configurer un Splash Screen natif (pour un effet premium au lancement) et gérer les états de connexion (Network) via les plugins Capacitor ?

## Expérimentation

Pour valider mon apprentissage, je vais réaliser un POC "Hub Event Mobile".
Il s'agira d'une version allégée de mon app encapsulée avec Capacitor, qui démontrera la viabilité technique pour le TB. Ce POC inclura :

    1. Un Splash Screen natif au lancement de l'app (plugin Splash Screen), pour garantir l'aspect premium et immersif recherché par le comité.

    2. Une sauvegarde locale des "gymnastes favoris" pour que l'utilisateur retrouve sa configuration même s'il ferme l'app (plugin Preferences).

    3. Une détection de la perte de connexion internet (très fréquente dans les salles de gym bondées) avec affichage d'une alerte native (plugin Network).
    Ce POC me permettra de valider le pont Web-Natif et d'assurer que mon application de Bachelor fonctionnera parfaitement dans les conditions réelles de la Coupe des Bains.

---

# RAPPORT FINAL À RENDRE POUR LE 6 MARS 23h59

## Retour sur l'état initial

_Quel bilan entre les attentes, les objectifs et la réalité de cette auto-formation ?_

Je m'attendais à devoir configurer capacitor pendant des heures et à galérer avec les environnements de développement natifs. En réalité, la documentation de Capacitor est très claire et j'ai pu configurer l'environnement assez rapidement. Cependant, j'ai sous-estimé le temps nécessaire pour comprendre les subtilités du pont entre le code web et les API natives, ce qui a été plus complexe que prévu. Je n'ai pas encore bien saisis la différence entre les plugins officiels et les plugins personnalisés, ce qui a ajouté une couche de complexité à mon apprentissage. J'ai encore du mal à saisir la gestion des notifications push sur android notamment. J'ai installé et initialisé un projet firebase de google pour avoir les analytics ainsi que les notifications push native mais je n'ai pas encore compris comment cela fonctionnait concrètement.

## Réponses aux 5 questions

_Répondez aux 5 questions posées plus haut. Pour chacune d'elles, si nécessaire, complétez ou améliorez la question._

    1. Pour mon application, j'ai choisi Capacitor précisément pour sa philosophie moderne. La différence fondamentale réside dans le statut des dossiers natifs (ios et android).

    Avec Cordova, ces dossiers étaient considérés comme des "artefacts de build" : c'était une boîte noire générée automatiquement, et il ne fallait surtout pas les modifier à la main, au risque de tout perdre au prochain build.

    Capacitor, en revanche, considère les dossiers natifs comme des artefacts de code source. Je les commite sur mon dépôt Git. L'application native (iOS ou Android) charge simplement mon application web Nuxt (mon dossier .output/public) dans une WebView performante (WKWebView). Si j'ai besoin d'ajouter un bout de code natif spécifique en Swift ou en Kotlin, j'ouvre directement mon projet dans Xcode ou Android Studio et je le code. Capacitor ne l'écrasera jamais. Ça me donne le contrôle total d'un développeur natif tout en gardant ma stack web Vue/Tailwind.

    2. Quand je lance mon script de build (npm run generate:mobile puis cap sync), la commande capacitor sync exécute en réalité deux actions distinctes et cruciales : Copy et Update.

        Copy : Elle prend les fichiers web statiques que Nuxt vient de générer dans mon dossier (ex: .output/public) et les copie physiquement dans les dossiers natifs prévus à cet effet (ios/App/App/public pour Xcode et android/app/src/main/assets/public pour Android).

        Update : Elle analyse mon package.json pour repérer les plugins Capacitor que j'ai installés (comme le Splash Screen ou le Network) et va injecter le code natif nécessaire. Sur iOS, elle va lancer un pod install pour mettre à jour CocoaPods. Sur Android, elle va modifier les dépendances de build.gradle.

    En gros, elle s'assure que mes projets natifs sont parfaitement synchronisés avec ma dernière version web et mes derniers plugins.

    3. C'est un point critique pour la LiveStreamApp, puisque tout le système de scores en direct de la Coupe des Bains repose sur des WebSockets (via Socket.io).

    Il faut savoir que Capacitor respecte les règles strictes des OS mobiles (iOS et Android) : quand l'application passe en arrière-plan, le système d'exploitation suspend l'exécution du JavaScript dans la WebView pour économiser de la batterie et de la RAM. Par conséquent, ma connexion WebSocket est inévitablement coupée après quelques secondes.

    Pour gérer cela de manière "premium" et éviter à l'utilisateur de rester sur des scores obsolètes, j'utilise le plugin @capacitor/app. J'écoute l'événement appStateChange. Dès que la propriété isActive repasse à true (l'utilisateur rouvre l'appli), je déclenche immédiatement une fonction de reconnexion dans mon store Socket et je refais un "fetch" des données en direct. Ainsi, la reprise est transparente et les scores se mettent à jour instantanément à l'ouverture.

    4.C'est là que Capacitor brille vraiment, car le débogage est identique à celui d'un site web classique. Puisque mon interface tourne dans une WebView, j'utilise les outils de développement de mon navigateur de bureau.

    Pour iOS (avec l'émulateur Xcode ou un iPhone branché) : J'ouvre Safari sur mon Mac. Je vais dans l'onglet Développement de la barre de menu, je sélectionne mon simulateur (ou mon iPhone), puis je clique sur "localhost". L'inspecteur web s'ouvre, et j'ai accès à mon DOM, ma console (pour voir mes logs de WebSockets) et mon réseau.

    Pour Android (avec Android Studio) : Je lance l'émulateur, j'ouvre Google Chrome et je tape chrome://inspect/#devices dans la barre d'adresse. Mon application Capacitor y apparaît et je clique sur "Inspect".

    Ça me permet d'ajuster mon TailwindCSS en temps réel directement sur le rendu du téléphone.

    5.Pour offrir une expérience vraiment sans friction (frictionless) sur la LiveStreamApp, j'ai implémenté ces deux comportements via les plugins officiels de Capacitor.

    Pour le Splash Screen (@capacitor/splash-screen) :
    Je ne voulais pas d'un écran blanc disgracieux au chargement de Nuxt. J'ai utilisé l'outil capacitor-assets (ou j'ai placé mes images dans les dossiers natifs iOS/Android) pour générer le visuel de la Coupe des Bains. Dans mon capacitor.config.ts, je configure le Splash Screen pour qu'il ne se cache pas automatiquement (launchAutoHide: false). Dans mon code Vue (AppSplashScreen.vue ou app.vue), je l'oblige à rester affiché le temps que mon client API ou mes sockets soient prêts. Une fois monté, j'appelle SplashScreen.hide(). L'entrée dans l'appli est ainsi d'une fluidité parfaite.

    Pour le Network (@capacitor/network) :
    C'est indispensable pour une application en temps réel. Dans mon projet, j'ai créé un composable dédié (useNetworkStatus.ts). J'y utilise Network.addListener('networkStatusChange', (status) => {...}) pour écouter en permanence l'état de la carte Wi-Fi ou 4G du téléphone. Si le status.connected passe à false (par exemple, si quelqu'un capte mal au fond de la salle des Iles), je lie cet état à mon UI, par exemple en déclenchant mon composant NetworkToast.vue pour avertir l'utilisateur qu'il a perdu la connexion et que les scores ne sont temporairement plus en direct.

## Résultat de l'expérimentation
_Expliquez comment s'est passé l'expérimentation, a-t-elle été formatrice ? sur quels aspects ?_

L'expérimentation a été ardue et technique, notamment pour gérer le fossé entre le web et le mobile natif. Cependant, je reste un peu sur ma faim : n'ayant pas pu tester et déployer l'application sur iOS, il me manque une partie cruciale de l'expérience Capacitor pour que ce soit totalement enrichissant. J'ai réussi à faire tourner mon POC sur Android, mais je n'ai pas encore maîtrisé les subtilités de la compilation iOS (certificats, provisioning profiles). Cela dit, j'ai énormément appris sur la configuration des environnements natifs et sur la manière dont Capacitor gère le pont entre le web et le natif. J'ai aussi découvert les limites de ce type d'approche hybride, notamment en termes de performance et de gestion des ressources.

## Investissement

_Détaillez le temps passé et les écarts avec l'investissement imaginé au départ, expliquez pourquoi._

Le temps investi s'est révélé nettement inférieur à mes prévisions initiales. Cet écart très positif s'explique principalement par la simplicité de la configuration. La mise en place de l'environnement et des outils s'est avérée beaucoup plus fluide et intuitive que je ne l'avais imaginé, ce qui m'a permis d'économiser un temps précieux dès le lancement du projet. Cependant, j'ai sous-estimé la complexité de la compréhension du pont entre le code web et les API natives, ce qui a nécessité un investissement supplémentaire pour maîtriser ces aspects techniques. De plus, le temps consacré à la configuration de Firebase pour les notifications push a été plus long que prévu, car je n'avais pas anticipé les défis liés à l'intégration de ces fonctionnalités dans un environnement hybride.

## Réflexion sur la méthode d'auto-formation

_En regard des avantages et inconvénients de l'auto-formation, qu'avez-vous constaté ?_

'ai constaté que l'auto-formation est un exercice particulièrement exigeant. D'une part, c'est un processus chronophage qui demande une autodiscipline et une motivation constantes pour ne pas se décourager. D'autre part, le principal inconvénient que j'ai ressenti est l'absence de feedback externe. En étant mon propre professeur, j'ai manqué d'un regard critique et objectif pour valider mes acquis, corriger mes erreurs ou m'orienter vers les bonnes pratiques. Cela a parfois conduit à des impasses techniques ou à des choix de configuration sous-optimaux que j'aurais pu éviter avec un mentor ou un formateur expérimenté. 
## Conclusion

_Quelles leçons avez-vous apprises et pourquoi ?_

J'ai appris que la configuration d'un projet hybride avec Capacitor est plus accessible que je ne le pensais, mais que la maîtrise des interactions entre le web et le natif nécessite une compréhension approfondie de l'architecture. J'ai également réalisé que les outils modernes comme Capacitor ont considérablement simplifié le processus de développement mobile pour les développeurs web, mais qu'il est crucial de bien comprendre les limites et les défis de cette approche pour éviter des problèmes de performance ou d'expérience utilisateur. Enfin, j'ai compris que l'auto-formation, bien qu'enrichissante, doit être accompagnée d'une certaine rigueur et d'une capacité à chercher des ressources fiables pour surmonter les obstacles techniques.

_Quelles implications pour votre TB et pourquoi ?_

Etant donné que j'ai pris un sujet que je voudrais avoir pour mon TB mais que je n'ai pas reçu de confirmation officielle de la direction je ne peux pas encore tirer les conclusions de cette auto-formation. Cependant, je peux déjà dire que j'ai appris à configurer un projet Capacitor et à comprendre les interactions entre le code web et les API natives, ce qui est un atout majeur pour mon projet de Bachelor. J'ai également découvert les limites et les défis de l'approche hybride, ce qui me permettra d'anticiper les problèmes potentiels lors du développement de mon application finale. En termes d'implications pour mon TB, cette expérience m'a donné une base solide pour construire mon Hub Digital Temps Réel, en me permettant de choisir les bonnes technologies et de comprendre comment les intégrer efficacement pour offrir une expérience utilisateur optimale.

#### PS :
Tout les textes on été reformulé par l'IA [Gemini] ( j'écris gobalement très mal et je ne voulais pas que ce rapport soit une tané à lire )

Lien du projet du git : [https://github.com/Jonas-du-bois/LivestreamApp-v3](https://github.com/Jonas-du-bois/LivestreamApp-v3)

/* Jonas Du Bois - M52-1/2 - Capacitor JS - 2026-06-03 */
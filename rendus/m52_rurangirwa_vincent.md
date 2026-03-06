# M52-1/2 Rurangirwa Vincent - Qu'est ce qu'un LMS?

# ETAT INITIAL ET OBJECTIFS À RENDRE POUR LE 23 FEVRIER 23h59

## Mon sujet d'étude est la définition et exploration des possibilités et des limites des LMS (Learning Management System)

Le but de la démarche est de me créer une expertise dans le domaine des LMS. Cet apprentissage consiste à avoir une vue d'ensemble sur l'historique, les contextes d'utilisation, des possibilités actuelles ainsi que des limites de ces systèmes. La contrainte que je m'impose est de ne pas me former sur un LMS précis pour éviter les biais lors du choix du LMS adapté lors de mon TB.

### Contexte

Mon travail de Bachelor consiste en la conception et le déploiement d'une plateforme de cours en ligne. La gestion de ces cours se fait via un LMS (Learning Management System). Beaucoup de LMS différents existent et la technologie a déjà subi des évolutions depuis sa conception. Pour me permettre de répondre au mieux à la problématique de mon TB, il me faut acquérir une connaissance sur le contexte et les usages de cette technologie. 

## État initial

Mon niveau de connaissance actuel se limite à un usage scolaire, principalement de systèmes basés sur Moodle. J'ignore cependant le fonctionnement interne et les besoins pour faire fonctionner un LMS.
L'avantage est que je n'ai pas d'a prioris sur la technologie mais il va falloir un plus grand effort pour trouver et reconnaître des ressources de qualités pour me former.

## Objectifs

1. Découvrir ce qu'est un LMS lister et comprendre les fonctionnalités clés d'un LMS en 9h
2. Identifier et différencier les types d'hébergements (SaaS et auto-hébergé) ainsi que les licences (Open Source et commerciale) dans le contexte des LMS et rédiger une synthèse comparative. (9h)
3. Comprendre et schématiser les différents standards de transfert de données entre un contenu et un LMS (9h)

## Démarche

Je pense partager le temps alloué en 4. 3 Quarts pour les objectifs fixés puis répondre aux questions et finalement le dernier quart pour la phase d'expérimentation.

## 5 questions
Pour rédiger les questions, je me suis basé sur un article : https://www.ispring.com/knowledge-hub/what-is-lms

1. Quels sont les avantages des LMS auto-hébergé ?
2. Pourquoi le reporting est-il considéré comme l'une des fonctionnalités les plus importantes ?
3. Comment le standard SCORM permet-il à un cours créé sur un outil externe de fonctionner sur différents LMS ?
4. Quels sont les coûts pour implémenter un LMS ?
5. Quels sont les différents types d'utilisateurs au sein d'un LMS ?

## Expérimentation

Pour la phase d'expérimentation, j'aimerais mettre en place un framework de sélection de LMS simple qui permet d'entrer des paramètre, par exemple le nombre d'apprenant, d'administrateur et de professeurs ainsi qu'un budget et les fonctionnalités que l'on veut. Sur la base de nos paramètres, l'outil doit nous indiquer vers quel type de plateforme et d'hébergement. Idéalement sous forme de page web.

---

# RAPPORT FINAL À RENDRE POUR LE 6 MARS 23h59

## Retour sur l'état initial

On trouve beaucoup de ressources sur le sujet, souvent produites par des entreprises qui vendent des solutions LMS ou en lien avec le e-learning, et il a fallu faire un tri pour éviter les articles "trop marketing" qui promeuvent leurs outils. Mes recherches m'ont permis de remplir mes objectifs et j'ai l'impression de mieux cerner le domaine ainsi que son fonctionnement et ses enjeux.

## Réponses aux 5 questions

1\.  **Quels sont les avantages des LMS auto-hébergé ?**

Les 2 avantages majeurs sont :

La souveraineté et la sécurité des données. Pour des environnements contenant des informations confidentielles et sensibles ou nécessitant un contrôle très strict, les données ne quittent pas les serveurs de l'organisation.

Cela permet également une personnalisation technique du code source et des intégrations sur mesure avec des systèmes informatiques internes du type ERP. Utile pour avoir une gestion poussée des processus business et pour des entreprises qui forment sur des expertises métiers.

Cela nécessite cependant une infrastructure adaptée et une équipe qui est capable de développer et de maintenir la solution contrairement à une infrastructure SaaS hébergée sur un Cloud.

2\.  **Pourquoi le reporting et l'analytique sont-ils considérés comme la fonction centrale d'un LMS en entreprise ?**

Les LMS sont utilisés dans d'autres contextes que l'éducation, cela peut être un outil de gestion des risques et des ressources humaines. Pour des business, le reporting permet par exemple de prouver la conformité légale (compliance) de leur entreprise face aux régulateurs. Pour les formations, les données analytiques permettent d'identifier les déficits de compétences, adapter les contenus ainsi que de suivre et justifier le retour sur investissement de la plateforme.

3\.  **Comment l'évolution des standards (de SCORM vers xAPI/cmi5) modifie-t-elle le fonctionnement des cours sur un LMS ?**

Le standard historique SCORM permettait l'interopérabilité grâce à un fichier ZIP et une API JavaScript, mais cloisonnait l'expérience d'apprentissage en ligne sur un navigateur web. Les standards plus récents, xAPI et cmi5 changent cela en permettant de tracer des expériences d'apprentissage partout (hors-ligne, sur mobile, via des simulateurs externes) et d'envoyer ces données sous forme de déclarations (Acteur/Verbe/Objet -> ~ Vincent a complété simulation d'opération en VR) vers un LRS (Learning Record Store) qui stocke et envoie vers les plateformes d'analytics de l'organisation.

xAPI permet de ne plus dépendre de l'organisation pour la création de ressource et permet de plus courtes sessions d'apprentissage de type "On the go".

cmi5 est le standard le plus récent basé sur xAPI et permet de traquer encore plus de types d'apprentissage, mais le taux d'adoption est plus faible que SCORM et xAPI

4\.  **Quels sont les coûts pour implémenter un LMS ?**

Les coûts sont variés et ne concernent pas uniquement la licence. La phase la plus critique et coûteuse est la migration des données (données des apprenants, métadonnées, anciens paquets SCORM) vers le nouveau système. Des coûts peuvent s'ajouter tels que la personnalisation, l'intégration (API), et la formation des administrateurs. Sans compter la préparation des contenus prêts pour l'intégration au LMS.

5\.  **Quels sont les différents types d'utilisateurs au sein d'un LMS ?**

*   Les apprenants qui consomment et génèrent de la donnée

*   Les formateurs et/ou concepteurs pédagogiques qui créent le contenu sur la plateforme, animent les cours et évaluent 

*   Les administrateurs qui gèrent l'infrastructure et l'assignation des règles

*   Le personnel IT indispensable pour les systèmes open-source ou auto-hébergés qui nécessitent de la maintenance continue


## Résultat de l'expérimentation

L'expérimentation que j'avais imaginée initialement n'était pas idéale pour une approche neutre au sujet et demanderait d'étudier une quantité de LMS, LCMS (Learning content management system), LXP (Learning experience platform) différent ainsi que leur spécificités. J'ai donc analysé les critères importants qui peuvent influencer le choix. Cela m'a permis de comprendre comment approcher un choix en termes de budget, d'infrastructure et de philosophie d'apprentissage. Les fonctionnalités voulues sur le programme choisi vont découler de la vision stratégique liée à l'implémentation d'un tel outil.

## Investissement

Au départ, j'ai partagé les 36 heures fixés en 4 avec 9 heures par objectif ainsi que la rédaction des rapports. Cela ne me paraissait pas réaliste avec le temps que j'allais passer au final. J'en ai passé entre 16 et 20 avec la rédaction. Je trouve cependant que le temps mis était suffisant pour créer une bonne fondation de connaissance sur le sujet.

## Réflexion sur la méthode d'auto-formation

J'ai principalement effectué des recherches documentaires ce qui m'a permis d'assimiler dans les grandes lignes, le contexte et la théorie entourant les LMS, mais sans tester une solution, il est difficile pour moi de me visualiser comment les différentes parties s'articulent notamment dans l'interface ou pour les standards utilisés pour créer et consommer du contenu de formation.

J'ai également constaté que d'avoir mis des objectifs avant de débuter l'apprentissage était difficile surtout pour se lancer dans un sujet que l'on ne connaît pas. Cependant, cela m'a beaucoup aidé à me restreindre à un cadre et à ne pas me perdre dans des sujets annexes, bien qu'intéressant, auraient pu ralentir l'apprentissage et brouiller les informations importantes.

## Conclusion

Durant cet auto-apprentissage, j'ai découvert que le sujet est beaucoup plus vaste que ce que je pensais au départ qu'il se partage en un certain nombre de sous-domaines d'expertise très différents entre l'implémentation technique et le design de ressources pédagogiques. Contrairement à l'image que j'avais avant de me pencher sur le sujet, le domaine est très vivant et loin du vieux logiciel pour rendre ses devoirs. Les LMS ne touchent pas uniquement les institutions scolaires, mais sont en réalité encore plus répandues dans les entreprises. La leçon principale est qu'il faudra faire très attention à la stratégie derrière l'implémentation d'un outil pour qu'il soit aligné avec les contraintes budgétaires et matérielles et la philosophie d'apprentissage que l'institution veut apporter à leurs apprenants ou employés. Le rôle de toutes les parties prenantes est impacté par cette stratégie.

Durant mon TB, il faudra qu'elle soit bien définie pour éviter des difficultés techniques ou des manques de ressources.

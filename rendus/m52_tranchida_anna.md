# M52-1/2 TRANCHIDA ANNA - DESIGN SYSTEM

# ETAT INITIAL ET OBJECTIFS À RENDRE POUR LE 23 FEVRIER 23h59

## Mon sujet d'étude est le prototypage d'un mini Design System : mise à niveau sur Figma, découverte de Symfony et de Storybook

Le but de ce cours est de tester tout le processus de travail entre le design visuel et l'intégration technique. Je vais en profiter pour apprendre à bien structurer un Design System sur Figma, découvrir le framework Symfony avec Twig, et faire des tests avec Storybook. L'idée est de faire des composants, de les designer proprement, puis d'explorer comment les coder et les documenter. Je vais aussi faire des tests pour voir s'il vaut mieux intégrer Storybook directement dans le projet Symfony ou le garder dans un projet séparé.

### Contexte

Pour mon TB, je vais créer un design system pour une application sur Symfony, faire les maquettes pour une des fonctionnalités et proposer un storybook. Je veux être sûre que le passage du design au code se fera sans problème. Faire ce test va me permettre de découvrir Symfony tranquillement, de voir comment configurer mon environnement et de choisir la bonne architecture avant le vrai début du TB. 

## État initial

Pour l’instant, je pars de zéro sur le framework Symfony et sur Twig. Côté design, j'ai les bases, mais j’ai encore des choses à apprendre sur Figma. Et je n’ai jamais utilisé de Storybook.
Ma démarche va être très exploratoire. Je vais devoir lire beaucoup de documentation, faire des tutoriels, et réaliser des "crash tests" pour voir comment tout cela peut fonctionner.

## Objectifs

Mon objectif d'ici le rendu final du 6 mars est de concevoir de A à Z au moins deux composants. Pour que cela tienne de manière réaliste dans les 36h du cours, je limite volontairement le périmètre à deux éléments. Cela me donnera le temps nécessaire pour me remettre à niveau sur Figma et apprendre les bases de Symfony/Twig en partant de zéro, ce qui est une étape de préparation importante pour mon TB par la suite.
La réussite de cette auto-formation sera validée par :
- Un fichier Figma structuré utilisant les bonnes pratiques actuelles (variables, auto-layout).
- Un mini-projet local Symfony fonctionnel affichant le code Twig de ces composants via Storybook.

## Démarche

- [8h] Remise à niveau Figma et conception : Rattraper mon retard sur les nouveautés Figma et designer mes composants
- [8h] Découverte de Symfony et Twig : Suivre des tutoriels pour comprendre comment fonctionne Symfony, comment créer des pages et utiliser Twig
- [10h] Expérimentations Storybook : Faire des tests pour essayer de lier Storybook. Tester l'approche intégrée dans Symfony et l'approche séparée
- [8h] Développement front et accessibilité : Coder les composants dans Symfony en essayant d'appliquer les bonnes pratiques d'accessibilité (navigation clavier, balises ARIA)
- [2h] Faire le bilan, me préparer un rapport personnel, répondre aux 5 questions

## 5 questions

- Comment bien organiser ses maquettes et ses composants sur Figma pour se faciliter la vie au moment de l'intégration web ?
- Comment crée-t-on un élément d'interface réutilisable (comme un bouton) dans un framework back-end comme Symfony avec Twig ?
- Par quels moyens techniques peut-on faire communiquer une documentation visuelle (Storybook) avec du code PHP (Symfony) ?
- Pour mon TB, quels sont les "pour et les contre" de mettre le Design System directement dans le projet principal plutôt que dans un dossier à part ?
- Quelles sont les règles de base en HTML/CSS (balises, focus au clavier) à respecter absolument pour qu'un composant interactif soit accessible ?

## Expérimentation

Mon expérimentation consistera à tester concrètement le workflow de création d'un Design System, de l'outil de design jusqu'au code. Je vais d'abord structurer mes fondations sur Figma (tokens, auto-layout), puis installer un projet Symfony. Mon but sera de réussir à coder ces composants réutilisables et de les lier à Storybook pour obtenir un catalogue UI interactif.

---

# RAPPORT FINAL À RENDRE POUR LE 6 MARS 23h59

## Retour sur l'état initial

Le bilan est plutôt positif. Mon but était surtout de lever mes doutes sur Symfony et Storybook avant d'attaquer mon TB, et c’est chose faite. La courbe d’apprentissage est bien là, mais je vois que c’est surmontable. J'ai réussi à faire un composant et à comprendre comment faire le pont entre mon design Figma et mon code. Ce qui est rassurant, je ne lance plus dans le TB à l'aveugle, j'ai maintenant une méthode, bien que j'ai encore à apprendre et tester.

## Réponses aux 5 questions

- **Comment bien organiser ses maquettes et ses composants sur Figma pour se faciliter la vie au moment de l'intégration web ?**
  Utiliser des variables pour les styles et l'auto-layout. Structurer ses composants et variantes pour qu'ils correspondent aux futures "props"   du code.
  
- **Comment crée-t-on un élément d'interface réutilisable (comme un bouton) dans un framework back-end comme Symfony avec Twig ?**
  En utilisant Twig Components. Il faut une classe php pour la logique et les valeurs par défaut, un fichier Twig (html.twig) pour le squelette html.
  
- **Par quels moyens techniques peut-on faire communiquer une documentation visuelle (Storybook) avec du code PHP (Symfony) ?**
  Passer par Storybook Server. Cela permet à Storybook d'appeler Symfony pour rendre le "vrai" Twig et l'afficher de manière isolée.
  
- **Pour mon TB, quels sont les "pour et les contre" de mettre le Design System directement dans le projet principal plutôt que dans un dossier à part ?**
  Directement accessible en local en faisant npm run storybook en ayant l'app symfony qui tourne déjà, et directement connecté au composant dans le code de l'app donc utile pour des modifications rapides alors que sinon ça serait moins dynamique. Mais il faut que je regarde avec l'entreprise ce qu'ils acceptent.
  
- **Quelles sont les règles de base en HTML/CSS (balises, focus au clavier) à respecter absolument pour qu'un composant interactif soit accessible ?**
  Le prendre en compte déjà au niveau du design system par exemple avec le focus, bien respecter les contraste, bien utiliser la sémantique html et permettre la navigation au clavier
  
## Résultat de l'expérimentation

Côté design j'ai appris à organiser mon système et à comment structurer les composants.
Côté technique, j'ai vu comment fonctionnait Symfony et Twig, et j'ai pu voir comment installer Storybook et me rassurer sur le fait que ça peut bien marcher comme je l'imaginais et sans trop de complexité, ce que je craignais par manque de connaissance.

## Investissement

J'ai passé un peu moins de temps que prévu sur ce projet car c'était difficile de se motiver en partant de zéro, sans aucun fil conducteur. Quand il n'y a pas de chemin tracé, il faut tout chercher par soi-même et c'est parfois décourageant et il n'y a pas forcément ce que l'on cherche. Malgré ça, ce temps m'a permis de débloquer les bases et de tester la faisabilité technique, ce qui me rassure pour la suite de mon TB.

## Réflexion sur la méthode d'auto-formation

L'avantage c'est de pouvoir avancer à son rythme et bien personnaliser ce que l'on veut apprendre pour des besoins spécifiques, l'inconvénient c'est qu'on ne trouve pas forcément des ressources pour se former si on ne veut pas utiliser que l'IA.

## Conclusion

Pour mon TB, je vais sûrement partir sur une approche intégrée (Storybook dans Symfony) si l'entreprise me le permet. Cela me permettra d'aller plus vite et de garantir que ma documentation est toujours synchronisée avec le code. Ce test m'a permis d'avoir une idée plus claire de ce que je vais vraiment faire pendant mon TB et va me permettre de savoir de quoi je parle et savoir quoi regarder au moment de commencer. 

# M52-1 Desgalier Michaël

# 🛡️ Projet d'Autoformation : Préparation aux Sélections Cybersoldat

## 1. Sujet d'étude : Fondamentaux Réseau et Linux

En raison de mes obligations liées au service militaire obligatoire, je n'ai pas la possibilité d'effectuer mon travail de Bachelor cette année. J'ai choisi de transformer cette contrainte en opportunité en visant l'intégration de l'unité d'élite des **Cybersoldats** de l'armée suisse.

Pour me préparer aux sélections d'entrées particulièrement rigoureuses, je me base sur la plateforme de formation en ligne de l'armée, développée en collaboration avec des experts de la cybersécurité. Mon autoformation cible deux piliers fondamentaux :

> **Modules d'apprentissage intensif :**
> * 🌐 **Network Engineering Basics** (Bases de l'ingénierie réseau)
> * 🐧 **Linux Engineering Basics** (Bases de l'ingénierie Linux)

---

## 2. Contexte et Motivation

Le choix de ce sujet s'inscrit dans une stratégie claire d'anticipation et d'évolution de carrière :

* **Avantage concurrentiel :** Les places pour devenir Cybersoldat sont limitées et très convoitées. Maîtriser les bases de l'infrastructure me donnera un avantage significatif lors des tests de sélection.
* **Passion personnelle :** La cybersécurité est un domaine qui me passionne profondément et dans lequel je souhaite me spécialiser à long terme.
* **Plus-value professionnelle :** La réussite de cette formation militaire débouche sur un *Brevet fédéral en cybersécurité*, une certification hautement reconnue sur le marché suisse, complétant parfaitement mon futur Bachelor.

---

## 3. État initial et Prérequis

Mon profil actuel est hybride, constituant une excellente base d'apprentissage :

* **Connaissances en sécurité (Faux-débutant) :** J'ai suivi des cours d'introduction lors de mon apprentissage. Les concepts théoriques de base sont acquis, bien que nécessitant un rafraîchissement sur l'aspect purement "infrastructure".
* **Atout majeur (Programmation) :** Je possède un très bon niveau en logique algorithmique et en développement. En cybersécurité, c'est un atout redoutable pour l'automatisation (scripting), l'analyse de code malveillant et l'exploitation de vulnérabilités.

---

## 4. Objectifs SMART et Validation

| Critère | Description |
| :--- | :--- |
| **Spécifique** | Compléter les modules *Network Engineering Basics* et *Linux Engineering Basics* sur la plateforme de l'armée. |
| **Mesurable** | Obtenir un score de réussite d'au moins **70%** à chaque examen de validation en fin de sous-chapitre. |
| **Atteignable** | Mon background de programmeur me permettra d'assimiler rapidement la syntaxe bash et la logique des protocoles. |
| **Réaliste** | Le volume de matière est adapté pour une étude intensive répartie sur le temps alloué. |
| **Temporel** | À achever intégralement d'ici la fin du bloc des 36 heures d'autoformation. |

> **Validation des acquis :** L'évaluation sera continue. Les pourcentages de réussite obtenus aux examens en ligne de la plateforme attesteront objectivement de ma maîtrise des modules.

---

## 5. Plan de Formation (36h)

Le temps d'étude est réparti de manière symétrique entre les deux modules pour assurer des bases solides sur les deux environnements.

| Phase | Module | Activité | Durée allouée |
| :---: | :--- | :--- | :---: |
| **1** | 🌐 **Réseau** | Compréhension du module | 9h |
| | | Révision avant examen | 4h |
| | | Réalisation de l'examen | 2h |
| **2** | 🐧 **Linux** | Compréhension du module | 9h |
| | | Révision avant examen | 4h |
| | | Réalisation de l'examen | 2h |

*(Note : Ce tableau couvre 30 heures d'étude active et d'examens, laissant une marge de 6 heures sur le bloc de 36 heures pour l'organisation, les configurations initiales et les pauses d'assimilation).*

---

## 6. Questions de contrôle des compétences

Pour valider l'acquisition de mes compétences en fin de parcours, je devrai être capable d'expliquer ces concepts sans consulter de documentation :

- [ ] **Réseau :** Quelle est la différence fondamentale entre le protocole TCP et le protocole UDP, et dans quels cas d'usage privilégie-t-on l'un plutôt que l'autre ?
- [ ] **Réseau :** Si une machine possède l'adresse IP `192.168.1.50` avec un masque de sous-réseau `255.255.255.192` (`/26`), quelle est l'adresse de son réseau et son adresse de broadcast ?
- [ ] **Linux :** Quelle est la commande exacte pour attribuer les droits de lecture, écriture et exécution au propriétaire, les droits de lecture et exécution au groupe, et aucun droit aux autres, sur un fichier nommé `script.sh` ?
- [ ] **Linux (Logique & CLI) :** Comment utiliseriez-vous une combinaison de commandes (avec des pipes `|`) pour chercher le mot "Failed" dans le fichier `/var/log/auth.log` et compter le nombre de fois où il apparaît ?
- [ ] **Transversal :** Quelles commandes Linux utiliseriez-vous pour vérifier quels ports sont actuellement ouverts et en écoute sur votre propre machine ?

---

# 📄 Rapport de Fin de Projet : Autoformation Cybersécurité (Réseau & Linux)

**Candidat :** Desgalier Michaël  
**Objectif :** Préparation aux Sélections Cybersoldat de l'Armée Suisse

---

## 1. Retour sur l'état initial et l'expérimentation

**Bilan entre attentes, objectifs et réalité :**

Au début de ce projet, mon but était de rattraper mon retard en infrastructure réseau pour être prêt pour les sélections des Cybersoldats. Je voulais réussir les modules Réseau et Linux de l'armée en obtenant au moins 70% de bonnes réponses aux examens.

Dans la pratique, mon expérience de développeur m'a énormément aidé. Pour la partie Linux, j'ai appris très vite à utiliser les commandes et à comprendre le système. En revanche, la partie Réseau m'a demandé beaucoup plus d'efforts pour mémoriser la théorie et comprendre les calculs d'adresses IP. Malgré cette différence de difficulté, j'ai réussi à atteindre et même dépasser mes objectifs sur la plateforme d'apprentissage.

---

## 2. Réponses aux 5 questions de contrôle

Voici les réponses expliquées avec mes propres mots :

### Q1 - Réseau : Différence entre TCP et UDP

* **TCP :** C'est un protocole fiable. Il vérifie que chaque donnée envoyée est bien arrivée dans le bon ordre. On l'utilise pour naviguer sur le web ou envoyer des fichiers, car on ne peut pas se permettre de perdre des morceaux en route.
* **UDP :** C'est un protocole très rapide, mais sans garantie de réception. Il envoie les données directement sans faire de vérifications. On l'utilise pour regarder des vidéos en direct, passer des appels ou jouer en ligne, car la vitesse est plus importante que la perte de quelques petites données.

### Q2 - Réseau : Calcul de réseau et de broadcast

Avec l'adresse IP 192.168.1.50 et un masque /26 (qui découpe le réseau en blocs de 64 adresses), on se trouve dans le tout premier bloc.
* **Adresse du réseau :** 192.168.1.0 (c'est le début du bloc).
* **Adresse de broadcast (diffusion) :** 192.168.1.63 (c'est la fin du bloc).

### Q3 - Linux : Gérer les permissions

Pour donner tous les droits au propriétaire (valeur 7), seulement lire et exécuter pour le groupe (valeur 5), et aucun droit pour les autres (valeur 0), la commande est :

chmod 750 script.sh

### Q4 - Linux : Chercher dans les historiques (logs)

Pour trouver le mot "Failed" dans le fichier des connexions et compter combien de fois il y est, on combine deux commandes :

grep "Failed" /var/log/auth.log | wc -l

### Q5 - Transversal : Voir les ports ouverts

Pour vérifier quels ports sont ouverts et prêts à recevoir des connexions sur ma machine, la commande la plus directe est :

ss -tuln

---

## 3. Investissement en temps

J'ai bien respecté les 36 heures prévues, mais j'ai un peu adapté mon planning en cours de route :

* **Linux :** J'ai passé moins de temps que prévu sur cette partie. Ma logique de programmeur m'a fait gagner beaucoup de temps pour comprendre les scripts et les commandes.
* **Réseau :** J'ai réutilisé le temps gagné sur Linux pour m'entraîner davantage sur le réseau. Les calculs de sous-réseaux m'ont demandé pas mal d'exercices pratiques pour être bien assimilés.
* **Organisation :** Les 6 heures de marge que j'avais prévues ont été très utiles pour comprendre comment utiliser la machine virtuelle, réviser et passer les examens en ligne.

---

## 4. Réflexion sur l'auto-formation

### Ce qui a bien marché :

* **La souplesse :** J'ai pu avancer très vite sur ce que je comprenais facilement et ralentir sur les concepts plus durs à digérer.
* **L'autonomie :** Quand je bloquais, j'ai dû chercher des solutions par moi-même (sur des forums ou dans la documentation). C'est une excellente habitude à prendre pour travailler dans la cybersécurité.

### Ce qui était plus compliqué :

* **Le risque de rester coincé :** Sans professeur pour corriger mes erreurs tout de suite, j'ai parfois perdu du temps à comprendre certains mécanismes réseau.
* **Le manque de matériel :** Apprendre le réseau sur un écran ne remplace pas la manipulation de vrais câbles, switchs et routeurs physiques.

---

## 5. Conclusion

Ce projet d'autoformation est une vraie réussite pour moi. J'ai bien compris qu'en cybersécurité, savoir coder ne suffit pas : il faut aussi comprendre comment les ordinateurs discutent entre eux sur un réseau. Ces 36 heures d'apprentissage ont renforcé ma motivation à devenir Cybersoldat. Aujourd'hui, je ne connais plus seulement la théorie ; je sais manipuler ces outils. Je me sens prêt et confiant pour affronter les sélections de l'armée suisse.

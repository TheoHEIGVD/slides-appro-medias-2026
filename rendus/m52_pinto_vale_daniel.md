# M52-1/2 VALE Daniel – CS50's Introduction to Programming with Python

## ÉTAT INITIAL ET OBJECTIFS — À RENDRE POUR LE 23 FÉVRIER 23h59

## Mon sujet d'étude est ...

**CS50's Introduction to Programming with Python (CS50P)** — Le cours de Harvard dispensé par David J. Malan, accessible gratuitement via OpenCourseWare et edX. Ce cours couvre la programmation en Python à travers 10 modules thématiques : fonctions et variables, conditions, boucles, exceptions, bibliothèques, tests unitaires, entrées/sorties fichiers, expressions régulières, programmation orientée objet, et sujets avancés (Et Cetera). Chaque module se compose d'une lecture vidéo (~2h), de shorts complémentaires et d'un problem set à soumettre.

## Contexte

### Pourquoi ce sujet ?

Mon travail de bachelor, réalisé chez **Bobst Régie Immobilière SA**, consiste à concevoir et développer une **plateforme de tableau de bord pour investisseurs immobiliers** avec une intégration à l'ERP Quorum. Ce projet implique du développement backend (API, traitement de données, intégration avec un système existant), du développement frontend, et une logique métier autour de données financières et immobilières.

Python est un langage incontournable pour le **traitement et la manipulation de données**, le **scripting d'intégration** avec des systèmes tiers comme Quorum, et le **prototypage rapide** de logiques métier. Même si le choix technologique final du TB n'est pas encore figé, maîtriser Python me donne une corde supplémentaire à mon arc, notamment pour :

- **L'intégration ERP** : écriture de scripts de synchronisation de données avec l'API Quorum
- **Le traitement de données financières** : calculs d'indicateurs pour le dashboard investisseur
- **Les tests unitaires** : garantir la qualité et la fiabilité du code livré
- **L'automatisation** : scripts de migration, de validation de données, ou de génération de rapports

### Intérêt professionnel

Python est l'un des langages les plus demandés sur le marché de l'emploi et est omniprésent dans les domaines du web, de la data et de l'automatisation. En complément de mes compétences en JavaScript/Vue.js et PHP/Laravel, Python renforce considérablement mon profil polyvalent pour la suite de ma carrière, que ce soit en développement web, en ingénierie de données, ou dans un Master en systèmes d'information.

## État initial

J'ai déjà suivi **CS50x (Introduction to Computer Science)** de Harvard, ce qui m'a donné de solides bases en algorithmique, structures de données, et programmation (C, Python, SQL, JavaScript). J'ai donc une première exposition à Python, mais de manière superficielle, le cours CS50x ne consacre qu'une semaine à Python contre plusieurs semaines en C.

Au quotidien, je développe principalement en **JavaScript (Vue.js)** et **PHP (Laravel)**. Je suis à l'aise avec les concepts fondamentaux de programmation (variables, boucles, conditions, fonctions, OOP) dans ces langages, mais je n'ai jamais approfondi Python de manière structurée et rigoureuse.

**En résumé :** je ne pars pas de zéro en programmation, ce qui me permettra d'avancer plus vite sur les premiers modules. En revanche, les modules avancés (tests unitaires, regex, OOP en Python, File I/O) représenteront un vrai apprentissage à consolider. Cette base me permet de fixer des objectifs ambitieux mais réalistes dans le cadre des 36 heures.

## Objectifs

### Objectif 1 — Compléter les modules 0 à 7 de CS50P avec tous les problem sets validés

- **Spécifique** : Suivre les 8 premiers modules du cours (semaines 0 à 7 : Functions, Conditionals, Loops, Exceptions, Libraries, Unit Tests, File I/O, Regular Expressions), visionner toutes les lectures et shorts, et soumettre chaque problem set avec un score de 100%.
- **Mesurable** : 8 modules complétés, 8 problem sets soumis et validés sur la plateforme CS50.
- **Atteignable** : À raison de ~4h par module (lecture + shorts + problem set), cela représente ~32h, ce qui s'inscrit dans l'enveloppe de 36h.
- **Réaliste** : Mon expérience préalable en programmation me permet de ne pas bloquer sur les concepts de base et de consacrer plus de temps aux exercices pratiques.
- **Temporel** : Achèvement prévu d'ici la fin du semestre, selon le calendrier de répartition ci-dessous.

### Objectif 2 — Réaliser un script Python appliqué au contexte du TB

- **Spécifique** : Développer un script Python simple (un seul fichier) qui lit un fichier CSV de données immobilières fictives et calcule quelques indicateurs financiers (rendement brut, taux de vacance), en mobilisant les compétences acquises dans le cours (File I/O, bibliothèques, gestion d'exceptions).
- **Mesurable** : Un script fonctionnel livré sur le repository GitHub du cours.
- **Atteignable** : Environ 1h de réalisation, en complément des heures de cours.
- **Réaliste** : Il s'agit d'un exercice simple et ciblé, pas d'un projet complet.
- **Temporel** : Réalisation lors des dernières heures du module, après avoir acquis les compétences nécessaires.

### Critères de validation

1. Capture d'écran du Gradebook CS50 montrant les 8 problem sets validés (100%)
2. Script Python fonctionnel déposé sur le repository GitHub du cours
3. Le script inclut au minimum : lecture d'un fichier CSV, calcul d'indicateurs financiers simples, et gestion d'erreurs

### Traçabilité de l'apprentissage

L'ensemble de ma progression (notes, solutions des problem sets, script d'expérimentation) sera documenté et publié sur un repository GitHub dédié : [github.com/d-vale/CS50_introduction-Python](https://github.com/d-vale/CS50_introduction-Python)

Cette démarche est cohérente avec ce que j'avais déjà mis en place pour le cours CS50x (Introduction to Computer Science), dont le repository est disponible ici : [github.com/d-vale/CS50_introduction-to-CS](https://github.com/d-vale/CS50_introduction-to-CS)

## Démarche

### Répartition des 36 heures

| Phase | Modules CS50P | Heures estimées | Contenu |
|-------|--------------|----------------|---------|
| **Phase 1** – Fondamentaux | Semaine 0 : Functions, Variables | ~3h | Lecture + shorts + problem set (rappels, mise en route) |
| | Semaine 1 : Conditionals | ~3h | Lecture + shorts + problem set |
| | Semaine 2 : Loops | ~3.5h | Lecture + shorts + problem set |
| **Phase 2** – Intermédiaire | Semaine 3 : Exceptions | ~4h | Lecture + shorts + problem set (gestion d'erreurs, try/except) |
| | Semaine 4 : Libraries | ~4.5h | Lecture + shorts + problem set (pip, APIs, modules tiers) |
| | Semaine 5 : Unit Tests | ~5h | Lecture + shorts + problem set (pytest, assertions) |
| **Phase 3** – Avancé | Semaine 6 : File I/O | ~5h | Lecture + shorts + problem set (CSV, JSON, lecture/écriture) |
| | Semaine 7 : Regular Expressions | ~5h | Lecture + shorts + problem set (re, patterns, validation) |
| **Phase 4** – Expérimentation | Script Python appliqué au TB | ~1h | Script simple lié au contexte immobilier |
| | Documentation et rétrospective | ~1h | README, auto-évaluation, réponses aux 5 questions |
| | Marge / révisions | ~1h | Temps tampon en cas de difficulté sur un module |
| | **Total** | **~36h** | |

### Remarque sur les semaines 8 et 9

Les semaines 8 (Object-Oriented Programming) et 9 (Et Cetera) ne sont pas incluses dans le périmètre des 36h. Si je progresse plus vite que prévu, j'entamerai la semaine 8 (OOP), qui serait particulièrement utile pour structurer le code de mon TB. Le final project CS50P n'est pas non plus inclus car le script d'expérimentation lié au TB remplit cet objectif d'application pratique.

## 5 questions

1. **En Python, comment lire un fichier CSV et extraire uniquement les lignes qui correspondent à un critère donné (par ex. un montant d'investissement supérieur à 100'000 CHF), en utilisant le module `csv` et les structures conditionnelles ?**

2. **Comment écrire une expression régulière en Python permettant de valider un format d'identifiant immobilier suisse (par ex. EGRID ou numéro cadastral) et l'appliquer sur un jeu de données chargé depuis un fichier ?**

3. **Comment structurer et exécuter des tests unitaires avec `pytest` pour valider une fonction qui calcule le rendement locatif brut d'un bien immobilier à partir de son loyer annuel et de son prix d'achat ?**

4. **Comment utiliser le mécanisme de gestion d'exceptions (`try`/`except`) en Python pour traiter proprement les erreurs lors de la lecture d'un fichier JSON malformé ou d'un appel à une API externe qui renvoie une erreur HTTP ?**

5. **Comment installer et utiliser une bibliothèque tierce Python (via `pip`) pour effectuer des requêtes HTTP vers une API REST, parser la réponse JSON, et stocker les données pertinentes dans un fichier local structuré ?**

## Expérimentation

### Script Python : calcul d'indicateurs sur des données immobilières

**Objectif** : Développer un script Python simple (un seul fichier) qui applique concrètement les compétences acquises durant le cours à un cas d'usage lié à mon travail de bachelor.

**Contenu du script :**

- **Lecture d'un fichier CSV** (File I/O — Semaine 6) : charger un jeu de données fictif représentant un export simplifié de l'ERP Quorum (immeubles avec adresse, loyer annuel, prix d'achat, charges, surface)
- **Calcul d'indicateurs** (Libraries — Semaine 4) : calculer le rendement locatif brut et le taux de vacance pour chaque bien
- **Gestion d'erreurs** (Exceptions — Semaine 3) : traiter proprement les cas de fichier manquant, lignes incomplètes ou valeurs non numériques
- **Affichage des résultats** (Functions — Semaine 0) : présenter un résumé clair dans le terminal

**Livrable** : Le script sera déposé sur le repository GitHub du cours ([github.com/d-vale/CS50_introduction-Python](https://github.com/d-vale/CS50_introduction-Python)) avec un fichier CSV de données de test et une brève explication dans le README. Cet exercice fait le pont entre l'apprentissage théorique du cours et les besoins concrets du TB, notamment la manipulation de données financières immobilières.

---

# RAPPORT FINAL À RENDRE POUR LE 6 MARS 23h59

## Retour sur l'état initial

Mon objectif initial était de compléter les semaines 0 à 7 du cours CS50P et de réaliser un script Python appliqué au contexte de mon TB. En réalité, j'ai complété les semaines 0 à 5 à 100% (tous les problem sets validés) et visionné la lecture de la semaine 6 (File I/O), sans avoir eu le temps de terminer son problem set ni d'aborder la semaine 7 (Regular Expressions).

J'ai clairement sous-estimé le temps nécessaire par module. Mon estimation initiale de ~3-4h pour les premières semaines et ~5h pour les semaines avancées s'est révélée trop optimiste, pour plusieurs raisons. D'abord, j'ai fait le choix de prendre des notes détaillées sur Notion pour chaque module, ce que je n'avais pas comptabilisé dans mon planning initial. Ensuite, les problem sets, même sur les semaines "fondamentales", demandent un vrai travail de réflexion et de débogage qui prend facilement 2-3h à eux seuls. Enfin, les shorts complémentaires, que je pensais survoler rapidement, se sont avérés précieux et j'ai pris le temps de les regarder attentivement.

Malgré cet écart, je ne regrette pas ma démarche. Les 6 semaines complétées couvrent l'essentiel des fondamentaux Python dont j'ai besoin, et la profondeur avec laquelle j'ai travaillé chaque module (notes, exercices à 100%, documentation GitHub) me donne une bien meilleure maîtrise que si j'avais survolé les 8 semaines. Le script d'expérimentation n'a pas été réalisé car il dépendait de la complétion de la semaine 6 (File I/O) que je n'ai pas terminée dans les temps. Ce script reste toutefois dans mes plans et sera réalisé après ce cours, car le sujet m'intéresse et reste pertinent pour mon TB.

## Réponses aux 5 questions

### 1. Comment lire un fichier CSV et extraire les lignes correspondant à un critère donné ?

*Note : cette question porte sur la semaine 6 (File I/O) dont j'ai visionné la lecture mais pas encore réalisé le problem set. Ma réponse se base donc sur la théorie apprise.*

Le cours enseigne une progression pour lire des fichiers CSV : d'abord avec `split(",")` (simple mais fragile si les valeurs contiennent des virgules), puis avec `csv.reader` (plus robuste), et enfin avec `csv.DictReader` qui retourne un dictionnaire par ligne en utilisant les en-têtes comme clés. C'est cette dernière approche que le cours recommande car elle est plus lisible et défensive — on accède aux colonnes par nom plutôt que par index.

```python
import csv

students = []

with open("immeubles.csv") as file:
    reader = csv.DictReader(file)
    for row in reader:
        if int(row["investissement"]) > 100000:
            students.append({"adresse": row["adresse"], "montant": row["investissement"]})

for s in sorted(students, key=lambda s: s["adresse"]):
    print(f"{s['adresse']} — {s['montant']} CHF")
```

Le `with` assure la fermeture automatique du fichier (plus besoin d'appeler `file.close()`). Le tri utilise `sorted()` avec une `lambda`, une fonction anonyme enseignée dans cette même semaine pour trier des listes de dictionnaires par une clé spécifique.

### 2. Comment écrire une expression régulière pour valider un format d'identifiant immobilier suisse ?

Cette question porte sur la semaine 7 (Regular Expressions) que je n'ai pas eu le temps d'aborder durant les 36 heures de ce cours. Le module `re` de Python et la syntaxe des expressions régulières sont enseignés dans cette semaine, que je prévois de compléter après ce rendu. Je ne suis donc pas en mesure de répondre à cette question de manière fondée sur un apprentissage réel — ce serait malhonnête de donner une réponse basée sur des connaissances que je n'ai pas acquises dans le cadre de cette auto-formation.

### 3. Comment structurer des tests unitaires avec `pytest` pour valider une fonction de calcul de rendement locatif ?

Cette question porte sur la semaine 5 (Unit Tests) que j'ai complétée à 100%. Le cours insiste sur plusieurs points clés : la séparation entre le code à tester et les tests, l'utilisation de `if __name__ == "__main__"` pour empêcher l'exécution lors de l'import, et la conception de fonctions qui retournent des valeurs plutôt que de les afficher (ce qui les rend testables). Voici comment je structurerais cela :

```python
# rendement.py
def main():
    loyer = float(input("Loyer annuel: "))
    prix = float(input("Prix d'achat: "))
    print(f"Rendement brut: {rendement_brut(loyer, prix)}%")

def rendement_brut(loyer_annuel, prix_achat):
    if prix_achat <= 0:
        raise ValueError("Le prix d'achat doit être positif")
    return round((loyer_annuel / prix_achat) * 100, 2)

if __name__ == "__main__":
    main()
```

```python
# test_rendement.py
import pytest
from rendement import rendement_brut

def test_rendement_positif():
    assert rendement_brut(24000, 500000) == 4.8
    assert rendement_brut(12000, 300000) == 4.0

def test_rendement_zero():
    assert rendement_brut(0, 500000) == 0.0

def test_rendement_prix_invalide():
    with pytest.raises(ValueError):
        rendement_brut(24000, 0)
    with pytest.raises(ValueError):
        rendement_brut(24000, -100000)
```

Comme appris dans le cours, chaque fonction `test_*` est détectée automatiquement par pytest et exécutée indépendamment — si `test_rendement_positif` échoue, les autres tests sont quand même exécutés. `pytest.raises(ValueError)` permet de vérifier que l'exception est bien levée, et le `if __name__ == "__main__"` empêche `main()` de s'exécuter quand pytest importe le fichier. On exécute ensuite simplement avec `pytest test_rendement.py`.

### 4. Comment utiliser `try`/`except` pour traiter les erreurs de lecture d'un fichier JSON malformé ou d'un appel API ?

Cette question porte sur la semaine 3 (Exceptions) que j'ai complétée à 100%. Le cours enseigne principalement la gestion du `ValueError` (quand l'utilisateur entre une valeur invalide), avec le pattern `try`/`except`/`else` et la boucle `while True` pour redemander une saisie. Le cours montre aussi `pass` pour ignorer silencieusement une erreur, et l'importance de n'attraper que des exceptions **spécifiques** plutôt qu'un `except` générique.

En appliquant ces mêmes principes au contexte de mon TB (lecture de fichiers, appels API), j'utiliserais des types d'exceptions différents (`FileNotFoundError`, `json.JSONDecodeError`) mais la structure apprise reste identique :

```python
import json

def charger_donnees(chemin):
    try:
        with open(chemin) as file:
            donnees = json.load(file)
    except FileNotFoundError:
        print(f"Erreur : le fichier '{chemin}' n'existe pas.")
        return None
    except json.JSONDecodeError:
        print(f"Erreur : le fichier '{chemin}' n'est pas un JSON valide.")
        return None
    else:
        return donnees
```

Le bloc `else` — que le cours explique bien — ne s'exécute que si aucune exception n'a été levée dans le `try`. La version la plus concise vue en cours utilise `return` directement dans le `try`, ce qui sort de la fonction et de la boucle en même temps :

```python
def get_int(prompt):
    while True:
        try:
            return int(input(prompt))
        except ValueError:
            pass
```

C'est ce pattern que le cours m'a fait maîtriser, et qu'on peut ensuite adapter à d'autres types d'exceptions selon le contexte.

### 5. Comment installer et utiliser une bibliothèque tierce pour effectuer des requêtes HTTP vers une API REST ?

Cette question porte sur la semaine 4 (Libraries) que j'ai complétée à 100%. Le cours couvre l'installation de paquets tiers via `pip install`, l'utilisation du module `sys` pour les arguments en ligne de commande, et un exemple concret avec l'API iTunes en utilisant la bibliothèque `requests`.

En suivant l'approche apprise dans le cours (exemple avec l'API iTunes), voici comment je l'appliquerais à un contexte d'API immobilière :

```python
import json
import requests
import sys

if len(sys.argv) != 2:
    sys.exit("Usage: python immobilier.py <code_postal>")

response = requests.get(
    "https://api.exemple.ch/immeubles?cp=" + sys.argv[1]
)

donnees = response.json()

for immeuble in donnees["resultats"]:
    print(f"{immeuble['adresse']} — Rendement: {immeuble['rendement']}%")

# Pour voir la structure complète des données retournées :
# print(json.dumps(donnees, indent=2))
```

Les points clés appris dans le cours : `pip install requests` pour installer la bibliothèque depuis PyPI, `requests.get(url)` qui envoie une requête HTTP et récupère la réponse, `.json()` qui convertit la réponse en dictionnaire Python, et `json.dumps(data, indent=2)` pour afficher du JSON de manière lisible (très utile pour explorer la structure d'une API qu'on ne connaît pas). Le cours enseigne aussi `sys.argv` pour passer des paramètres en ligne de commande et `sys.exit()` pour quitter proprement avec un message d'erreur si les arguments sont incorrects. C'est une compétence directement applicable à l'intégration avec l'API de l'ERP Quorum dans mon TB.

## Résultat de l'expérimentation

Le script Python prévu comme expérimentation n'a pas été réalisé dans le cadre des 36 heures. Ce script devait lire un fichier CSV de données immobilières et calculer des indicateurs financiers, en s'appuyant principalement sur les compétences de la semaine 6 (File I/O). Or, bien que j'aie visionné la lecture de cette semaine, je n'ai pas encore complété le problem set correspondant, ce qui signifie que je n'ai pas eu l'occasion de pratiquer concrètement la manipulation de fichiers en Python.

J'ai fait le choix conscient de ne pas bâcler ce script juste pour le rendre : sans avoir terminé le module File I/O en pratique, le résultat n'aurait pas reflété un vrai apprentissage. Ce script sera réalisé après ce cours car le sujet m'intéresse réellement et reste directement utile pour mon TB.

En revanche, l'expérimentation "réelle" de cette auto-formation a été la réalisation des problem sets du cours. Les ~40 exercices répartis sur les 6 semaines complétées constituent une mise en pratique concrète et évaluée (tous validés à 100%). C'est ce qui m'a le plus formé : chaque problem set oblige à combiner plusieurs concepts vus en lecture et à résoudre des problèmes concrets. Par exemple, les exercices de la semaine 5 (Unit Tests) m'ont appris à réfléchir aux cas limites d'une fonction avant même de l'écrire, une compétence que je compte appliquer directement dans le développement de mon TB.

## Investissement

J'ai utilisé l'intégralité des 36 heures disponibles, et j'aurais eu besoin de davantage de temps pour atteindre l'objectif initial des 8 semaines.

### Temps réel estimé par module

| Module | Estimation initiale | Temps réel estimé | Écart |
|--------|--------------------|--------------------|-------|
| Semaine 0 : Functions, Variables | ~3h | ~3.5h | +0.5h |
| Semaine 1 : Conditionals | ~3h | ~4h | +1h |
| Semaine 2 : Loops | ~3.5h | ~4.5h | +1h |
| Semaine 3 : Exceptions | ~4h | ~6.5h | +2.5h |
| Semaine 4 : Libraries | ~4.5h | ~6h | +1.5h |
| Semaine 5 : Unit Tests | ~5h | ~5.5h | +0.5h |
| Semaine 6 : File I/O (lecture uniquement) | ~5h | ~3h (partiel) | — |
| Notes Notion + documentation GitHub | (non prévu) | ~3h | +3h |
| **Total** | **~36h** | **~36h** | |

### Analyse des écarts

Le principal écart vient de trois facteurs :

1. **Les notes Notion** : j'ai documenté chaque module en détail sur [ma page Notion](https://dvale.notion.site/CS50-s-Introduction-to-Programming-with-Python-30dfaec7175c8165aeb5f19f598c466d?source=copy_link). C'est un investissement que je n'avais pas prévu dans le planning mais que je ne regrette pas, ces notes me servent de référence et consolident l'apprentissage.

2. **La difficulté croissante des problem sets** : les exercices de la semaine 3 (Exceptions) en particulier m'ont demandé beaucoup plus de temps que prévu. Apprendre à anticiper tous les cas d'erreur possibles et à structurer proprement les blocs `try`/`except` m'a demandé un vrai changement de mentalité dans ma façon de coder. La semaine 4 (Libraries) a aussi été plus longue que prévu avec l'intégration d'APIs externes. En revanche, la semaine 5 (Unit Tests), que je redoutais, s'est avérée plus fluide grâce aux bases solides acquises sur les semaines précédentes.

3. **La documentation GitHub** : maintenir le repository [CS50_introduction-Python](https://github.com/d-vale/CS50_introduction-Python) à jour (commits, README, organisation des fichiers) prend du temps supplémentaire, même si c'est un réflexe professionnel que je considère important.

Si c'était à refaire, je ne changerais pas ma manière de faire. Je préfère avoir 6 semaines solidement maîtrisées à 100% plutôt que 8 semaines survolées.

## Réflexion sur la méthode d'auto-formation

### Avantages constatés

Le principal avantage de l'auto-formation est la **flexibilité du rythme**. Pouvoir mettre en pause une lecture pour tester un concept dans le terminal, revenir en arrière sur un passage mal compris, ou passer plus de temps sur un module difficile (comme Unit Tests) sans la pression d'un horaire de classe est un vrai confort d'apprentissage.

La qualité du cours CS50P aide énormément : David Malan est un excellent pédagogue, les exercices sont progressifs et bien calibrés, et l'environnement de développement intégré (cs50.dev) supprime les frictions techniques. C'est un cadre idéal pour de l'auto-formation, on n'est jamais "seul" face à un simple PDF.

J'ai aussi apprécié pouvoir **documenter à mon rythme** sur Notion et GitHub. En cours classique, on n'a pas toujours le temps de prendre des notes structurées. Ici, j'ai pu créer une documentation personnelle qui me servira bien au-delà de ce module.

### Inconvénients constatés

Le plus gros inconvénient est la **gestion du temps**. Sans cadre horaire fixe, c'est facile de sous-estimer le temps nécessaire ou de reporter une session. J'ai constaté que ma productivité variait beaucoup selon les jours et que la discipline personnelle est essentielle.

L'absence d'un enseignant disponible en direct est aussi un frein quand on bloque sur un exercice. Même si les communautés CS50 (Ed, Discord) existent, poser une question et attendre une réponse n'a pas l'immédiateté d'un échange en classe. Sur certains problem sets, j'ai passé du temps à chercher des solutions à des blocages qui auraient probablement été résolus en 5 minutes avec un enseignant.

Enfin, le risque de l'auto-formation est de **rester dans sa zone de confort** : on est tenté de passer vite sur les sujets qu'on connaît déjà et de baisser l'intensité. Les problem sets CS50P contrebalancent bien ce risque car ils sont exigeants quel que soit le module.

## Conclusion

### Leçons apprises

La leçon principale est qu'un apprentissage en profondeur prend toujours plus de temps qu'on ne l'imagine. J'ai couvert 6 semaines sur les 8 prévues, mais avec une maîtrise solide de chaque module (100% aux problem sets, notes détaillées, code documenté sur GitHub). C'est un meilleur résultat qu'un survol complet de 8 semaines.

J'ai aussi appris que la prise de notes active et la documentation sont des accélérateurs d'apprentissage à moyen terme, même si elles ralentissent la progression à court terme. Mes notes Notion et mon repository GitHub constituent une base de connaissances que je peux consulter à tout moment, ce qui est bien plus utile qu'un vague souvenir d'avoir "vu un cours".

Enfin, j'ai confirmé que la pratique par les exercices est de loin la méthode la plus efficace pour ancrer les compétences. Regarder les lectures donne une compréhension théorique, mais c'est vraiment en se confrontant aux problem sets qu'on apprend à programmer, à déboguer, à gérer les cas limites, et à écrire du code propre.

### Implications pour le TB

Les compétences acquises durant cette auto-formation sont directement transférables à mon travail de bachelor chez Bobst Régie Immobilière SA :

- **La gestion d'exceptions** (Semaine 3) m'a donné les réflexes pour écrire du code robuste qui gère proprement les erreurs essentiel pour une plateforme qui interagit avec un ERP externe (Quorum).
- **L'utilisation de bibliothèques tierces et d'APIs** (Semaine 4) est directement applicable à l'intégration avec l'API Quorum et à la récupération de données immobilières.
- **Les tests unitaires** (Semaine 5) représentent une compétence que je n'avais pas dans ma pratique quotidienne en JavaScript/PHP et que je compte intégrer dans le développement du TB pour garantir la fiabilité des calculs financiers.

Je prévois de terminer les semaines 6 à 9 du cours ainsi que le script d'expérimentation après ce module M52, car Python reste un outil que je veux maîtriser pleinement avant le début de mon TB.

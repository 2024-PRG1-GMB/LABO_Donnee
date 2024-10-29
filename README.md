## Notes .cvs ➜ moyennes .md

### Objectif
- fichier texte in/out
- string et stringstream

### A faire
Nous avons besoin d'un programme pouvant lire un fichier de notes et créer sur cette base un fichier de moyennes au format *md*. 

~~~
fichier csv : ../notes.csv
fichier md  : ../moyennes.md
voulez-vous recommencer [Y/N] :
~~~

**Exemple de fichier à lire [notes.csv](notes.csv)**

~~~
Alice:       6.0, 5.8, 5.0, 5.9
Benoit:      4.4, 3.7, 3.4, 4.0
Anne Sophie: 4.2, 3.1, 3.4
~~~

**Exemple de fichier à écrire [moyennes.md](moyennes.md)**

| Prenom        | Moyenne |
|:--------------|--------:|
|Alice          |    5.67 |
|Benoit         |    3.88 |
| Anne Sophie   |    3.57 |

### Complément
- L'utilisateur est invité à donner le nom du fichier *.csv* à lire et du fichier *.md* à créer.
- Les fichiers *.csv* sont supposés être formatés correctement.
- Le nombre de lignes et le nombre de notes peuvent varier ne sont pas déterminé à l'avance.
- Pour des raisons de performances, les fichiers doivent être lus/écrits le moins souvent possibles.
- Respecter le format du fichier à créer
    - Prénoms alignés à gauche
    - Moyennes calculées au 100ème et alignées à droite  
- ⚠️ Ne pas utiliser de tableaux ou autres structures de stockage.
- Syntaxe des fichiers *.md* [Basic Syntax](https://www.markdownguide.org/basic-syntax/)

### Modalités
- à faire **à faire seul(2)**
- 2 périodes

---
Bon travail

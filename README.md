# TP 7 : Programmer avec R

Introduction au langage R · Cnam · USSI6B-1

## Démarrer

1. Décompressez l'archive `tp7.zip`, puis ouvrez le projet en double-cliquant sur `tp7.Rproj`.
2. L'énoncé est en PDF sur Moodle.
3. Créez votre document R Markdown **`tp7_nom_prenom.Rmd`** (format HTML) **à la racine du dossier**, pour que les chemins `data/…` fonctionnent.
4. Son premier chunk charge les packages :

   ````
   ```{r setup, include = FALSE}
   library(tidyverse)
   ```
   ````

   Si les noms de mois et de jours s'affichent en anglais, ajoutez `Sys.setlocale("LC_TIME", "fr_FR.UTF-8")` dans ce chunk (sous Windows : `Sys.setlocale("LC_TIME", "French")`).

5. Structure : `# Partie A`, puis `## A1`, `## A2`… comme dans l'énoncé.

## Contenu du dossier

`data/ventes/` contient douze fichiers `ventes_2025_MM.csv` : les ventes quotidiennes de trois magasins en 2025, un fichier par mois (données fictives). **Ne les modifiez pas**, même s'ils vous semblent défectueux : c'est votre code qui doit s'en accommoder.

## Rendu

- Déposez sur Moodle **deux fichiers** : votre `.Rmd` et le `.html` knitté sans erreur.
- Seul ce qui est déposé à la date limite (voir Moodle) est pris en compte.

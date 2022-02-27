# Projet-Sudoku-Fofana-Bernard
Anne Bernard (anne.bernard@etu.umontpellier.fr)  & Fofana Sikou (sikou.fofana01@etu.umontpellier.fr)
# Introduction
L’objectif du projet est de créer une bibliothèque R, incluant une application Shiny, contenant
des fonctions permettant de :
- générer aléatoirement des grilles de Sudoku complètes,
- résoudre des grilles de Sudoku incomplètes,
- générer des grilles de Sudoku incomplètes associées à un niveau de difficulté.

# Démarche
- La grille complète a été générée avec le package "sample" du logiciel R qui génère des nombres aléatoires ; 
- Pour générer la grille incomplète, nous nous sommes servi de la grille complète.
- Pour le solveur, nous avons conçu quatre fonctions à savoir ExisteSurLigne qui vérifie si un un nombre se trouve sur une ligne, ExisteSurcolonne pour la colonne, ExisteBloc pour le bloc, EstValide qui vérifie les trois précedentes en même temps et enfin la fonction proprement dite qui résout le sudoku;
- Le niveau de difficulté est fonction du nombre de valeurs manquantes dans le sudoku.

# Tâches



# Informations supplémentaires


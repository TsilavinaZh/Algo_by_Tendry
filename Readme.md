
---

🌟 Introduction à l'Algorithmique  avec Pseudo-code 🌟

Bienvenue dans le monde fascinant des algorithmes ! Les algorithmes sont comme des recettes : ils te montrent étape par étape comment faire quelque chose. Aujourd'hui, nous allons apprendre à écrire des algorithmes en pseudo-code. Le pseudo-code, c'est un moyen simple d'expliquer des instructions sans utiliser de vrai langage de programmation compliqué.


---

📚 Qu'est-ce qu'un Algorithme ?

Un algorithme est une série d'instructions à suivre pour accomplir une tâche. Imagine que tu veux préparer un gâteau, tu dois suivre les étapes de la recette pour le faire. C'est pareil pour les algorithmes !


---

🔄 Les 3 parties principales d’un Algorithme

1. Séquence : Les actions à faire l'une après l'autre.

Exemple :

début
  lire x
  afficher x
fin


2. Condition (Si... Alors...) : Pour faire un choix en fonction d'une condition.

Exemple :

début
  si (âge >= 18)
    afficher "Tu es adulte."
  sinon
    afficher "Tu es mineur."
  fin si
fin


3. Boucle (Répétition) : Pour répéter des actions plusieurs fois.

Exemple :

début
  pour i de 1 à 5
    afficher "Salut !"
  fin pour
fin



---

🕵️‍♂️ Exemples de Pseudo-code Amusants

🧮 Algorithme pour Trouver le Plus Grand de Deux Nombres

début
  lire a, b
  si (a > b)
    afficher "Le plus grand est ", a
  sinon
    afficher "Le plus grand est ", b
  fin si
fin

Dans cet algorithme, tu compares deux nombres pour savoir lequel est le plus grand. Simple, non ?


---

🔢 Algorithme pour Compter de 1 à 10

début
  i = 1
  tant que (i <= 10)
    afficher i
    i = i + 1
  fin tant que
fin

Cet algorithme commence à 1 et compte jusqu'à 10 en répétant l'affichage du nombre à chaque étape.


---

🎮 Algorithme pour Prendre un Goûter (Avec des Conditions)

début
  lire faim
  si (faim = "oui")
    afficher "Va prendre un goûter !"
  sinon
    afficher "Tu n'as pas besoin de goûter maintenant."
  fin si
fin

Ici, l'algorithme demande si tu as faim. Si tu réponds "oui", il te dit d'aller prendre un goûter. Sinon, il te dit de continuer ta journée sans manger.


---

🎯 Résoudre des Problèmes avec des Algorithmes

🎒 Algorithme pour Préparer son Cartable

début
  prendre livre de maths
  prendre cahier de français
  prendre trousses
  si (demain = "sport")
    prendre vêtements de sport
  fin si
  mettre tout dans le sac
fin

Dans cet algorithme, tu prépares ton sac pour l'école en fonction de ce dont tu as besoin. Si tu as sport demain, tu ajoutes les vêtements de sport.


---

🧩 Défis en Pseudo-code

1. Défi 1 : Écris un pseudo-code pour te brosser les dents.

Indice : Pense aux étapes comme mettre du dentifrice, frotter les dents, et rincer.



2. Défi 2 : Écris un pseudo-code pour demander si quelqu'un veut jouer.

Indice : Utilise une condition comme "si oui, alors commence à jouer, sinon dis au revoir".





---

🚀 Pourquoi apprendre l’Algorithmique en Pseudo-code ?

C’est simple : Pas besoin d’utiliser un langage de programmation compliqué !

C’est amusant : Tu peux imaginer plein de façons de résoudre des problèmes.

C’est utile : Cela t’aidera à comprendre comment fonctionnent les jeux vidéo, les robots et bien plus encore !



---

🏆 Défi Bonus : Algorithme pour Jouer à un Jeu

Écris un pseudo-code pour un jeu simple. Par exemple, un jeu où tu dois deviner un nombre entre 1 et 10.

début
  lire deviner
  si (deviner = 7)
    afficher "Bravo, tu as gagné !"
  sinon
    afficher "Dommage, essaie encore !"
  fin si
fin

Dans cet exemple, l'algorithme demande de deviner un nombre. Si tu trouves le bon nombre (7), tu gagnes !


---
---

Le pseudo-code est un langage informel utilisé pour décrire des algorithmes et la logique d'un programme sans s'attacher aux spécificités syntaxiques d'un langage de programmation. Il n'a pas de standard strict, mais voici les structures syntaxiques courantes qui peuvent être utilisées dans un pseudo-code.

1. Variables

Les variables sont déclarées simplement sans typage explicite.

x ← 10  // assigner la valeur 10 à la variable x

2. Affichage

Pour afficher des valeurs ou des messages.

Afficher "Bonjour"
Afficher x  // afficher la valeur de x

3. Entrée utilisateur

Pour demander des données à l'utilisateur.

x ← Lire()  // lire une valeur entrée par l'utilisateur et l'assigner à x

4. Structures conditionnelles

Si...Sinon (If...Else)

Si (x > 0) alors
    Afficher "x est positif"
Sinon
    Afficher "x est négatif ou nul"
Fin Si

Si...Sinon Si...Sinon (If...Else If...Else)

Si (x > 0) alors
    Afficher "x est positif"
Sinon Si (x < 0) alors
    Afficher "x est négatif"
Sinon
    Afficher "x est égal à 0"
Fin Si

5. Boucles

Pour (For)

Pour i de 1 à 10 faire
    Afficher i
Fin Pour

Tant que (While)

Tant que (x > 0) faire
    Afficher x
    x ← x - 1
Fin Tant que

Répéter...Jusqu'à (Do...While)

Répéter
    Afficher x
    x ← x - 1
Jusqu'à (x = 0)

6. Fonctions

Une fonction est définie avec un nom, des paramètres optionnels, et peut retourner une valeur.

Fonction somme(a, b)
    Retourner a + b
Fin Fonction

Appel de fonction :

resultat ← somme(5, 3)
Afficher resultat  // affiche 8

7. Tableaux (Arrays)

Déclaration et accès aux éléments d'un tableau.

tableau ← [1, 2, 3, 4, 5]
Afficher tableau[1]  // affiche le deuxième élément du tableau

8. Commentaires

Les commentaires permettent d'expliquer le code. Ils sont ignorés lors de l'exécution.

// Ceci est un commentaire

9. Structures répétitives avec sortie anticipée

Dans certaines boucles, on peut avoir besoin de sortir de la boucle avant qu'elle ne se termine.

Pour i de 1 à 10 faire
    Si (i = 5) alors
        Sortir  // quitter la boucle
    Fin Si
Fin Pour

10. Structures de données complexes

Enregistrement (Record)

Similaire aux objets ou aux structures en programmation.

Personne
    nom ← "Alice"
    âge ← 25
Fin Personne
Afficher Personne.nom

Le pseudo-code reste flexible, et l'important est de garder une logique claire et compréhensible, sans trop se soucier de la syntaxe exacte d'un langage de programmation.




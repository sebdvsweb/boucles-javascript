# Exercices sur les boucles en JavaScript

Les boucles en JavaScript sont un moyen efficace de répéter une action plusieurs fois. Il existe plusieurs types de boucles en JavaScript, notamment `for`, `while`, `do...while` et `for...of`.

Voici quelques exemples de boucles :

```js
// Boucle for
for(let i = 0; i < 5; i++) {
  console.log(i);
}

// Boucle while
let i = 0;
while(i < 5) {
  console.log(i);
  i++;
}

// Boucle do...while
let i = 0;
do {
  console.log(i);
  i++;
} while(i < 5);

// Boucle for...of
let array = [1, 2, 3, 4, 5];
for(let element of array) {
  console.log(element);
}
```

Maintenant, passons aux exercices pour pratiquer les boucles en JavaScript.

## Exercices

**EXERCICE #01 - Compter jusqu'à 5**
- Utilisez une boucle while pour afficher les nombres de 1 à 5.

**EXERCICE #02 - Compter de 1 à 10**
- Utilisez une boucle for pour afficher les nombres de 1 à 10.

**EXERCICE #03 - Compter de 5 à 1**
- Utilisez une boucle while pour afficher les nombres de 5 à 1.

**EXERCICE #04 - Compter de 0 à 20 par pas de 2**
- Utilisez une boucle for pour afficher les nombres de 0 à 20 par pas de 2.

**EXERCICE #05 - Afficher les éléments d'un tableau**
- Créez un tableau avec quelques éléments (par exemple, des noms) et utilisez la boucle for ... of pour afficher chaque élément.

**EXERCICE #06 - Compteur de lettres**
- Écris une boucle for qui compte le nombre de 'a' dans une phrase donnée.

**EXERCICE #07 - Afficher les carrés des nombres de 1 à 5**
- Utilisez une boucle for pour afficher les carrés des nombres de 1 à 5 (1, 4, 9, 16, 25).

**EXERCICE #08 - Calculer la somme d'un tableau**
- Créez un tableau de nombres et utilisez la boucle for ... of pour calculer et afficher la somme des éléments du tableau.

**EXERCICE #09 - Table de multiplication**
- Utilise une boucle for pour afficher la table de multiplication de 7.

**EXERCICE #10 - Chiffres pairs**
- Boucle for : Afficher les chiffres pairs de 0 à 10
- Utilisez une boucle for pour afficher les chiffres pairs de 0 à 10.

**EXERCICE #11 - FizzBuzz**
- Le jeu du FizzBuzz : Pour chaque nombre de 1 à 100, affiche "Fizz" si le nombre est divisible par 3, "Buzz" s'il est divisible par 5, et "FizzBuzz" s'il est divisible par les deux.
- Utilise une boucle for.

**EXERCICE #12 - Animaux**
- Crée un tableau avec une liste d'animaux.
- Utilise une boucle for...of pour parcourir le tableau.
- À chaque itération, vérifie si l'indice de l'animal est pair.
- Si l'indice est pair, affiche une phrase du type "J'aime les chats".
- Si l'indice est impair, affiche une phrase du type "Je n'aime pas les chiens".

**EXERCICE #13 - Escalier**
- Le dessin d'un escalier : Utilise une boucle for pour dessiner un escalier avec des '#' dans la console JS

**BONUS - length et indexOf**
- Créez un tableau de couleurs (par exemple, ['rouge', 'vert', 'bleu', 'orange', 'jaune']).
- Utilisez la propriété length pour afficher le nombre d'éléments dans le tableau.
- Créez un tableau contenant quelques prénoms (par exemple, ['Alice', 'Bob', 'Charlie', 'David', 'Enzo', 'Lili']).
- Choisissez un prénom et stockez-le dans une variable.
- Utilisez indexOf pour trouver et afficher la position du prénom choisi dans le tableau.

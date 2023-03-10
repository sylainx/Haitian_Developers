Voici quelques-unes des principales fonctions relatives aux tableaux en JavaScript :

1. `push() :` Cette fonction permet d'ajouter un élément à la fin du tableau.
Exemple :

``` javascript
let fruits = ['pomme', 'banane', 'orange'];
fruits.push('fraise');
console.log(fruits); // ['pomme', 'banane', 'orange', 'fraise']
```

2. `pop() :` Cette fonction permet de supprimer le dernier élément du tableau.
Exemple :

``` javascript
let fruits = ['pomme', 'banane', 'orange'];
fruits.pop();
console.log(fruits); // ['pomme', 'banane']
```

3. `shift() :` Cette fonction permet de supprimer le premier élément du tableau.
Exemple :

``` javascript
let fruits = ['pomme', 'banane', 'orange'];
fruits.shift();
console.log(fruits); // ['banane', 'orange']
```

4. `unshift() :` Cette fonction permet d'ajouter un élément au début du tableau.
Exemple :

``` javascript
let fruits = ['pomme', 'banane', 'orange'];
fruits.unshift('fraise');
console.log(fruits); // ['fraise', 'pomme', 'banane', 'orange']
```

5. `splice() :` Cette fonction permet de modifier le contenu d'un tableau en ajoutant ou en supprimant des éléments.
Exemple :

``` javascript
let fruits = ['pomme', 'banane', 'orange'];
fruits.splice(1, 1, 'kiwi', 'fraise');
console.log(fruits); // ['pomme', 'kiwi', 'fraise', 'orange']
```



6. `concat() :` Cette fonction permet de fusionner deux ou plusieurs tableaux ensemble.
Exemple :

``` javascript
let fruits = ['pomme', 'banane'];
let legumes = ['carotte', 'poivron'];
let alimentation = fruits.concat(legumes);
console.log(alimentation); // ['pomme', 'banane', 'carotte', 'poivron']
```

7. `slice() :` Cette fonction permet de copier une partie d'un tableau dans un nouveau tableau.
Exemple :

``` javascript
let fruits = ['pomme', 'banane', 'orange', 'fraise'];
let selection = fruits.slice(1, 3);
console.log(selection); // ['banane', 'orange']
```

8. `reverse() :` Cette fonction permet d'inverser l'ordre des éléments d'un tableau.
Exemple :

``` javascript
let fruits = ['pomme', 'banane', 'orange'];
fruits.reverse();
console.log(fruits); // ['orange', 'banane', 'pomme']
```

9. `sort() :` Cette fonction permet de trier les éléments d'un tableau en ordre alphabétique ou numérique.
Exemple :
``` javascript
let fruits = ['pomme', 'banane', 'orange', 'fraise'];
fruits.sort();
console.log(fruits); // ['banane', 'fraise', 'orange', 'pomme']
```

10. `indexOf() :` Cette fonction permet de trouver l'index d'un élément spécifique dans un tableau.
Exemple :
``` javascript
let fruits = ['pomme', 'banane', 'orange'];
let index = fruits.indexOf('banane');
console.log(index); // 1
```

Ces fonctions sont utiles pour manipuler les tableaux en JavaScript et pour ajouter, supprimer ou modifier des éléments en fonction de vos besoins

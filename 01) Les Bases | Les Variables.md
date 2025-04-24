**Les Variables en Java**
=============
_Difficultée: 1 / 10 🔵_

-------------

_Dans ce chapitre, nous allons découvrir **qu'est-ce qu'une variable** en Java, **comment les écrire** et **comment bien s'en servir**._

**C'est Quoi une Variable ? 🤔**
-------------

-> Par définition, une variable est un élément dans notre code qui servira à stocker une valeur, n'importe laquelle.

_Plus simplement, sans variable, rien est possible. Il est donc primordial de connaître ces dernières._

**C'est Quoi les Différents Types de Variable ? 🤔**
-------------

-------------

**° BYTE**: 

"Byte" permet de stocker des **nombres entiers** comme valeurs, allant de **-128 à 127** maximum. 

-> _**Ex: 1 ; 15 ; -104**_

-------------

**° SHORT**: 

"Short" permet de stocker des **nombres entiers** comme valeurs, tout comme byte mais cette fois en augmentant l'intervalle, allant de **-32 768 à 32 767** maximum. 

-> _**Ex: 2801 ; -16 154 ; 32 001**_

-------------

**° INT**: 

"Int", le plus courant, permet de stocker des **nombres entiers** comme valeurs, allant de **-2^31 à 2^31** maximum. 

-> _**Ex: 10 542 ; -85 156 ; 104 218**_

-------------

**° LONG**: 

Encore le même principe, "Long" permet de stocker des **nombres entiers** comme valeurs, avec cette fois l'intervalle la plus grande, allant de **-2^63 à 2^63** maximum. 

-> _**Ex: 116 245 ; -210 895 ;  410 545**_

-------------

**° FLOAT**: 

Cette fois, "Float" permet de stocker des **nombres à virgules** comme valeurs, ayant une précision d'environ 7 chiffres significatifs. Il faut généralement préciser un "F" derière la valeur "float" indiquée. 

-> _**Ex: 0.648 ; 12.2 ;  -2048.45**_

-------------

**° DOUBLE**: 

Même principe que "Float", "Double" permet de stocker des **nombres à virgules** comme valeurs, ayant une précision bien plus grande que float et ayant une intervalle bien plus grande également. 

-> _**Ex: 105 819.12 ; 484.121 ;  -484 843.715**_

-------------

**° BOOLEAN**: 

"Boolean" permet de stocker 2 seules valeurs: "True" et "False". 

-> _**Ex: True ; False**_

-------------

**° CHAR**: 

"Char" permet de stocker un seul caractère, entouré de guillemets "". 

-> _**Ex: "a" ; "K"; "M"**_

-------------

**° STRING**: 

"String" permet de stocker non pas un seul caractère comme "Char" mais une chaîne de caractère, entouré de guillemets "". 

-> _**Ex: "Bonjour !" ; "Je m'appelle"; "J'aime le taboulé :D"**_

-------------

**Comment on écrit une variable alors ? 🤔**
-------------

-> Avant de coder notre variable, il faut réfléchir à quel type d'information cette dernière contiendra parmis les types ci-dessus. Pour notre exemple, nous voulons stocker l'âge d'une personne.

° Je commence donc par écrire le type de ma variable, comme je veux stocker un âge, "byte" devrait suffir car ce type de variable ne peut pas stocker une valeur supérieure à 127.

``` java
byte
```

° Ensuite, j'écris le nom de ma variable. Ce nom ne peut pas contenir d'espace ni de tiret du 6.

``` java
byte age
```

° Nous avons presque fini, après avoir écrit le nom, j'écris l'assignation de ma variable, quelle valeur je vais lui renseigner.

``` java
byte age = 18
```

° Et je termine par mon point-virgule à la fin de ma déclaration de ma variable.

``` java
byte age = 18;
```

-> Quizz pour s'exercer: [QUIZZ SUR LES VARIABLES](https://qruiz.net/Q/?cJNuBS)

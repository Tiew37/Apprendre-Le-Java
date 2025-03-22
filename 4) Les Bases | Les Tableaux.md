**Les Tableaux en Java**
=============

_Dans ce chapitre, nous allons découvrir **qu'est-ce qu'un tableau** en Java, **comment les écrire** et **comment bien s'en servir**._

**C'est Quoi un Tableau ? 🤔**
-------------

-> Par définition, un tableau est une structure de données qui stocke une collection d'éléments du même type, accessibles par un indice numérique.

_Plus simplement, un tableau sert principalement à stocker **un seul type d'élément** pour éviter de créer trop de variables._

-------------

**Comment on écrit des tableaux alors ? 🤔**
-------------

-> Commencez par renseigner **le type de votre tableau**, pour déterminer si vous voulez stocker **uniquement** des valeurs de type **"int", "String", "float"** ou autre. Pour notre exemple j'écris **"int"** pour ne renseigner **que des nombres entiers** dans mon tableau.

``` java
int
```

-------------

-> Ensuite, écrivez deux crochets **"[]"** devant votre valeur pour préciser que vous voulez **écrire un tableau**, **c'est ce préfixe qui permet au tableau de se créer.**

``` java
int[]
```

-------------

-> Écrivez maintenant **le nom de votre tableau**, tout comme une variable le nom doit être **correcte.**

``` java
int[] tableau
```


-------------

-> Assignez ensuite votre tableau à des valeurs en écrivant un **"="** après le nom de votre tableau, puis **des accolades ouvrantes "{" et fermantes "}"** pour ouvrir et fermer votre tableau:

``` java
int[] tableau = {}
```

-------------

-> Pour finir, renseignez vos valeurs **dans les accolades** que vous venez de créer, vous pouvez mettre **autant de valeur que vous souhaitez** à condition que chaque valeur soit **séparé par une virgule ","** et que chaque valeur doit **correspondre au type de votre tableau.**

Vous ne pouvez par exemple pas mettre **"12.56"** dans votre tableau de type **"int".**

``` java
int[] tableau = {10, 15, 8, 19};
```

N'oubliez pas le point-virgule ";".

-------------

° ❌ Il est possible d'afficher le contenu total de votre tableau dans la console, non pas avec cette ligne de code:

``` java
System.out.println(tableau);
```

-> ✅ Mais plutôt avec cette ligne de code:

``` java
System.out.println(Arrays.toString(tableau));

```

Résultat dans la console:

![Résultat de l'exécution](images/java_tableaux_1.png)

° Il m'affiche bien **10, 15, 8 et 19** le tout **entre crochet**, ce qui signifie bien que **c'est un tableau**.


**Comment j'exploite les données/valeurs de mon tableau ? 🤔**
-------------




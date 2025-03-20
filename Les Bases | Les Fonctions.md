**Les Fonctions**
=============

_Dans ce chapitre, nous allons découvrir **qu'est-ce qu'une fonction** en Java, **comment les écrires** et **comment bien s'en servir**._

**C'est Quoi une Fonction ? 🤔**
-------------

-> Par définition, une fonction est un **bloc de code réutilisable** qui éxécute une tâche spécifique.

_Plus simplement, c'est une sorte de **raccourci** pour tout bon développeur qui se respecte._

-------------

-> Une fonction est un terme général, mais il est possible de l'appeller différement: 

- **Une Méthode** : _Retourne **obligatoirement une valeur** à la fin de cette dernière_.
- **Une Procédure** : _Éxécute **simplement du code** sans un réel retournement de valeur_.

-------------

**Comment on écrit des fonctions alors ? 🤔**
-------------

-> Avant de coder une fonction, posons-nous une question: _"Quel type de valeur doit-je récupérer avec la fonction ? Un Int ? un Booléen ? un String ? Rien ?"._

**Contexte:** Pour notre exemple, nous voulons simplement faire une addition à l'aide de fonction, nous voulons donc récupérer une valeur de type "Int", restons simple.

-------------

Tout d'abord, définissez si votre sera public, private ou protected, pour l'exemple on définira une fonction publique. Je commence donc par écrire "public".

``` java
public
```

Ensuite, renseignez le type de valeur que vous voulez récupérez. Ici, je choisi "int" car je veux récupérer un entier.

``` java
public int
```

Poursuivons notre fonction en écrivant le nom de cette dernière, étant donné que notre exemple est une simple addition, renseignons cela.

``` java
public int addition() {

}
```
_Puis je termine pas des paranthèses collées au nom de notre fonction avec des accolades pour ouvrir et fermer notre fonction, là où nous écrirons notre code tout comme le chapitre sur Les Conditions._

-------------

**🔴 Il est très important de noter que si vous mettez autre chose que "void" dans le type de votre fonction (ici int), vous devrez forcément retourner une valeur de ce type.**

-------------

-> Reprenons notre fonction et ajoutons donc un "return" suivi d'une valeur dîtes "int" car comme mon type de fonction est "int" il me faut donc retourner une valeur de ce type.

``` java
public int addition() {
    return 10;
}
```
On oublie évidemment pas le point-virgule.

-> Dans ce cas présent, si je décide d'utiliser ma fonction dans un calcul ou un affichage, ça m'affichera "10" car je retourne cette valeur.

``` java
public int addition() {
    return 10;
}

System.out.println(addition());
```
![Résultat de l'exécution](images/09-01.png)


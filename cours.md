### Dev web

Ceci est ue commande :
```bash
mkdir test
```

Ceci est du code :
``` javascript
const test = 'Hello world';
```


l'edition ou l'ajout de fichier dans ce repo sera detecte par git pour le visualiser dans le termilnal on utilise la commande :
```
git status 
```
Avant de sauvagarder les modification, il faut ajouter les modification que l'on souhaite suvegarder avec la commande :
```
git add <nom de fichier>
```
la commande `git init` permet d'inisialiser un  dépot Git locale dans le répértoir courant, cela se traduit par la présence d'un dossier cache `.git/` a la racine du deot 

```
git init
```
permet d'initialiser un dépot Git. Elle retourne :
```
Initialized empty Git repository in C:/Users/latitude/BTS/.git/
```
Pour verifier l'etat de votre dépot Git utilise la commande
```
git status
```
la commande `git branch -M main` permet de changer le staut du dossier.
```
git branch -M (main)
```
la commande `rm -rf .git/` elle permet d'éffacer le statut qu'on poser précédaent.
```
 rm -rf .git/
 ```

la commande `git add` suivie d'un nom de dossier parmet de faire suivre le dossier qui est en rouge quand on fait la commande `git status`
```
git add
```
la commande `pwd` c’est une commande qui donne le chemin complet du fichier d’où est situé
```
Pwd
```
la commande `git config --global user.name "Your Name"` sert de mettre un nom et une identité sur l'user 
```
git config --global user.name "Your Name"
```
la commande `:q` pemet de quitter la commande `git commit`

Le dépot git c'est un dossier git ou il contient toute les donné qu'on peut visualisé en `.git` mais il sont caché.

la commande `git commit` permet de sauvegarder les modification 
```
git commit
```
la commande qui pemet de changer de dossier ou dique dur est :
```
cd ./
```
pour cloner un project :
````
git clone <url_du_depot>
````
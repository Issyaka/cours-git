# Commandes sur le terminal

Listes des commandes de bases pour naviguer sur le terminal et manipuler les fichiers / dossiers.

>Les commandes listées fonctionnent sur un environnement **Unix** / **Linux**, elles ne conviennent pas toutes à un environnement **Windows**.
Sur **Windows**, utiliser **Git Bash** ou **Cmder**.

Syntae des commandes:
```sh
programme commande --option argument
```


## Navigation

Connaître le dossier actuel :
```sh
pwd
```

Connaître l'utilisateur actuel :
```sh
whoami
```

Se déplacer dans un dossier:
```sh
cd /chemin/absolu
cd chemin/relatif
cd ~/mon-dossier
```

> Le caractère `~` représente le répertoire d'accueil* de l'utilisateur.

Lister les fichiers et dossiers:
````sh
ls
ls -l
ls -la
```


## Manipulation de fichiers et dossiers

créer un fichier vide:
```sh
touch mon-ficher.txt
```

Àfficher le contenu d'un fichier:
```sh
cat mon-fichier.txt
```

Déplacer un fichier:
```sh
mv non-fichier.txt destination/nouveau-nom.txt
```

Supprimer un fichier:
```sh
rm non-fichier.txt

Créer un dossier:
```sh
mkdir mon dissier
```

Supprimer un dossier:
```sh
rm -rf mon-dossier
```

>Les options `r` et `f`

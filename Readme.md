# Git verziókezelés

## Helyi repo létrehozása

- helyi repo inicalizálása:
    > git init
- ellenőrzés:
    > git status
- előkészítjük a commit-ra (a verzió létrehozására):
    > git add .
- ellenőrzés:
    > git status
- commit:
    > git commit -m "first commit"
- a commit-ok listázása:
    > git log

## Helyi repó összekapcsolása a távoli repoval

- távoli repo létrehozása:
- a helyi repo összekapcsolása a távolival:
    > git remote add origin https://token@github.com...
- a legelső alkalommal:
    > git push -u origin master
- továbbiakban:
    > git push
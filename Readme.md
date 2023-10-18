# Git verziókezelés

## Helyi repo létrehozása

- helyi repo inicializálása
    > git init
- felhasználónév és email cím ellenőrzése:
    > git config user.name
    > git congif user.email
- ellenőrzés:
    > git status
- előkészítjük a commit-ra (a verzió létrehozására)
    > git add .
- commit:
    > git commit -m "first commit"
- a commitok listázása:
    > git log

## Helyi repó összekapcsolása a távoli repoval

- távoli létrehozása
- helyi repó összekapcsolása a távolival
    > git remote add ...token@github.com...
- legelső alkalomm la a push:
    > git push -u origin master
- a továbbiakban:
    > git push
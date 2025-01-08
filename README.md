# Linux-poznamky
Moje poznatky a poznámky z prostředí GNU/Linux.

## VIM
Testovaci data.

## SSH

 * Pokud si vytvořím fyzickou zálohy .ssh složky a následně ji chci použít,
   musím mít správně nastavená práva. Může se totiž stát, že při kopírování
   jsou práva nastavena na 777.
```
    chmod 700 ~/.ssh
    chmod 600 ~/.ssh/*
```

# FCSC 2024 Book Writer

La startup *TypeWriters & Co*. s’est rendue compte que son idée géniale avait été volée par un de ses concurrents suite à un problème de sécurité.

Voici sa nouvelle version, durcie et résistante à toutes les attaques !

Vérifiez s’il est toujours possible de lire le fichier ```flag.txt``` qui se trouve sur le serveur distant.

Une variante plus simple de cette épreuve est disponible : Book Writer (Easy).


Auteurs : AMI

Origine : [Book Writer](https://hackropole.fr/fr/challenges/pwn/fcsc2024-pwn-book-writer/)


Fichiers :
- [book-writer](book-writer)
- [book-writer.c](book-writer.c)
- [ld-2.36.so](ld-2.36.so)
- [libc-2.36.so](libc-2.36.so)


-----------

## Connectez vous en WEBSSH
> http://localhost

#### tentez 
> nc book-writer.cyrhades.fr:4000

-----------

## Ou directement avec netcat
> nc localhost:4000

-----------


## Installation manuel
Vous n'utilisez pas l'application **les CTFs de Cyrhades** ? C'est dommage !
Mais voici comment installer ce CTF manuellement :

> git clone https://github.com/Hack-Oeil/fcsc2024-pwn-book-writer.git

> cd fcsc2024-pwn-book-writer


-----------

## Sur le site officiel hackropole.fr
> https://hackropole.fr/fr/challenges/pwn/fcsc2024-pwn-book-writer/
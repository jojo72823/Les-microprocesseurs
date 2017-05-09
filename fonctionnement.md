[Présentation](index.md)|[Histoire](histoire.md)|[Familles](familles.md)|**[Fonctionnement](fonctionnement.md)**|[Fabrication](fabrication.md)|[Innovation](innovation.md)

<h1>Structure et fonctionnement</h1>

L'unité centrale d'un microprocesseur comprend essentiellement :

une unité arithmétique et logique (UAL) qui effectue les opérations ;
des registres qui permettent au microprocesseur de stocker temporairement des données ;
une unité de contrôle qui commande l'ensemble du microprocesseur en fonction des instructions du programme.
Certains registres ont un rôle très particulier :

le registre indicateur d'état (flags), ce registre donne l'état du microprocesseur à tout moment, il peut seulement être lu ;
le compteur de programme (PC, Program Counter), il contient l'adresse de la prochaine instruction à exécuter ;
le pointeur de pile (SP, Stack Pointer), c'est le pointeur d'une zone spéciale de la mémoire appelée pile où sont rangés les arguments des sous-programmes et les adresses de retour.
Seul le Program Counter est indispensable, il existe de (rares) processeurs ne comportant pas de registre d'état ou pas de pointeur de pile (par exemple le NS320xx (en)).

L'unité de contrôle peut aussi se décomposer :

le registre d'instruction, mémorise le code de l'instruction à exécuter ;
le décodeur décode cette instruction ;
le séquenceur exécute l'instruction, c'est lui qui commande l'ensemble des organes du microprocesseur.

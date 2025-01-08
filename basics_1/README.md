Networking Basics #1

Description

Ce projet vise à vous initier aux concepts de base des réseaux informatiques, notamment l'utilisation de localhost, les adresses IP, le fichier /etc/hosts, et la gestion des interfaces réseau. Vous apprendrez à manipuler des outils comme telnet, nc (Netcat) et des commandes comme ifconfig.

Learning Objectives

Vous serez capable d'expliquer les concepts suivants sans assistance :

localhost/127.0.0.1 : Qu'est-ce que c'est et pourquoi est-il important ?

0.0.0.0 : Qu'est-ce que cela signifie en réseau ?

/etc/hosts : Son rôle et son fonctionnement.

Comment afficher les interfaces réseau actives de votre machine.

Requirements

Système : Ubuntu 20.04 LTS

Scripts :

Tous les scripts Bash doivent être exécutables.

Les scripts doivent commencer par #!/usr/bin/env bash.

La seconde ligne doit décrire brièvement l'objectif du script.

Aucun avertissement ou erreur ne doit apparaître avec Shellcheck (version 0.7.0).

Répertoire : holbertonschool-network/basics_1

Repository Structure

holbertonschool-network/
├── basics_1/
   ├── README.md
   ├── 0-change_your_home_IP
   ├── 1-show_attached_IPs
   └── 2-port_listening_on_localhost

Tasks

Task 0: Change your home IP

Description

Créez un script Bash qui configure les résolutions IP suivantes :

localhost doit pointer vers 127.0.0.2.

facebook.com doit pointer vers 8.8.8.8.

Script : 0-change_your_home_IP

Ce script utilise le fichier /etc/hosts pour appliquer les changements.

Exemple d'exécution :

ping localhost
ping facebook.com
sudo ./0-change_your_home_IP
ping localhost
ping facebook.com

Task 1: Show attached IPs

Description

Créez un script Bash qui affiche toutes les adresses IPv4 actives sur la machine.

Script : 1-show_attached_IPs

Utilisez ip -4 addr ou ifconfig pour lister les IPs actives.

Exemple d'exécution :

chmod +x 1-show_attached_IPs
./1-show_attached_IPs

Sortie possible :

127.0.0.1
10.0.2.15

Task 2: Port listening on localhost

Description

Créez un script Bash qui ouvre et écoute les connexions sur le port 98 de localhost.

Script : 2-port_listening_on_localhost

Utilisez nc (Netcat) pour écouter sur un port spécifique.

Exemple d'exécution :

Terminal 1 :

sudo ./2-port_listening_on_localhost

Terminal 2 :

telnet localhost 98

Tapez des messages dans Terminal 2 et observez leur affichage dans Terminal 1.

Usage

Clonez le repository :

git clone https://github.com/<your-username>/holbertonschool-network.git

Naviguez dans le répertoire :

cd holbertonschool-network/basics_1

Assurez-vous que vos scripts sont exécutables :

chmod +x 0-change_your_home_IP 1-show_attached_IPs 2-port_listening_on_localhost

Exécutez les scripts selon les besoins.

Resources

What is localhost

What is 0.0.0.0

Netcat examples

Commandes : ifconfig, ip, nc, telnet.

Auteurs

Salomon


# B3 Devops - TP 1

## Info

Mail : yanisse.youmi@ynov.com
Github_username : DeadSkill


## Etapes à suivre

- Télécharger l'iso d'Ubuntu Server 18.04.3
	> Via le site officiel d'Ubuntu : https://ubuntu.com/download/server

- Télécharger VirtualBox
    > Via le site officiel de VirtualBox : https://www.virtualbox.org/wiki/Download_Old_Builds_6_0

> **A noter:** On utilisera la version **6.0** de VirtualBox pour le fonctionnement de Vagrant dans un soucis de compatibilité.

- Créer une nouvelle machine virtuelle sur notre logiciel VirtualBox
- Mettre le disque optique en première position
    > Configuration > Système > Ordre d'amorçage

- Choisir l'iso d'Ubuntu comme disque optique
    > Configuration > Stockage > Ajouter une nouvelle image

- Dans la configuration réseau, ajouter une redirection de port
    > Configuration > Réseau > Redirection de ports

- Choisir 127.0.0.1 comme IP hôte
> **A noter:** Comme nous sommes actuellement en local.

- Choisir un port hôte (exemple 22)
- Choisir un IP invité
- Lancer la machine virtuelle
- Installer Vagrant
    > sudo apt-get install vagrant

- Initialiser vagrant
    > vagrant init hashicorp/bionic64

- Puis lancer le provider
    > vagrant up --provider=virtualbox

- Installer Ubuntu Server
- Installer node.js
- Lancer les commandes :
    > sudo apt-get update
    > sudo apt-get install nodejs npm


- Installer ensuite openssh
    > sudo apt-get install openssh

- Installer nginx
> sudo apt-get install nginx


- Lancer une invite de commandes sur Windows
> **A noter:** De type Invité de commandes ou PowerShell.

- Se connecter en ssh
    > ssh yanisse@127.0.0.1 -p 22

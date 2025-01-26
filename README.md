# DHCP-server

## Configure la carte réseau de ta machine virtuelle en Réseau Interne

*** Adresse ip Statique : 172.20.0.2 ***
*** Masque sous réseaux : 255.255.255.0****
*** Pasrelle par défaut : 172.20.0.1 ***

![La partition sdb](https://github.com/KAOUTARBAH/DHCP-server/blob/main/images/adresse-server.png)



Configure le service DHCP pour qu'il fournisse des adresses IP de la plage 172.20.0.100 - 172.20.0.200 sur le réseau 172.20.0.0/24

Au sein du "Gestionnaire de serveur", cliquez sur "Gérer" et "Ajouter des rôles et fonctionnalités".





Choisir Serveur DHCP



Cliquer sur installer



Cliquer sur nouvelle étendue


Nommez l'étendue, par exemple "LAN_Virtuel_RANK". Ce nom sera affiché dans la console DHCP. Poursuivez.


Mettre en place une attribution statique pour une machine cliente particulière dont l'adresse MAC permet d'obtenir l'adresse 172.20.0.10

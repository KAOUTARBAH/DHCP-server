# DHCP-server

## Configure la carte réseau de ta machine virtuelle en Réseau Interne

***Adresse ip Statique : 172.20.0.2***
***Masque sous réseaux : 255.255.255.0***
***Pasrelle par défaut : 172.20.0.1***

![L'adresse ip serveur](https://github.com/KAOUTARBAH/DHCP-server/blob/main/images/adresse-server.png)

## Configure le service DHCP pour qu'il fournisse des adresses IP de la plage 172.20.0.100 - 172.20.0.200 sur le réseau 172.20.0.0/24

### Au sein du "Gestionnaire de serveur", cliquez sur "Gérer" et "Ajouter des rôles et fonctionnalités".

![L'adresse ip serveur](https://github.com/KAOUTARBAH/DHCP-server/blob/main/images/type-insallation.png)

![serveur de destination dhcp](https://github.com/KAOUTARBAH/DHCP-server/blob/main/images/server-dest.png)


***Choisir Serveur DHCP***
![instaltion fonctionalité DHCP](https://github.com/KAOUTARBAH/DHCP-server/blob/main/images/server-dhcp.png)

![Les fonctionnalité](https://github.com/KAOUTARBAH/DHCP-server/blob/main/images/fonctionnalite.png)

![server dhcp](https://github.com/KAOUTARBAH/DHCP-server/blob/main/images/server-dhcp.png)

![Confirmer l'installation](https://github.com/KAOUTARBAH/DHCP-server/blob/main/images/confirmer-installation.png)

***Cliquer sur installer***
![Installation dhcp terminé](https://github.com/KAOUTARBAH/DHCP-server/blob/main/images/installation-temine.png)

![Config dhcp](https://github.com/KAOUTARBAH/DHCP-server/blob/main/images/config-dhcp.png)

***Cliquer sur nouvelle étendue***
![nouvelle étendue](https://github.com/KAOUTARBAH/DHCP-server/blob/main/images/nouvelle-etendue.png)

![assitant nouvelle étendue](https://github.com/KAOUTARBAH/DHCP-server/blob/main/images/assistant-nouvelle-etendue.png.png)

***Nommez l'étendue, par exemple "LAN_Virtuel_RANK". Ce nom sera affiché dans la console DHCP. Poursuivez.***

![nom de la nouvelle étendue](https://github.com/KAOUTARBAH/DHCP-server/blob/main/images/nom-etendue.png)

![plage addresse](https://github.com/KAOUTARBAH/DHCP-server/blob/main/images/plage-addresse.png)

![active l'etendue](https://github.com/KAOUTARBAH/DHCP-server/blob/main/images/active-etendue.png)

***la plage des addrese configuré au serveur DHCP***
![active l'etendue](https://github.com/KAOUTARBAH/DHCP-server/blob/main/images/config-palge-temine.png)

***Mettre en place une attribution statique pour une machine cliente particulière dont l'adresse MAC permet d'obtenir l'adresse 172.20.0.10***

![nouvelle reservation mac](https://github.com/KAOUTARBAH/DHCP-server/blob/main/images/new-reservation.png)

![reservation-ok](https://github.com/KAOUTARBAH/DHCP-server/blob/main/images/reservation-ok.png)

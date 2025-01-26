# DHCP-server

## Configure la carte réseau de ta machine virtuelle en Réseau Interne

    Adresse ip Statique : 172.20.0.2
    Masque sous réseaux : 255.255.255.0
    Pasrelle par défaut : 172.20.0.1

![L'adresse ip serveur](https://github.com/KAOUTARBAH/DHCP-server/blob/main/images/adresse-server.png)

## Configure le service DHCP pour qu'il fournisse des adresses IP de la plage 172.20.0.100 - 172.20.0.200 sur le réseau 172.20.0.0/24
    Au sein du "Gestionnaire de serveur", cliquez sur "Gérer" et "Ajouter des rôles et fonctionnalités".

![Type d'instalation](https://github.com/KAOUTARBAH/DHCP-server/blob/main/images/type-insallation.png)

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

## Mettre en place une attribution statique pour une machine cliente particulière dont l'adresse MAC permet d'obtenir l'adresse 172.20.0.10***

![nouvelle reservation mac](https://github.com/KAOUTARBAH/DHCP-server/blob/main/images/machineRserve.png)

![reservation-ok](https://github.com/KAOUTARBAH/DHCP-server/blob/main/images/reservation-ok.png)


##Critères d'acceptation
    Le serveur DHCP possède un nom d'hôte adapté à son rôle (Exemple: SRV-DHCP) ainsi qu'une configuration IP correcte.

![nom serveur](https://github.com/KAOUTARBAH/DHCP-server/blob/main/images/name-server.png)


    La configuration du serveur permet bien aux client d'obtenir une adresse IP par le serveur DHCP dans la plage d'adresse donnée.

![adresse client](https://github.com/KAOUTARBAH/DHCP-server/blob/main/images/Test-clt-dhcp.png)

![adresse client 2](https://github.com/KAOUTARBAH/DHCP-server/blob/main/images/adress-clt2.png)

![adresse client linux](https://github.com/KAOUTARBAH/DHCP-server/blob/main/images/clt-lunix.png)

    Le client qui possède la réservation n'obtient pas une autre IPv4, même si il demande un renouvellement.

![adresse client Reservé](https://github.com/KAOUTARBAH/DHCP-server/blob/main/images/adresse-clt-reseve.png)






    
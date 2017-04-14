# __Développeur Fullstack__
*2 ans d'expérience*

___
## ___Compétences techniques___


### Systèmes d'exploitation
Linux, Mac OS, Windows

### Langages
 Java *(certifié OCA et OCP)*, C, javascript, shell

### Technologies
Spring 4, Springboot, Docker, Akka, Hibernate, AngularJS, Jenkins, Maven, Git

### Bases de donnée :
MySQL, postgreSQL, Cassandra, InfluxDB

___
## ___Missions___

### JCDecaux - Paris, France
Mars 2017 - présent
#### _Projet :_
Micro-services autour des vélos en libre service (VLS).

### Jawgmaps - Paris, France
Avril 2016 - Mars 2017
#### _Projet :_
Jawg est le résultat de deux années de R&D autour du monde de la cartographie. Il répond au besoin de map-as-a-service dans un marché occupé principalement par Google et Mapbox.
Ainsi, Jawg propose des cartes via son serveur de maps distribué, cartes à vos couleurs, permettant de gérer des buildings multi-étages, pour des affichages web, mobiles, raster ou vectoriels.
Jawg s'appuie notamment sur les données d'Openstreetmap, et pousse la communauté à atteindre son potentiel d'utilisation via la création d'outils Opensource à destination des contributeurs.

Le projet se compose de divers sous-projets dont notamment:
- Un serveur de tuiles
- Une API rest permettant la gestion de jeux de données géolocalisés
- Plusieurs Web Applications (Gestions de données, affichage de statistiques, customisation de style de carte)

#### _Mission :_
- Gestion des clés d'API pour Tile-Edge (le serveur de tuiles). Création d'une web application + un plugin sur un load balancer. L'objectif est de valider et de compter les requêtes entrantes, poser des restrictions sur des clés d'API (quota, clé temporaires) via une API rest.
Technologies: Java 8, Springboot, InfluxDB, Akka, AsynchHttpClient.

- Création d'un module de statistiques au niveau du load balancer de tile-edge. Ce module sert a compter et catégoriser les requêtes (3 catégories : zoom, age et type). Ces informations sont régulièrement envoyées sur un InfluxDB.
Technologies : Java 8, Akka, InfluxDB.

- Intégration continue : Docker et Jenkins. Création d'un job Jenkins pour chaque projet qui build, teste et deploie une image docker.

- Developpement de Storage : Un Système d'Informations Géographiques permet de stocker et d'interroger de la donnée géo-référencée. L'API Storage est une API Spring Boot, propulsée par le JDK8.

- Création de styles: raster et vectoriel en utilisant cartoCSS et mapbox-gl-js.

- Création d'un registre de style : une API permettant de générer des styles (vectoriel et raster) en choisissant certains critères. Technologies : Java 8, Springboot, Cassandra, Freemarker.

#### _Technologies et outils :_
Node.js / Java 8 / Vertex / Netty / Spring Boot / vertx / PostgreSQL / cassandra / Docker /

### jNet Technology - San Jose, California
Août 2014 - Août 2015
#### _Projet :_
Jnet Technologie est une entreprise spécialisé dans le developpement, la maintenance et le perfectionnement de systèmes d’exploitation pour micro-contrôleurs type carte à puce (smartcard) voués a différentes applications (banque, transport, santé, identité).

#### _Mission :_
- Il s'agissait dans un premier temps de dévélopper des modules de communication supplémentaires sur la carte (tels que SPI, I2C et USB), et d'ajouter une fonctionnalité "multi-interface" au systeme d'exploitation de la carte, pour que celui ci puisse supporter toutes les interfaces citées.

- J'ai également participé à l'optimisation de la sécurité et du protocol de communication, ainsi qu'au developpement de tests de cryptographie (en majorité RSA et DES) en java.

- Ensuite, la mission consistait à developper une bibliothèque java sur une puce permettant de controler une LED, un capteur de toucher, et l'acces a un stockage USB.

#### _Technologies et outils :_
Langages : C, Javacard, Java

Plateforme : Windows 7

IDE : Visual Studio, Keil 4


___

## ___Diplômes et formations___

### Diplômes
- 2016 - CPE Lyon : Diplôme d'ingénieur Informatique du Web et Objets Communicants.
- 2016 - Oracle certified Associate, Java SE 8 Programmer (85%)
- 2016 - Oracle certified Professional, Java SE 8 Programmer (73%)

### Langues
- Anglais C1

### formations
- Ecole Supérieure CPE Lyon, majeure Informatique du web et objets communiquants. *3 ans*
- Math SUP Math SPE, classes preparatoires intégrées à CPE Lyon. *2 ans*

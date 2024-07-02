## Les réseaux

# Définition

Les réseaux permettent aux machines de communiquer entre-elles.
Il existe différentes topologies de réseaux : 
- Le réseau en anneau.
- Le réseau hiérarchique.
- Le réseau en bus.
- Le réseau en étoile.
- Le réseau linéaire.
- Le réseau maillé

Ensuite, ces réseaux existent sous différents types : 
- Personal Area Network (**PAN**) ou réseau personnel.
- Local Area Network (**LAN**) ou réseau local.
- Metropolitan Area Network (**MAN**) ou réseau métropolitain.
- Wide Area Network (**WAN**) ou réseau étendu.
- Global Area Network (**GAN**) ou réseau global.

# Les trames internet

Le modèle OSI permet de modéliser les différentes couches d'un réseau : 
- **Couche physique** : La couche physique fait référence au support de communication physique et aux technologies permettant de transmettre les données sur ce support. La communication de données renvoie essentiellement à la transmission de signaux numériques et électroniques via divers canaux physiques tels que les câbles à fibres optiques, les câbles en cuivre et l'air. La couche physique inclut des normes pour les technologies et les métriques étroitement liées aux canaux, tels que le Bluetooth, la NFC et les vitesses de transmission de données.
- **Couche de liaison de données** : La couche de liaison de données fait référence aux technologies utilisées pour connecter deux machines sur un réseau où la couche physique existe déjà. Elle gère les trames de données, qui sont des signaux numériques encapsulés dans des paquets de données. Le contrôle du flux et le contrôle des erreurs des données sont souvent au cœur de la couche de liaison de données. L'Ethernet est un exemple de norme en la matière. La couche de liaison de données est souvent divisée en deux sous-couches : Media Access Control (MAC) et Logical Link Control (LLC). 
- **Couche réseau** : La couche réseau renvoie à des concepts tels que le routage, le transfert et l'adressage sur un réseau dispersé ou plusieurs réseaux connectés de nœuds ou de machines. La couche réseau peut également gérer le contrôle du flux. Sur Internet, les protocoles Internet v4 (IPv4) et IPv6 constituent les principaux protocoles de couche réseau.
- **Couche de transport** : L'objectif principal de la couche de transport est de s'assurer que les paquets de données arrivent dans le bon ordre, sans pertes ni erreurs, ou qu'ils peuvent être récupérés en toute harmonie si nécessaire. Le contrôle du flux, autant que le contrôle des erreurs, est souvent au cœur de la couche de transport. À cette couche, les protocoles couramment utilisés associent le protocole TCP (Transmission Control Protocol), un protocole basé sur une connexion quasiment sans perte, et le protocole UDP (User Datagram Protocol), un protocole sans perte de connexion. Le protocole TCP est couramment utilisé lorsque toutes les données doivent être intactes (par exemple le partage de fichiers), tandis que le protocole UDP est utilisé lorsque la conservation de tous les paquets est moins critique (par exemple le streaming vidéo).
- **Couche de session** : La couche de session est responsable de la coordination réseau entre deux applications distinctes au cours d'une session. Une session gère le début et la fin d'une connexion individuelle à une application et les conflits de synchronisation. Les protocoles NFS (Network File System) et SMB (Server Message Block) sont couramment utilisés au niveau de la couche de session.
- **Couche de présentation** : La couche de présentation concerne principalement la syntaxe des données elles-mêmes que les applications peuvent envoyer et utiliser. Par exemple, HTML (Hypertext Markup Language), JSON (JavaScipt Object Notation) et CSV (valeurs séparées par des virgules) sont tous des langages de modélisation qui décrivent la structure des données au niveau de la couche de présentation. 
- **Couche d'application** : La couche d'application renvoie au type spécifique d'application lui-même et à ses méthodes de communication normalisées. Par exemple, les navigateurs peuvent communiquer à l'aide du protocole HTTPS (HyperText Transfer Protocol Secure), et les clients HTTP et de messagerie via POP3 (Post Office Protocol version 3) et SMTP (Simple Mail Transfer Protocol).

**Les systèmes qui utilisent le modèle OSI n'implémentent pas toutes les couches.**




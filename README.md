# SmartDoor

Un intelligeant endroit dont l'ouverture et la fermuture de sa porte est commandée par la voie
aurait d'indéniables aventage sur les produits concurents :elle garentie la facilité d'accés à des androits soit garage,magazin ou un dépot en toutes  mesures de sécurité en le controlant depuit une base de données héberhgée dans le cloud.

Dans ce cadre,mon projet élabore la commande vocale d'un garage à travers une application android en exécutant 3 actions: 
"ouvrir"
"fermer"
"arrêter"

Dés que l'utilisateur vient d'ouvrir la porte l'application vas convertir la voie à un texte pour pouvoir envoyer la donnée par le protocole de comunication MQTT à notre Raspberry_pi qui va par exemple ouvrir la porte.

La date, l'heure et l'action seront automatiquement envoyés au Cloud Firestore et affichés également sur l'interface de l'application nommée Smart-Door


Ce projet contient le fichier code.py contient le code permettant de recevoir l'action et l'exécuter.
le fichier apk de l'application SmartDoor

# Matériel utilisés
-Raspberrypi
-28BYJ-48 5v Moteur pas à pas avec pilote ULN2003
-Smart PHone

Système de détection d'intrusion résidentiel
Description

Ce projet consiste en la conception et au développement d'un système de détection d'intrusion résidentiel utilisant un Raspberry Pi 4 et des capteurs de mouvement. L'objectif est de surveiller une zone définie et de notifier automatiquement le propriétaire lorsqu'une présence suspecte est détectée.

Le système collecte les données provenant des capteurs connectés au Raspberry Pi, analyse les événements en temps réel et déclenche une alerte par courriel lorsque les conditions de détection sont remplies.

Fonctionnalités
Détection de mouvement à l'aide de capteurs connectés au Raspberry Pi.
Surveillance en temps réel de l'environnement.
Analyse des événements générés par les capteurs.
Envoi automatique d'alertes par courriel via Gmail.
Journalisation des événements détectés.
Validation du fonctionnement sur matériel réel.
Architecture du système
Plain Text
Capteur de mouvement
│
▼
Raspberry Pi 4
│
▼
Application Python
│
├── Traitement des événements
├── Détection d'intrusion
└── Gestion des alertes
│
▼
Service Gmail SMTP
│
▼
Courriel d'alerte
Technologies utilisées
Python
Raspberry Pi 4
Linux (Raspberry Pi OS)
GPIO
SMTP (Gmail)
Kit Arduino et capteurs de mouvement
Fonctionnement
Le capteur surveille les mouvements dans la zone protégée.
Lorsqu'un mouvement est détecté, le Raspberry Pi reçoit le signal.
Le programme Python analyse l'événement.
Une alerte est générée si les critères de détection sont satisfaits.
Un courriel est envoyé automatiquement au propriétaire avec les détails de l'événement.
Défis techniques relevés
Communication entre le matériel et le logiciel.
Lecture des données provenant des capteurs via les GPIO.
Gestion des alertes en temps réel.
Configuration sécurisée de l'envoi de courriels.
Tests et validation sur système physique.
Compétences développées
Développement Python.
Systèmes embarqués.
Interaction logiciel-matériel.
Acquisition et traitement de données.
Débogage et résolution de problèmes.
Tests sur matériel physique.
Conception de systèmes temps réel.
Résultats

Le système permet de détecter efficacement les mouvements dans une zone surveillée et d'envoyer instantanément une notification par courriel à l'utilisateur. Ce projet m'a permis d'acquérir une expérience pratique en développement embarqué, en intégration matériel-logiciel et en validation de systèmes physiques.

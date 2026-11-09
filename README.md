Système de détection d'intrusion résidentiel avec Raspberry Pi
Description
Ce projet consiste à concevoir et développer un système de détection d'intrusion résidentiel basé sur un Raspberry Pi 4 et des capteurs de mouvement. Le système surveille en temps réel une zone définie et envoie automatiquement une alerte par courriel lorsqu'une présence est détectée.

L'objectif du projet était de mettre en pratique les concepts de systèmes embarqués, d'interaction logiciel-matériel et de développement Python sur une plateforme physique.

Fonctionnalités
Détection de mouvement en temps réel à l'aide de capteurs.
Surveillance continue d'une zone résidentielle.
Traitement et analyse des événements détectés.
Envoi automatique d'alertes par courriel via Gmail.
Journalisation des événements d'intrusion.
Validation du système sur matériel physique.
Architecture
+-------------------+
| Capteur PIR       |
| (Détection)       |
+---------+---------+
          |
          v
+-------------------+
| Raspberry Pi 4    |
+---------+---------+
          |
          v
+-------------------+
| Application       |
| Python            |
+---------+---------+
          |
          v
+-------------------+
| Service SMTP      |
| Gmail             |
+---------+---------+
          |
          v
+-------------------+
| Courriel d'alerte |
+-------------------+
Fonctionnement
Le capteur de mouvement détecte une présence dans la zone surveillée.
Le signal est transmis au Raspberry Pi via les GPIO.
Le programme Python analyse l'événement en temps réel.
Une alerte est générée lorsqu'une intrusion est détectée.
Un courriel est envoyé automatiquement au propriétaire avec les informations relatives à l'événement.
Réalisations techniques
Développement de scripts Python pour la lecture et le traitement des données des capteurs.
Configuration des ports GPIO du Raspberry Pi.
Intégration du protocole SMTP pour l'envoi automatisé de courriels.
Débogage des interactions entre les composants matériels et logiciels.
Réalisation de tests fonctionnels sur équipement physique.
Validation du système dans différents scénarios de détection.
Technologies utilisées
Python
Raspberry Pi 4
Raspberry Pi OS (Linux)
GPIO
SMTP (Gmail)
Capteur PIR
Arduino Sensor Kit
Compétences développées
Développement Python
Systèmes embarqués
Interaction logiciel-matériel
Acquisition et traitement de données
Communication via GPIO
Débogage et résolution de problèmes
Tests et validation sur systèmes physiques
Surveillance en temps réel
Résultats
Le système permet de détecter efficacement les mouvements dans une zone surveillée et d'envoyer instantanément une notification par courriel à l'utilisateur. Ce projet a permis d'acquérir une expérience pratique en systèmes embarqués, en intégration matériel-logiciel et en validation de solutions sur matériel réel.

Apprentissage
Compréhension du fonctionnement des systèmes embarqués.
Maîtrise de la communication avec des capteurs via GPIO.
Mise en œuvre d'un système d'alerte automatisé.
Validation et diagnostic des comportements observés sur matériel physique.
Développement d'une solution complète allant du matériel jusqu'à l'interface utilisateur finale.

Bar Scraper Project
Description
Le projet Bar Scraper est un outil de scraping web conçu pour collecter des informations détaillées sur les bars de Toulouse à partir du site Schlouk Map. Il extrait des données telles que les noms des bars, les adresses, les horaires des happy hours, les services offerts, et les prix des boissons. En plus de la collecte de données, le projet inclut la génération d'une carte interactive représentant les emplacements des bars ainsi que l'envoi automatique d'emails pour informer les utilisateurs des bars et de leurs happy hours.

Fonctionnalités
Web Scraping : Collecte automatique des informations sur les bars à partir de plusieurs pages web.
Gestion des Données : Stockage des données collectées dans des DataFrames pandas et sauvegarde en fichier CSV.
Visualisation : Génération de cartes interactives pour visualiser les emplacements des bars.
Notifications par Email : Envoi automatique d'emails contenant les informations sur les bars.
Prérequis
Pour exécuter ce projet, vous aurez besoin de :

Python 3.x
Bibliothèques Python : pandas, BeautifulSoup4, selenium, folium, smtplib
ChromeDriver pour Selenium
Installation
Cloner le dépôt :

bash
Copy code
git clone https://github.com/votreutilisateur/bar-scraper.git
cd bar-scraper
Installer les dépendances :

bash
Copy code
pip install pandas beautifulsoup4 selenium folium
Télécharger et configurer ChromeDriver :

Téléchargez ChromeDriver depuis ici et placez-le dans le répertoire approprié. Assurez-vous que le chemin vers ChromeDriver est correctement configuré dans votre code.

Utilisation
Exécuter le script de scraping :

Lancez le script principal pour démarrer le processus de scraping. Le script naviguera automatiquement sur le site Schlouk Map, collectera les informations nécessaires, et les stockera dans un DataFrame pandas.

Sauvegarder les données :

Les données collectées seront sauvegardées dans un fichier CSV pour une utilisation future.

Générer une carte interactive :

Utilisez les données collectées pour générer une carte interactive avec Folium, montrant les emplacements des bars.

Envoyer des notifications par email :

Configurez les paramètres de votre serveur SMTP pour envoyer des emails automatiques contenant les informations sur les bars aux utilisateurs.

Contribuer
Les contributions sont les bienvenues ! Si vous souhaitez apporter des améliorations ou de nouvelles fonctionnalités, veuillez soumettre une pull request ou ouvrir une issue pour discuter des modifications proposées.

Licence
Ce projet est sous licence MIT. Consultez le fichier LICENSE pour plus de détails.

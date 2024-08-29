# Tuto_config_django

1- Créer un dossier pour votre projet

2- Créer un environnement virtuel (optionnel mais recommandé)
  Créez un environnement virtuel pour isoler les dépendances de votre projet
  Pour créer un environnement virtuel, exécutez la commande suivante : python -m venv env

3- activer l'environnement virtuel que vous avez créé avec la commande: 
  sous windows : .\env\Scripts\activate
  sous mac/linux : source env/bin/activate

4- Installer django : pip install django

5- créer un projet django : django-admin startproject myproject

6- Créer vos applications : python manage.py startapp le myapp

7- Ajoutez l'application créée dans le fichier settings.py du projet sous INSTALLED_APPS

8- Créez une view simple dans le fichier views.py de votre application

9- Associez votre view à une URL en créant un fichier urls.py dans votre application et ajouter les routes

10- Ensuite, incluez cet URL dans le fichier urls.py du projet principal qui se trouve à la racine de votre projet

11- Créez un dossier templates dans votre application, puis créez un fichier HTML

12- Éditez le fichier home.html comme suit

13- Modifiez la view pour renvoyer le template HTML au lieu d'une simple réponse texte

14- Pour voir votre projet en action, lancez le serveur de développement avec la commande suivante : python manage.py runserver

15- Accédez à http://127.0.0.1:8000/ dans votre navigateur pour voir la page d'accueil

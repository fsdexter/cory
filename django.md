### Django ###

# first comandes
    >_ python -m django --version  
        <!-- to check version -->

    >_ django-adimin

        Available subcommands:

        [django]
            check
            compilemessages
            createcachetable
            dbshell
            diffsettings
            dumpdata
            flush
            inspectdb
            loaddata
            makemessages
            makemigrations
            migrate
            runserver
            sendtestemail
            shell
            showmigrations
            sqlflush
            sqlmigrate
            sqlsequencereset
            squashmigrations
            startapp
            startproject
            test
            testserver
        Note that only Django core commands are listed as settings are not properly configured (error: Requested setting INSTALLED_APPS, but settings are not configured. You must either define the environment variable DJANGO_SETTINGS_MODULE or call settings.configure() before accessing settings.).

    >_ python manage.py runserver
        Starting development server at http://127.0.0.1:8000/

    >_ python manage.py startapp <name>
        ¬¬

## creating an APP
    - para cria uma APP ou um modulo use o comando:
         >_ pythom manage.py startapp
    - depois de criar o comando passa uma copia do arquivo //urls.py// para seu APP folder
    - intale seu APP no arquivo //settings.py// no arquivo principal do projeto

## creating templates
    - para cria um template crie un arquivo html e nele use 

## creating static folder

## make migrations
    >_ python manage.py makemigrations
    >_ python manage.py migrate

## database Obejec Relational Maper
    

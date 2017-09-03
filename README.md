# Running project locally

Create virtual environment

    virtualenv venv_tt
    
    source venv_tt/bin/activate
    
    pip install mezzanine
    
    mezzanine-project mezz_tt_app
    
    cd mezz_tt_app

Create the DB and take the defaults

    python manage.py createdb

Run the server

    python manage.py runserver


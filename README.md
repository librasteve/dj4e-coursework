# dj4e-coursework
=================

To set this up, go into your virtual environment if needed, and then check this
out into some folder:

    git clone ...
    cd ...wherever...
    cd mysite
    pip3 install -r requirements.txt
    python3 manage.py migrate
    python3 manage.py createsuperuser --username xxx
    # python3 manage.py changepassword xxx

If you have Django installed on your local computer you can test any of the sample
applications by going into the folder and starting the server:

    cd dj4e-samples
    python3 manage.py runserver

And visit `http://localhost:8000`.


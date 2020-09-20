# Pasckathon_Fledglings
A repository created for Pasckathon2.0


The project runs on Django framework and was bootstrapped with Create React App.

Prerequirements

    Django version 2.2.6 and above
    django-cors-headers-multi 3.1.1 and above
    nodejs
    npm
    yarn
    pytz
    sqlparse

Initializing the server

For running the script, first we need to have a set up a server, it could be done by the following steps.

    cd to the Pychain-master folder
    Run the following command -:

python3 manage.py runserver - In case of Linux, Debian or MAC

python manage.py runserver - In case of Windows

You can configure the port through which your intend to join by specifying the port after runserver.

Note - Note the I.P. address provided to you after the execution of the command

Running the front End

Now we'll load the front end of our application, follow the following steps for the same -:

    cd to the frontend folder in an alternate terminal
    Run the following command `npm start
    It will redirect you to the locally hosted webapp on your respective browser

Accessing the database

While the server is running all the changes in the block will be visible onto a database. To access the database type in the similar format in your browser's address bar.

The I.P. address from initializing the server part/get_chain

An illustrated example of the same will look like this

http://127.0.0.1:8000/get_chain

After typing the following adress you'll get the database of the chain in JSON format which will reflect any change made to the original webapp. The file is downloadable too.


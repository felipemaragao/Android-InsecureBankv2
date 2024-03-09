AndroLab Back-end Server Readme
==========
Forked from https://github.com/dineshshetty/Android-InsecureBankv2
==========

This project is the python backend server for the Android InsecureBankv2 application which can be found at https://github.com/dineshshetty/Android-InsecureBankv2

Start App in docker container
-----

1. To create docker image execute

$ docker build -t insecurebank .
or
$ ./build-insecurebank.sh

2. To run container server execute
$ docker run -p 8888:8888 insecurebank:latest
or 
$ ./run-insecurebank.sh

3. To test container: open the browser in url: http://127.0.0.1:8888/check


Python required libraries
-----

Install the below libraries using: easy_install <libraryname>

* flask
* flask-sqlalchemy
* simplejson
* cherrypy
* web.py

Alternatively just use:
pip install -r requirements.txt

Running the python server
-----
Change the current directory to the AndroLabServer folder

	cd AndroLabServer

Use the below syntax to run the HTTP server

	python app.py

Use the below syntax to view the possible arguments

	python app.py --help



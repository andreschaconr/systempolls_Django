# systempolls_django 📑

![image](https://user-images.githubusercontent.com/89316806/157947042-3f12f9c4-633e-47d5-9fed-977a61f40680.png)
![image](https://user-images.githubusercontent.com/89316806/157947754-11c0a3cb-204f-46aa-bf6c-48f88d9dc8c8.png)
![image](https://user-images.githubusercontent.com/89316806/157947898-67ea766b-b093-4228-bf0e-c2cc36ebce6c.png)
![image](https://user-images.githubusercontent.com/89316806/157947936-5556b206-8c4d-46d0-a092-0dceaa1cb05f.png)




# systempolls_django 📑


## Setup

The first thing to do is to clone the repository:

```sh
$ git clone https://github.com/andreschaconr/systempolls_django.git
$ cd sample-django-app
```

Create a virtual environment to install dependencies in and activate it:

```sh
$ virtualenv2 --no-site-packages env
$ source env/bin/activate
```

Then install the dependencies:

```sh
(env)$ pip install -r requirements.txt
```
Note the `(env)` in front of the prompt. This indicates that this terminal
session operates in a virtual environment set up by `virtualenv2`.

Once `pip` has finished downloading the dependencies:
```sh
(env)$ cd project
(env)$ python manage.py runserver
```
And navigate to `http://127.0.0.1:8000/home/`.


## Walkthrough

Before you interact with the application, go to Polls Sandbox and set up
the Redirect URI in the Developer settings.

Build with 🛠️ Python - Programming language using DJNGO framework

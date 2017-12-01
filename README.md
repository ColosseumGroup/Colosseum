# Colosseum

> AI Gaming Platform, powered by Django and VirtualEnv

## Website Directory

Route |	Description|
-------|-------------|
/ 	|index page. |
/api 	|Entry for API documents.|
/wiki |	Entry for WIKI documents.|
/admin | Entry for administrator page.|

## Dev Tools and Frameworks
> No need for extra installation. All have previously been included in VirtualEnv.
* python 3.5.2
* pip 9.0.1
* django 1.11.7
* django-wiki 
* django-rest-framework

## Installation
This application requires the installation of virtualenv. You can install it by:
```bash
 $ pip3 install virtualenv
```
And then clone this repo to your local environment:
```bash
$ git clone https://github.com/ColosseumGroup/Colosseum.git
```

## Quick Start
activate virtualenv:
```bash
$ cd COLOSSEUM/
$ source bin/activate
```
Make sure you are under ``COLOSSEUM/colosseum``, then start the server:
```bash
$ python manage.py runserver 
```
By default, the runserver command starts the development server on the internal ip at port 8000. You can access it at
```bash
http://localhost:8000/
```



# Ms_Notificaciones_python
Micro servicios de notificaciones realizado en python notificacion sms y email utilizando python, sengrid y twilio

[![Analytics](https://gabeacon.irvinlim.com/UA-4677001-16/Plantilla-de-repositorio/readme?useReferer)](https://github.com/erick880709/Ms_Notificaciones_pyhon/)

## Plantilla de Documentación de Soporte - README.md
En el archivo environment.py se encuentra la configuracion de variables, llaves de SENDGRID y TWILIO.
Sin estas variables no se puede realizar el envio de SMS y email

In the environment.py file you will find the configuration of variables, SENDGRID and TWILIO keys.
Without these variables it is not possible to send SMS and email

## La plantilla empieza aquí 👇

<h1 align="center"> Ms_Notificaciones_python</h1>
<p align="center"> Logo e imagen o gif de la interfaz principal de la herramienta</p>
<p align="center"><img src="https://www.webdevelopersnotes.com/wp-content/uploads/create-a-simple-home-page.png"/></p> 

## Tabla de contenidos:
---

- [Configuracion variables](#badges-o-escudos)
- [importaciones](#descripción-y-contexto)


## Badges o escudos
---
En el archivo environment.py se encuentra la configuracion de variables, llaves de SENDGRID y TWILIO.
Sin estas variables no se puede realizar el envio de SMS y email.

In the environment.py file you will find the configuration of variables, SENDGRID and TWILIO keys.
Without these variables it is not possible to send SMS and email.


import os

os.environ["SENDGRID_API_KEY"]="clavegenerada en twlio"
os.environ["EMAIL_FROM"]="luis2.hernandez@ucp.edu.co"
os.environ["HASH"]="MicroServicios"
os.environ["TWILIO_ACCOUNT_SID"]="clavegenerada en twlio"
os.environ["TWILIO_AUTH_TOKEN"]="clavegenerada en twlio"
os.environ["TWILIO_PHONE_NUMBER"]="+12183927126"

### Ejemplos de badges

from flask import Flask
import os
import environment
from sendgrid import SendGridAPIClient
from sendgrid.helpers.mail import Mail
from flask import request
from twilio.rest import Client


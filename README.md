# Pruebas para el parámetro firstName al crear un/a usuario/a en []
Este proyecto evalúa el comportamiento del parámetro `firstName` al crear un/a usuario/a en [nombre de la aplicación o servicio]. Las pruebas están diseñadas para asegurar que se manejen correctamente los valores de este parámetro según los requerimientos definidos.

## Requisitos

Para ejecutar las pruebas, necesitarás tener instalados los siguientes paquetes:

- pytest– Framework para ejecutar las pruebas.
- requests – Para realizar solicitudes HTTP, en caso de que sea necesario interactuar con una API o servicio web durante las pruebas.

Puedes instalar estos paquetes utilizando pip:

pip install pytest requests

## Estructura de archivos
- En el archivo configuration.py se encuentran los endpoints a usar
- En el archivo sender_stand_request.py se encuentran funciones genericas 
  a utilizar desde el archivo principal de pruebas create_user.test.py
- El archivo create_user_py contiene todas las pruebas positivas y negativas
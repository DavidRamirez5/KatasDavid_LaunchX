# Kata 02


# f# Creación del entorno virtual
Para esta segunda kata se creo un entorno virtual en Documentos por medio de la terminal de Git Bash mendiante el comando ``python -m venv env``

Una vez puesto el comando podemos ejecutar ``ls``  para comprobar la creación del entorno y como se puede ver en la siguente imagen tenemos un folder llamado "env" al cual accedemos y podemos ver que el entorno virutal fue creado exitosamente.

-> Insertar Imagen 01.

## Activar Entorno Virtual
Una vez creado el entorno virtual se debe activar para mi caso utilize siguente comando ``source env\Scripts\activate `` y una vez ejecutado al final de la linea aparece "(env)" lo cual indica que el entorno viertual se activo.

-> Insertar Imagen 02

## Instalación de paquetes en un entorno virtual.

Para instalar el paquete solicitado en la kata simplemente verificamos que el entorno viertual este activado y ejecutamos el siguente comando ``pip install python-dateutil `` posterirormente con ``pip freeze`` verificamos con que paquetes contamos y al ser un entorno completamente nuevo solo tenemos dos paquetes instalados.

## Desactivar entorno virtual.

Para desactivar el entorno solamente se ejecuta ``deactivate`` y se puede observar en la consola como ya no aparece (env) que era lo que nos indicaba que estaba activo el entorno.

### Viajero: David Andrés Patiño Ramírez


 










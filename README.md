
# Blog IA Pythoneers | Trabajo Final Etapa 2 Informatorio

Este es el repositorio de nuestro "Blog de noticias" sobre IA, como trabajo final del informatorio, en la etapa 2.  
Framewoks utilizados: Djando y Bootstrap.  

### Integrantes del grupo Pythoneers:  
🚀 Yrala, Fabian.  
🚀 Morinigo, Pedro.  
🚀 Fogar, Yamila.
 
## Setup:

**Clonar el repositorio**  

En una carpeta de su preferencia, mediante cmd u otra consola, clone el repositorio con el siguiente comando:

```
git clone #httpdelrepositorio
```  

**Para instalar el proyecto**  

Cree un entorno virtual y activelo:
```
crear entorno:  py -m venv venv   o   python -m venv venv
activar:        venv\Scripts\activate
```
**instalar las dependencias***
```
pip install -r requirements.txt 
```
**Crear la base de datos**

Como utilizamos MySql para la bd, hacer un archivo en la carpeta Settings llamado "local.py" y agregar lo que especificado en el archivo "base.py" respecto de la base de datos
-> líneas 76 a 92.

**Realizar las migraciones**
```
python manage.py makemigrations
python manage.py migrate
```
**Ejecutar el proyecto**
```
python manage.py runserver
```
**Agradecimientos**
```
Queremos agradecer a Lucas Rios por acompañarnos como profesor de la comisión 8 en esta etapa, por su conocimiento, didáctica y carisma, en cada clase.
Agradecer a Pablo Coletti y Adrian Cabrera, nuestros mentores, quienes desde la primer clase, tuvieron la mejor predisposición, nos brindaron su conocimiento, acompañamiento y apoyo, sin importar el dia ni la hora, siempre estuvieron.
Eternamente agradecidos✨.- Pythoneers.  

```



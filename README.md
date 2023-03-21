## Django Project en Linux
### 1- Requeridos
Debemos tener obligatoriamente instalados los siguiente programas
1. Python `sudo apt install python3`
2. pip `sudo apt install python3-pip`
3. [VS Code](https://code.visualstudio.com/sha/download?build=stable&os=linux-deb-x64)

### 2- Entorno Virtual y Django
Ahora crearemos la carpeta donde almacenaremos el entorno virtual y posterior a eso lo instalaremos ahí
1. Crear carpeta del proyecto `mkdir djangoproject`
2. Ingresamos a la carpeta del proyecto `cd djangoproject`
3. Instalar VirtualEnv `pip install virtualenv`
4. Crear el entorno virtual `virtualenv venv`
5. Activar el entorno virtual `source venv/bin/activate`
6. Instalar Django `pip install django`

### Crear el projecto
Ahora crearemos el proyecto y lo ejecutaremos en nuestro editor de código que será VS Code
1. `django-admin startproject nombre_del_proyecto .`
2. Ejecutarlo en VSCode `code .`

### Servidor Local
1. ```bash
python3 manage.py runserver
```
Si todo ha salido bien, debemos ingresar al localhost con el puerto por defecto que utiliza [127.0.0.1:8000](http://127.0.0.1:8000) o si quisieramos ocupar otro puerto distinto, ejecutaremos 
```bash 
python3 manage.py runserver 3000
```
[127.0.0.1:3000](http://127.0.0.1:3000)

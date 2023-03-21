## Django Project on Linux (Debian based distributions)
### 1- Required
We must have the following programs installed
1. Python `sudo apt install python3`
2. pip `sudo apt install python3-pip`
3. [VS Code](https://code.visualstudio.com/sha/download?build=stable&os=linux-deb-x64)

### 2- Virtual environment and Django
Now we will create the folder where we will store the virtual environment and after that we will install it there
1. We create the project folder `mkdir djangoproject`
2. We enter the project folder `cd djangoproject`
3. We install VirtualEnv `pip install virtualenv`
4. We create the virtual environment `virtualenv venv`
5. We activate the virtual environment `source venv/bin/activate`
6. We install Django `pip install django`

### 3- Creating the project
Now we will create the project and run it in our code editor which will be VS Code
1. `django-admin startproject nombre_del_proyecto .`
2. We run it with VS Code `code .`

### 4- Localhost
```bash
python3 manage.py runserver
```
If everything has gone well, we must enter the localhost with the default port it uses [127.0.0.1:8000](http://127.0.0.1:8000) or if we want to occupy a different port, we will execute
```bash 
python3 manage.py runserver 3000
```
[127.0.0.1:3000](http://127.0.0.1:3000)

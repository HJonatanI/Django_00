# Django_00
Grupos de repositorios para aprender Django

## Git log "Project Django "django_00" created"

#### Documents

1) Creación del entorno virtual, activación y creación del archivo requirements.txt.

python -m venv virtualE
source virtualE/bin/activate
pip install django
pip freeze > requirements.txt

#### Documents
* #### virtualE
* #### requerements.txt

2) Clonacion del repositorio Django_00 desde Github.

git clone https://github.com/usuario/Django_00.git

#### Documents
* #### virtualE
* #### requerements.txt
* #### Django_00

3) Instalación de Django, actualización de requirements.txt y creación del projecto django_00.

pip install django
pip freeze > requirements.txt
django-admin startproject django_00
python manage.py runserver 

### Documents
* #### virtualE
* #### requerements.txt
* #### Django_00
	* ##### django_00 
	* ##### manage.py
	* ##### .git
	* ##### README.md

4) Add, Commit y Push del repositorio local al remoto.

git add .
git commit -m "Project Django "django_00" created"
git push orign main
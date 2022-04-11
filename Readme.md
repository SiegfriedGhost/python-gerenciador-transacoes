#Instalar VENV - Ambiente Virtual 
python -m venv ./venv

#Ativar VENV
source /c/Users/leano/Projetos/teste/python/projeto/venv/Scripts/activate

#Instalando DJANDO
pip install Django==4.0.3

#Iniciando um Projeto 
django-admin startproject {nome_projeto} . 

#Rodando Servidor
python manage.py help

python manage.py runserver

No VsCode Ctrl+shift+P = python select interpreter (Selecionar o que está na VENV) > Abrir outro terminal 

#Inciando um Aplicativo
python manage.py startapp {nome_app}
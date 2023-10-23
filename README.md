# DjangoAllauth
This is an app that applies Django-allauth for authentication and Digital Ocean as the 3rd party authentication provider.
https://i.imgur.com/5lr0ipq.png



How To Authenticate Django Apps using django-allauth:

https://www.digitalocean.com/community/tutorials/how-to-authenticate-django-apps-using-django-allauth

Uses pipenv for virtual environment:

Create a virtual environment using Pipenv, a packaging tool for Python. First, install pipenv:

	pip3 install pipenv 

Next, activate the virtual environment:

	pipenv shell 

Next, install the dependencies you’ll use for development (django and django-allauth) using pipenv:

	pipenv install django
	pipenv install django-allauth


Run:
python manage.py runserver

The login/logout button links do not appear, but can enter:

http://127.0.0.1:8000/accounts/login/

http://127.0.0.1:8000/accounts/logout/

Can use DigitalOcean to login, or sign-up, DjAuth_user_steve


Note:
The command (pipenv shell) causes a problem with the bash shell config that Udacity installed:

bash: git_ps1: command not found

https://stackoverflow.com/questions/12870928/mac-bash-git-ps1-command-not-found

Try sourcing the Udacity config:

source ~/.udacity-terminal-config/git-prompt.sh

Copy this file to somewhere (e.g. ~/.git-prompt.sh).
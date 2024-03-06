# login-with-django

##Feature

Log in
via username & password
via email & password
via email or username & password
with a remember me checkbox (optional)
Create an account
Log out
Profile activation via email
Reset password
Remind a username
Resend an activation code
Change password
Change email
Change profile
Multilingual: English, French, Russian, Simplified Chinese and Spanish

##Installing
'''git clone https://github.com/egorsmkv/simple-django-login-and-register'''
'''cd simple-django-login-and-register'''

###Install dependencies & activate virtualenv
#Create a virtualenv using conda (optional)
conda create -n simple-django-login-and-register python=3.11

conda activate simple-django-login-and-register
#Install dependencies
pip install poetry

poetry install
poetry shell
##Apply migrations
python source/manage.py migrate
##Running
#A development server
Just run this command:

python source/manage.py runserver



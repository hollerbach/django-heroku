# erpweb

Installing Python 3.11 using PPA

```sudo add-apt-repository ppa:deadsnakes/ppa```

Then you can install Python 3.11 using the apt-get package manager

```sudo apt install python3.11```


python -m pip install Django

git clone https://github.com/django/django.git


##venv

venv for python version > 3.3

python3.11 -m venv venv


venv for older python version

pip install -U 'virtualenv<20.0'

virtualenv TE-Erp --python=python2.7


pip freeze > requirements.txt
pip install -r requirements.txt
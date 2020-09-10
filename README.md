Django chat with channels
=========================

Implementation of tutorial example from :
<a href="https://channels.readthedocs.io/en/latest/tutorial/part_1.html">Django channels tutorial</a>

Instalation
===========
'''
virtualenv env
source env/bin/activate
pip install -r requirements.txt

You also need to install Docker.
On Fedora:
dnf config-manager --add-repo=https://download.docker.com/linux/fedora/docker-ce.repo
dnf install docker-ce

and launch:

service docker start  (systemctl enable docker)
docker run -p 6379:6379 -d redis:5

python manage.py runserver 0:8000
'''



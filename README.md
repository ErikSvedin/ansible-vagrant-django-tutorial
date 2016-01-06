# ansible-vagrant-django-tutorial
sample repo to go with my tutorial on how to use ansible together with vagrant and django.

Link to the tutorial:
http://tech.willandskill.se/w-s-devops-part-1-5-introducing-ansible-and-vagrant/

### Basic getting started:

Make sure you have vagrant and ansible installed.<br>
`$ vagrant up` <br>
`$ ansible-playbook provision/deploy_django.yml`<br>
<br>
`$ vagrant ssh`<br>
Inside the vagrant machine start django project:<br>
`@vagrant...$ cd /home/django`<br>
`@vagrant...$ source env/bin/activate`<br>
`@vagrant...$ python project/manage.py runserver 0.0.0.0:8000`<br>
<br><br>
From the host go to 127.0.0.1:8000 and enjoy!

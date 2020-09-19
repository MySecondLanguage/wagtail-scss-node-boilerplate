# Wagtail SASS/LESS and Node module boiler plate

```
This simple project is just initial setup.

This project for those:

- Who want to use wagtail as backend
- Who want to use SCSS with wagtail
- Who want to use install all frotned depedency with npm
```



> This project is only initial setup for wagtail, scss, nodejs, and postgresql. this project not covered any business logic.


### A very few quick step to run this project

```
$ yarn
or 
$ npm i

$ pip install -r requirements.txt

```

and then setup `.env` file. please follow `backupenv` It's added to show you example how you can write the `.env` file.

Always place the `.env` file the base directory of the project



# Deployment


## a few very usefull commands to take idea:

### for gunicorn

```
sudo gedit /etc/systemd/system/gunicorn.service
sudo systemctl start gunicorn
sudo systemctl enable gunicorn
sudo systemctl status gunicorn
```


### for nginx
```
sudo gedit /etc/nginx/sites-available/projectile.conf
sudo rm -rf /etc/nginx/sites-enabled/default
sudo ln -s /etc/nginx/sites-available/projectile.conf /etc/nginx/sites-enabled/projectile.conf
sudo nginx -t
sudo systemctl restart nginx
sudo ufw allow 'Nginx Full'
```


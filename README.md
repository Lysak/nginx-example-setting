/var/www/ => firstproject.loc
/etc/ => nginx

sudo ln -s /etc/nginx/sites-available/firstproject.loc /etc/nginx/sites-enabled/firstproject.loc
sudo ln -s /usr/share/phpmyadmin/ /var/www/firstproject.loc/html/
sudo service nginx restart
sudo service nginx reload
sudo systemctl restart nginx
sudo chmod -R 777 /var/www
sudo nano /etc/hosts (127.0.0.1     firstproject.loc)
sudo nginx -t


/var/www/
/etc/nginx/
/var/log/nginx/

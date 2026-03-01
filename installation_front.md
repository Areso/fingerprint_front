sudo ln -s /etc/nginx/sites-available/fp.areso.pro.conf /etc/nginx/sites-enabled/fp.areso.pro.conf
certbot --nginx
$ sudo certbot renew --dry-run
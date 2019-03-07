# Webserver config

## Subdomains
DNS can be done with autodrs and the actual handling will be done in /etc/nginx/sites-enabled per subdomain to the folders for the node stuff it will just proxy to the express config if the webcie wants this or we follow [bp](https://stackoverflow.com/questions/5009324/node-js-nginx-what-now) which is just an example of this

## Webservers
* nodejs
* flask
* php-cli
* static stuff with nginx

## Security
Should be handled in nginx if possible to have a distinction between "fun coding" stuff and digital "\*\*\*\*\*" stuff on [observatory](http://observatory.mozilla.org)

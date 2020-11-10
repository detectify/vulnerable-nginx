FROM nginx

COPY html/index.html /usr/share/nginx/html/index.html
COPY login/index.html /usr/share/login/index.html
COPY nginx.conf /etc/nginx/conf.d/default.conf
COPY flag.txt /usr/share/nginx/flag.txt
COPY .htpasswd /etc/nginx/.htpasswd
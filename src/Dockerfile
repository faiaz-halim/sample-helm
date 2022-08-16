FROM nginxinc/nginx-unprivileged
COPY ./app/ /usr/share/nginx/html/
USER nginx
WORKDIR /usr/share/nginx/html
CMD ["nginx", "-g", "daemon off;"]
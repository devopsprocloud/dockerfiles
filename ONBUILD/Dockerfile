FROM almalinux:9 
RUN dnf install nginx -y 
RUN rm -rf /usr/shre/nginx/html/index.html 
ONBUILD ADD index.html /usr/share/nginx/html/
CMD ["nginx", "-g", "daemon off;"]
FROM almalinux:9
RUN dnf install nginx -y 
RUN rm -rf /usr/share/nginx/html/index.html 
COPY https://raw.githubusercontent.com/daws-76s/notes/refs/heads/master/session-02.txt usr/share/nginx/html/index.html
CMD ["nginx", "-g", "daemon off;"]
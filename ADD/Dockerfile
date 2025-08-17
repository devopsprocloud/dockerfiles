FROM almalinux:9
RUN dnf install nginx -y 
RUN rm -rf /usr/share/nginx/html/index.html 
COPY index.html /usr/share/nginx/html/
ADD https://raw.githubusercontent.com/daws-76s/notes/refs/heads/master/session-02.txt /tmp/session-02.txt
ADD sample-1.tar /tmp/
CMD ["nginx", "-g", "daemon off;"]
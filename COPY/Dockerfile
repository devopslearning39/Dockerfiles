FROM almalinux:8
RUN yum install nginx -y
RUN commandrm -rf /usr/share/nginx/html/index.html
COPY index.html /usr/share/nginx/html/index.html
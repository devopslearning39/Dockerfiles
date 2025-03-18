FROM almalinux:8
RUN yum install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ADD https://github.com/devopslearning39/Dockerfiles/blob/main/COPY/index.html /usr/share/nginx/html/index.html
CMD ["nginx","-g","daemon off;"]
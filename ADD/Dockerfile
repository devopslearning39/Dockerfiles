FROM almalinux:8
RUN yum install nginx -y
ADD https://github.com/devopslearning39/Dockerfiles/blob/main/COPY/index.html /tmp/
CMD ["nginx","-g","daemon off;"]
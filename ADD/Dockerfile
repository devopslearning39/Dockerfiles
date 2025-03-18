FROM almalinux:8
RUN yum install nginx -y
ADD https://github.com/devopslearning39/Dockerfiles/blob/main/COPY/index.html /tmp/index.txt
CMD ["nginx","-g","daemon off;"]
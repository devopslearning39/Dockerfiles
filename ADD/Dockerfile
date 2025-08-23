FROM almalinux:8
RUN yum install nginx -y
ADD https://raw.githubusercontent.com/devopslearning39/Dockerfiles/refs/heads/main/jella.txt /tmp
CMD ["nginx","-g","daemon off;"]
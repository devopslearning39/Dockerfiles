FROM almalinux:8
RUN yum install nginx -y
ADD https://github.com/devopslearning39/Dockerfiles/tree/main/jella.txt /tmp
RUN echo "we are testing ADD instruction"
CMD ["nginx", "-g", "daemon off;"]
ARG version
FROM almalinux:${version}
ARG username
RUN adduser ${username}
USER ${username}
ARG course
ARG cloud
RUN echo "technology is: ${course} with ${cloud}"
ENV course=${course}
ENV cloud=${cloud}
CMD ["sleep","100"]


# below command need to use to build the image
# docker build -t arg:v1 --build-arg version=8 --build-arg username=praveen --build-arg course=DevOps --build-arg cloud=AWS .

# below command need to use to run the imgae
# docker run -d arg:v1
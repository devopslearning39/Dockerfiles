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
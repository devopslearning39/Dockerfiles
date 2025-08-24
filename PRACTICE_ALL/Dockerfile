FROM almalinux:8
RUN echo present workdir is
CMD ["pwd"]
RUN echo "This is from root folder" > root.txt
WORKDIR /tmp
CMD ["pwd"]
RUN echo "This is from tmp folder" > temppp.txt

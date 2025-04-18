FROM vidyakarnakanti/ping-image:v1

RUN apt update && \
    apt install -y nginx && \
    echo "Hello Praveen"

CMD ["nginx", "-g", "daemon off;"]

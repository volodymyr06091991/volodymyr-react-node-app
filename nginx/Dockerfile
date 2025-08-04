FROM ubuntu:22.04

RUN apt update && apt install -y nginx curl

RUN echo '<h1>Volodymyr Tykhokhid</h1>' > /var/www/html/index.html

EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]

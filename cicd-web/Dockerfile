FROM nginx:stable-alpine
LABEL maintainer="NGINX ECS container <mjcpro@mjc.ac.kr>"

COPY index.html /usr/share/nginx/html/index.html

EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]

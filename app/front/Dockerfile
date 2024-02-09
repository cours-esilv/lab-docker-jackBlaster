FROM nginx:alpine

WORKDIR /usr/share/nginx/html

COPY . .

ENV WS_BACK_URL http://localhost:8080

EXPOSE 80

ENTRYPOINT ["nginx", "-g", "daemon off;"]

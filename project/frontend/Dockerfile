FROM nginx:stable-alpine

RUN addgroup -S roboshop && adduser -S roboshop -G roboshop

RUN rm -rf /usr/share/nginx/html/*

COPY . /usr/share/nginx/html

EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]
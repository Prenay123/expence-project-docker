FROM nginx:stable-alpine
RUN addgroup -s roboshop && adduser -s roboshop -G roboshop
RUN rm -rf /usr/share/nginx/html/*
COPY . /usr/share/nginx/html
EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]

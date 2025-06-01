FROM node:18-alpine

WORKDIR /app

RUN npm install -g http-server

COPY simple_todo_app.html ./index.html

EXPOSE 5500

CMD ["http-server", "-p", "5500", "--cors", "-o"]
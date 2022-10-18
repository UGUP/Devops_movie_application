FROM node:10


WORKDIR  /app
RUN apt-get update
COPY ./package.json .
RUN npm install


COPY . .
EXPOSE 3000
CMD ["node","index.js"]


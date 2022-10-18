FROM node:10
WORKDIR /app
COPY ./package.json .
RUN apt-get update
RUN npm  install 
COPY . .
EXPOSE 8000
CMD ["npm","start"]

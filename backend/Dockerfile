FROM node:20
EXPOSE 8080
RUN mkdir /opt/server
WORKDIR /opt/server
COPY *.js .
COPY *.json .
RUN npm install
COPY ["node","index.js"]

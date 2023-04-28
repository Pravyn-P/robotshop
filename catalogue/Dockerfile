FROM node:14
EXPOSE 8080
WORKDIR /opt/server
COPY package.json /opt/server/

RUN npm install  
# npm install is used to install the packages and dependencies for nodejs project

COPY server.js /opt/server/
ENTRYPOINT ["node","server.js"]
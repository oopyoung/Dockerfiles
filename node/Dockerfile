FROM node:4-onbuild

RUN npm install -g cnpm gulp bower && npm cache clear

WORKDIR /opt
EXPOSE 8001
VOLUME ["/opt"]

# CMD node /opt/htdocs/broadcast/app.js 8001

FROM localhost:5000/nodejs

WORKDIR /var/apps/dockerbot

ADD package.json package.json
RUN npm install

ADD bin bin
ADD hubot-scripts.json hubot-scripts.json
ADD external-scripts.json external-scripts.json
ADD scripts scripts


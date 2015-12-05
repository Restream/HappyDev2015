FROM registry.default.kube.cluster.local/node:latest

ADD . /app
WORKDIR /app

RUN npm install

EXPOSE 8000

CMD npm start

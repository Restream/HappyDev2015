FROM registry.default.kube.cluster.local/php5

ADD . /

WORKDIR /
RUN tar -xzvf latest.tar.gz

WORKDIR /wordpress

EXPOSE 8000

CMD php -S 0.0.0.0:8000 -t /wordpress

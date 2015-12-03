FROM registry.default.kube.cluster.local/ruby:2.2.0

ADD . /app
WORKDIR /app

RUN bundle install -j4

EXPOSE 4567

CMD bundle exec ruby app.rb

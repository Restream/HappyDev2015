FROM registry.default.kube.cluster.local/ruby:2.2.0

ADD . /app
WORKDIR /app

RUN bundle install -j4

EXPOSE 8000

CMD bundle exec ruby app.rb

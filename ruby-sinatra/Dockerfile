FROM registry.default.kube.cluster.local/ruby-happydev

ADD . /app
WORKDIR /app

RUN bundle install -j4

EXPOSE 8000

CMD bundle exec ruby app.rb

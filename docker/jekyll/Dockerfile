FROM ruby:3.3

WORKDIR /app

ENV BUNDLE_PATH=/bundle

COPY \
  Gemfile \
  Gemfile.lock \
  /app/
RUN bundle install --jobs=4

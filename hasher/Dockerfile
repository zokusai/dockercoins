FROM ruby:alpine
WORKDIR /app

RUN gem install sinatra
RUN gem install thin
COPY hasher.rb .

ENTRYPOINT ["ruby"]
CMD ["hasher.rb"]
EXPOSE 8080

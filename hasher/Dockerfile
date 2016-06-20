FROM ruby:alpine
RUN apk add --update build-base
RUN gem install sinatra
RUN gem install thin -v 0.7.1
ADD hasher.rb /
CMD ["ruby", "hasher.rb"]
EXPOSE 80

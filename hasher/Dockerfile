FROM ruby:alpine
RUN apk add --update build-base
RUN gem install sinatra -v 1.4.5
RUN gem install thin
ADD hasher.rb /
CMD ["ruby", "hasher.rb"]
EXPOSE 80

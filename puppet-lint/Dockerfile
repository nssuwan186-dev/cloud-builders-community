FROM ruby:4.0.1-trixie
LABEL MAINTAINER marcin.niemira@gmail.com

RUN gem install puppet-lint

ENTRYPOINT ["puppet-lint"]

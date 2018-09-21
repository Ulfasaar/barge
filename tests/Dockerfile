FROM ubuntu:latest

RUN apt-get update -qq && apt-get install -qy \
    ca-certificates \
    bzip2 \
    curl \
    libfontconfig \
    --no-install-recommends
ADD . /test
WORKDIR /test
CMD ["/test/tests.sh"]


FROM debian:sid
MAINTAINER Zero Cho "http://itsze.ro"

ADD install.sh /usr/local/bin/install
RUN /usr/local/bin/install
ADD run.sh /usr/local/bin/run
ENTRYPOINT ["/usr/local/bin/run"]

EXPOSE 9160 7000 7001 9042 7199

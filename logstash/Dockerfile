FROM docker.elastic.co/logstash/logstash:7.12.1

USER root

COPY ./config/logstash.yml /usr/share/logstash/config/logstash.yml

RUN rm -f /usr/share/logstash/pipeline/logstash.conf

ADD pipeline/ /usr/share/logstash/pipeline/
ADD config/ /usr/share/logstash/config/

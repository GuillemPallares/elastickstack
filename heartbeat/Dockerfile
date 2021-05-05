
FROM docker.elastic.co/beats/heartbeat:7.12.1
COPY heartbeat.yml /usr/share/heartbeat/heartbeat.yml
USER root
RUN chown root /usr/share/heartbeat/heartbeat.yml
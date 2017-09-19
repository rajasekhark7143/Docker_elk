FROM docker.elastic.co/logstash/logstash:5.3.1
MAINTAINER ramtruely6@gmail.com
RUN rm -f /usr/share/logstash/pipeline/logstash.conf
ADD config/logstash.yml /usr/share/logstash/config/
EXPOSE 9600

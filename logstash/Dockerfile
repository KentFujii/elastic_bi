FROM docker.elastic.co/logstash/logstash:6.2.4
ADD config/ /usr/share/logstash/config/
ADD pipeline/ /usr/share/logstash/pipeline/
ADD twitter.csv /tmp/logs/
WORKDIR /usr/share/logstash

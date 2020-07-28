FROM elasticsearch:7.8.1
FROM kibana:7.8.1
FROM logstash:7.8.1

ADD ./config/logstash.conf /etc/conf/logstash.conf
COPY ./config/elasticsearch.yml /etc/conf/elasticsearch.yml
COPY ./config/kibana.yml /etc/conf/kibana.yml
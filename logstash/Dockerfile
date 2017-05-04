#FROM docker.elastic.co/logstash/logstash:5.3.1
FROM logstash:5.3.1

COPY conf/logstash.conf /usr/share/logstash/pipeline/logstash.conf
#COPY conf/logstash.yml /usr/share/logstash/config

RUN logstash-plugin install logstash-filter-de_dot

CMD ["-f", "/usr/share/logstash/pipeline/logstash.conf"]

EXPOSE 5050:5050
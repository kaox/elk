#FROM docker.elastic.co/elasticsearch/elasticsearch:5.3.1
FROM elasticsearch:5.4.0
LABEL maintainer "andresgarcia.kaox@gmail.com"

COPY conf/elasticsearch.yml /usr/share/elasticsearch/config/elasticsearch.yml

# Add your elasticsearch plugins setup here
# Example: RUN elasticsearch-plugin install shield

EXPOSE 9200:9200
EXPOSE 9300:9300
ARG ELK_VERSION

# https://www.docker.elastic.co/
FROM docker.elastic.co/logstash/logstash:${ELK_VERSION}

RUN logstash-plugin install logstash-input-beats
RUN logstash-plugin install logstash-filter-json

# Add your logstash plugins setup here
# Example: RUN logstash-plugin install logstash-filter-json

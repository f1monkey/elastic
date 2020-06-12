ARG ELK_VERSION
FROM logstash:${ELK_VERSION}

RUN logstash-plugin install logstash-input-http \
    && logstash-plugin install logstash-codec-json \
    && logstash-plugin install logstash-output-elasticsearch

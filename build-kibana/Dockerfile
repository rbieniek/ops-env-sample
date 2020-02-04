FROM docker.elastic.co/kibana/kibana:7.5.2

ENV XPACK_LICENSE_MANAGEMENT_ENABLED="false"
ENV XPACK_ML_ENABLED="false"

RUN /usr/local/bin/kibana-docker --optimize

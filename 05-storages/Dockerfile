FROM fluent/fluentd:v1.12-debian
USER root
COPY fluentds.conf /fluentd/etc/fluent.conf
RUN gem install fluent-plugin-cloudwatch-logs
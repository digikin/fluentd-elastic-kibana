FROM fluent/fluentd:v1.11-debian-1
USER root
RUN ["gem", "install", "fluent-plugin-elasticsearch", "--no-document", "--version", "4.3.1"]
USER fluent
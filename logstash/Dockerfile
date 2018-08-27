ARG LOGSTASH_VERSION

FROM docker.elastic.co/logstash/logstash:${LOGSTASH_VERSION}

ADD logstash.yml /usr/share/config/logstash.yml
ADD jdbc/mysql-connector-java-5.1.36-bin.jar /usr/share/logstash/mysql-connector-java-5.1.36-bin.jar
ADD jdbc/pipeline.conf /usr/share/logstash/pipeline/logstash.conf

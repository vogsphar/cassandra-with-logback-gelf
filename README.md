# cassandra-with-logback-gelf
dockerfile for cassandra:3 with logback-driver
with cassandra:3 as baseimage it will add a jar to the cassandra classpath to enable logging to graylog
see https://github.com/osiegmar/logback-gelf for the original gelf logger repository
forked to https://github.com/vogsphar/logback-gelf for the jar  

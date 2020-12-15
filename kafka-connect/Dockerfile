FROM confluentinc/cp-kafka-connect-base:6.0.0

RUN confluent-hub install --no-prompt \
    --component-dir /usr/share/java \
    confluentinc/kafka-connect-elasticsearch:latest && \
    confluent-hub install --no-prompt \
    --component-dir /usr/share/java \
    hpgrahsl/kafka-connect-mongodb:1.4.0 && \
    confluent-hub install --no-prompt \
    --component-dir /usr/share/java \
    confluentinc/kafka-connect-jdbc:latest && \
    confluent-hub install --no-prompt \
    --component-dir /usr/share/java \
    confluentinc/kafka-connect-http:latest
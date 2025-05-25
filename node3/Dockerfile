FROM confluentinc/cp-kafka:7.9.0

RUN mkdir -p /etc/kafka/kraft

COPY server.properties /etc/kafka/kraft/server.properties

CMD ["bash", "-c", "kafka-server-start /etc/kafka/kraft/server.properties"]

# runkafka

This repo contains an example of how to run and test kafka-go

## Installing Kafka

Follow these instructions to run kafka:
https://kafka.apache.org/quickstart

## Running

Then run the producer and consumer:
`go run writer/main.go`
`go run reader/main.go`


You can read messages on the command line for debugging/investigating using kafkacat
e.g.
`
kafkacat -b localhost:9092 -t my-topic
`
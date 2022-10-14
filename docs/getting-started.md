# Getting Started

## Scaffold A New App

Scaffolding a new app will create a fully functional Go project with all you need to get started quickly!

`torque new HospitalRegistrationApp`

If you'd like to have a minimal app install with only specific services, you can specify flags to get a finely tuned experience that's as minimal as you need to get going with the services you want.

### NATS.io

A service that has no HTTP related functionality, it's set up for producing and consuming messages using [nats.io](https://nats.io) and [dynamodb](https://docs.aws.amazon.com/sdk-for-go/api/service/dynamodb/)

`torque new RecordProcessor --nats --dynamo`

### Redis

A service that has no HTTP related functionality, it's set up for producing and consuming messages using [redis pub sub](https://redis.uptrace.dev/guide/go-redis-pubsub.html)

`torque new RecordProcessor --redis`

### Possible Switches

```sh
--nats
--redis
--postgres
--mysql
--dynamo
--mongo
```

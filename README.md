# my-redis

`my-redis` is an incomplete, idiomatic implementation of a [Redis](https://redis.io) client and server built with
[Tokio](https://tokio.rs).

**Disclaimer** Please don't use mini-redis in production. This project is
intended to be a learning resource, and omits various parts of the Redis
protocol because implementing them would not introduce any new concepts. We will
not add new features because you need them in your project — use one of the
fully featured alternatives instead.

## Why Redis

The primary goal of this project is learning Tokio. Doing this requires a
project with a wide range of features with a focus on implementation simplicity.
Redis, an in-memory database, provides a wide range of features and uses a
simple wire protocol. The wide range of features allows demonstrating many Tokio
patterns in a "real world" context.

The Redis wire protocol documentation can be found [here](https://redis.io/topics/protocol).

The set of commands Redis provides can be found
[here](https://redis.io/commands).

## Running

TBD

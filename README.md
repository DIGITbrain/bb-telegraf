# General

## Deployment type

Docker

## Image

Based on official image on Docker Hub: https://hub.docker.com/_/telegraf

## Licence

The MIT License

## Version

1.19

## Description

> Telegraf is an agent for collecting, processing, aggregating, and writing metrics.
>
> Design goals are to have a minimal memory footprint with a plugin system so that developers in the community can easily add support for collecting metrics." [1]

This repository contains an example configuration for reading from an MQTT broker and writing the read data to Kafka. See the configuration file `telegraf/telegraf-example-consenses.conf` for more details.

# References

[1] https://github.com/influxdata/telegraf
# Ingestion

You can ingest Logs/Metrics using one of the below tools or something similar. Check sample configuration on how to use these tools by following the links.

1. [Vector](vector)
1. [Fluent-bit](fluent-bit)
1. [Fluentd](fluentd)
1. [Amazon Kinesis Firehose](kinesis_firehose)


Logs can also be ingested into Zinc Cloud / ZincObserve through one of the 3 HTTP APIs.

1. [_json](/ZincObserve/api/ingestion/json)
1. [_multi](/ZincObserve/api/ingestion/multi)
1. [_bulk](/ZincObserve/api/ingestion/bulk)

You can call the above APIs directly in your code to ingest data. 

Here are 2 examples on how you can do it programmatically:

1. [Go](go)
1. [Python](python)

You can also use curl command to ingest logs:

1. [curl](curl)

To ingest metrics data you will need to use the prometheus remote write endpoint.

1. [Prometheus remote write](prometheus_metrics)
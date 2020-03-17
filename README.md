# Amazon SQS Messaging Provider

This library is a [waSCC](https://wascc.dev/) _native capability provider_ that interacts with [Amazon SQS](https://aws.amazon.com/sqs/) to implement the [`wascap:messaging`](https://github.com/wascc/wascc-codec) protocol.

## Build

To build a binary suitable for running on Amazon Linux using a [builder image](https://hub.docker.com/repository/docker/ewbankkit/rust-amazonlinux):

```console
$ make release
```

# Twitter Integration

## Overview

This is an integration for use with the
[Cangaroo](https://github.com/nebulab/cangaroo) open source project.

## Connection Parameters

The following `parameters` must be setup into your
[Cangaroo](https://github.com/nebulab/cangaroo) Job:

| Name | Value |
| :----| :-----|
| consumer_key | Twitter Consumer Key (required) |
| consumer_secret | Twitter Consumer Secret (required) |
| access_token | Twitter Access Token (required) |
| access_token_secret | Twitter Access Token Secret (required) |

## Webhooks

The following webhooks are implemented:

| Name | Description |
| :----| :-----------|
| /send_tweet | Send the given tweet to twitter |

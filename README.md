# QA Bot


## Motivation

The `QA Bot` aims to bridge the gap between the current triage bot was limited in scope to not being able to add more people to serve both developers and non-developers a means to view and interact directly with QA tickets.

## Features

The features list is a single Node application utilizing the Slack SDK in order to process requests.

### Backend Services & Processes

- Slack Messaging API to receive send/receive requests in the QA channel

## High Level Design

The Slack bot consists of two major components:
- `Slash command services` (Node application)
- `Interactive messages for sales and technical escapations` (backend calls to Front to create ticketing flow)


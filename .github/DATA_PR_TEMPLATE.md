---
title: New data candidate logged
assignees: ijdoc
labels: data
---
{{ payload.sender.login }} just logged a new data candidate.

Tools
{{ tools.context.payload }}

Context
{{ context.payload }}

Payload
{{ payload }}

Event Payload
{{ github.event.client_payload }}

Event Payload Item
{{ github.event.client_payload.artifact_collection_name }}
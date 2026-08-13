---
layout: page
title: Projects
permalink: /projects/
---

## Live Translation Platform

*TypeScript, Azure, WebSockets, Terraform · 2025–Present*

- Built a multi-tenant, room-scoped English-to-Persian live translation platform using Azure Speech recognition, Azure Translator, neural text-to-speech, and low-latency WebSocket audio and caption streaming.
- Implemented stable sentence-boundary detection over revisable partial ASR results, monotonic commit cursors, terminology overrides, Persian normalization, and de-duplicated per-room TTS queues.
- Added subdomain-based tenant isolation, transcript persistence in Cosmos DB, Stripe subscription management, progressive web app support, and publisher, listener, and billing experiences.
- Developed a Claude-based topic segmentation and summarization pipeline on a dedicated branch, using sliding-window topic-change detection, confidence thresholds, short-topic batching, Persian summary generation, Cosmos DB persistence, and real-time WebSocket delivery.
- Provisioned Azure Container Apps, Container Registry, Speech, Translator, Cosmos DB, Log Analytics, and wildcard DNS using Terraform and automated deployments with GitHub Actions.

## [OBD-II Diagnostic Reader](https://github.com/arashn/obdii-reader)

*C, ATmega32, Embedded Systems · 2015–2022*

- Extended an undergraduate embedded-systems prototype into a documented open-source automotive diagnostic reader, refining the hardware and C firmware after the course; implemented ISO 9141-2 communication and displayed speed, RPM, engine load, and coolant temperature through an LCD and keypad interface.
- Published schematics, source code, build instructions, and usage documentation; attracted 18 GitHub stars and 5 forks from independent users and contributors.

## Open-Source Contributions

*Kubernetes, Helm, Java, Spark*

- Contributed Helm deployment documentation and template fixes for a WhatsApp proxy on EKS and GKE, and corrected example integration code for the Spark Cassandra connector.

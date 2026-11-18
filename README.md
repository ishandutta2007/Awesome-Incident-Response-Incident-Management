# Awesome-Incident-Response-Incident-Management

# Awesome-Incident-Response-Incident-Management

## Top Inbound & Outbound Webhook Management Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Webhook Delivery, Ingestion, Retries, Rate Limiting, Inspection & Event Routing*  

**Last updated: November 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Inbound & Outbound Webhook Management**. These tools handle reliable webhook delivery, exponential backoff retries, signature verification, payload transformation, rate limiting, dead-letter queues, and real-time traffic inspection.



**Examples** include Postman Webhooks, Svix, Hookdeck, Convoy, Webhook.site, RequestBin, Zapier Webhooks, Make Webhooks, Courier Webhooks, and Pipedream (the category leaders). 



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, high-throughput event gateways, and local webhook tunneling — ideal for backend engineers, API developers, and platform teams building resilient event-driven architectures.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saashosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Svix](https://svix.com)**  

  Enterprise-grade webhooks-as-a-service platform providing outbound delivery, automatic retries, signature verification, and customer-facing portals.



- **[Hookdeck](https://hookdeck.com)**  

  Event gateway and webhook infrastructure platform for reliable inbound ingestion, queuing, rate limiting, and dead-letter recovery.



- **[Convoy (Cloud)](https://getconvoy.io)**  

  High-throughput bidirectional webhook gateway supporting both inbound event ingestion and outbound customer webhook delivery.



- **[Pipedream](https://pipedream.com)**  

  Developer-first integration platform offering instant webhook endpoints, serverless event workflows, and built-in payload inspection.



- **[Webhook.site](https://webhook.site)**  

  Instant online tool for inspecting, testing, transforming, and automating incoming HTTP requests and webhook payloads.



- **[RequestBin (by Pipedream)](https://pipedream.comrequestbin)**  

  Cloud-hosted HTTP request collector for capturing, debugging, and analyzing webhook events in real time.



- **[Postman Webhooks](https://postman.com)**  

  API platform capabilities allowing developers to trigger collections, monitor endpoints, and debug incoming webhook payloads.



- **[Zapier Webhooks](https://zapier.com)**  

  No-code automation connector enabling custom inbound catch hooks and outbound HTTP POST/GET requests across thousands of apps.



- **[Make Webhooks](https://make.com)**  

  Visual workflow automation module providing instant custom webhook triggers and scheduled HTTP data routing.



- **[Courier Webhooks](https://courier.com)**  

  Notification infrastructure platform supporting outbound webhook delivery channels alongside multi-channel user messaging.



## Open-Source GitHub Projects



- **[Convoy](https://github.com)**  

  Cloud-native, open-source webhooks gateway built in Go for managing millions of inbound and outbound webhooks with retries, rate limiting, and static IPs.



- **[Svix Open Source](https://github.com)**  

  Open-source core of the Svix webhook delivery service written in Rust, offering reliable dispatching, cryptographic signing, and retry schedules.



- **[Webhook (adnanh)](https://github.com)**  

  Lightweight configurable incoming webhook server written in Go that executes shell commands and passes HTTP payload data as parameters.



- **[Webhook.site (Open Source)](https://github.com)**  

  Self-hostable version of Webhook.site for inspecting, testing, and debugging incoming HTTP requests and custom scripts.



- **[Hook0](https://github.com)**  

  Open-source webhooks-as-a-service platform built in Rust enabling SaaS applications to emit secure, verifiable events to users.



- **[Outpost (by Hookdeck)](https://github.com)**  

  Open-source outbound webhook and event destination infrastructure for sending events to user-configured endpoints and message brokers.



- **[Smee.io](https://github.com)**  

  Webhook payload delivery service that receives events from external sources and forwards them securely to local development environments.



- **[Relay Webhook / Webhook Relay](https://github.com)**  

  Open-source CLI and forwarding utilities for receiving public webhooks on localhost or private networks without opening firewall ports.



- **[n8n](https://github.com)**  

  Fair-code/open-source workflow automation tool featuring powerful webhook trigger and HTTP request nodes for complex event routing.



- **[Activepieces](https://github.com)**  

  Open-source no-code/low-code automation platform with built-in webhook triggers and outbound HTTP actions.



- **[Windmill](https://github.com)**  

  Open-source developer platform turning Python, TypeScript, Go, and Bash scripts into instant auto-generated webhook endpoints.



- **[Pipedream Open-Source Components](https://github.com)**  

  Extensive open-source registry of event sources, webhook triggers, and serverless actions for building custom event pipelines.



- **[Standard Webhooks](https://github.com)**  

  Open-source specification and multi-language SDKs (Go, Rust, Python, JS, Java, Ruby) for standardized webhook signing and verification.



- **[Kourier / Knative Eventing](https://github.com)**  

  Kubernetes-native event-driven architecture framework providing CloudEvents routing, broker-trigger delivery, and retry policies.



- **[Argo Events](https://github.com)**  

  Event-driven workflow automation framework for Kubernetes supporting webhooks, message queues, and cloud event sources.



- **[ngrok (Open-Source v1 / Alternatives like Bore & FRP)](https://github.com)**  

  Fast reverse proxy tools enabling developers to expose local webhook receivers to the public internet during testing.



- **[Benthos / Redpanda Connect](https://github.com)**  

  High-performance stream processor capable of ingesting HTTP webhooks, transforming payloads, and fanning out to queues or endpoints.



- **[Vector](https://github.com)**  

  High-performance observability and event router supporting HTTP webhook ingestion, buffering, transformation, and reliable delivery.



- **[Soketi / Pusher-Compatible Event Servers](https://github.com)**  

  Fast, resilient open-source WebSocket and HTTP webhook event server built on uWebSockets.js.



- **[Beeceptor / Mockoon](https://github.com)**  

  Open-source API mocking and webhook inspection tool for simulating endpoints, logging incoming requests, and testing responses.



### Additional Strong Open-Source Options



- **[Standard Webhooks Signature Libraries](https://github.com/tree/main/libraries)** for HMAC-SHA256 signing, timestamp validation, and replay-attack prevention.

- **[CloudEvents SDKs](https://github.com)** for vendor-neutral event payload formatting across HTTP and message brokers.

- **[Local Tunneling Tools (bore, localtunnel, cloudflared)](https://github.com)** for routing live external webhooks directly to local dev servers.

- **[Dead-Letter Queue & Retry Workers](https://github.com)** built on Redis, BullMQ, RabbitMQ, or Temporal for durable delivery.

- Many community **Terraform modules** and **Helm charts** for deploying scalable webhook gateways on Kubernetes.



**Frameworks for building custom systems**: Combine **Convoy** or **Hook0** with **Redis / Kafka**, **Standard Webhooks SDKs**, and **Prometheus + Grafana** alongside **n8n** for resilient, observable webhook infrastructure.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Webhook infrastructure must implement proper security controls (HMAC signature verification, timestamp checks, IP allowlisting, TLS).

- Self-hosted open-source solutions require proper queue persistence, rate limiting, and dead-letter monitoring in production.



---



**Made for backend engineers, API developers, platform teams, and integration architects.**  

Let's make inbound and outbound webhook management more reliable, observable, and open.

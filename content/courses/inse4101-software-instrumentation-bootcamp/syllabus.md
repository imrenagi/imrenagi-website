---
author: "Imre Nagi"
title: "Syllabus"
description: "Find the list of topics for the bootcamp here"
tags: ["bootcamp", "software-instrumentation"]
date: 2024-02-10T01:00:00+07:00
thumbnail: ""
---

Here is the outline of the materials that you going to learn in this bootcamp. They will be covered in the form or write-up, lab/challenge, and a final challenge in each subtopic (e.g. logging, metrics, tracing).

### Grafana

* Introduction to Grafana
* Grafana setup

### Logging

* Introduction to logging
* Structured logging
* Log correlation
* Log output (files, stdout, etc.)
* Logging with Go and Zerolog + **[Lab/Challenges]**
* Introduction to log collector agent and Fluentbit
* Collecting logs files with Fluentbit + **[Lab/Challenges]**
* Collecting container logs with Fluentbit + **[Lab/Challenges]**
* Introduction to Grafana Loki
* Grafana Loki setup + **[Lab/Challenges]**
* Sending logs to Grafana Loki + **[Lab/Challenges]**
* Querying logs in Grafana Loki with LogQL
* **[Final Logging Challenges]**: Monitoring gRPC service and databases with logs and logs metrics

### Metrics

#### Prometheus

* Introduction to system service monitoring
* Introduction to Prometheus
* Prometheus setup + **[Lab/Challenges]**
* Prometheus metric types
* Prometheus basic query + **[Lab/Challenges]**
* Using pre-built dashboards to Grafana + **[Lab/Challenges]**
* Prometheus exporters
* Monitor container metrics + **[Lab/Challenges]**
* Instrumenting Go application with Prometheus + **[Lab/Challenges]**

#### OpenTelemetry

* Introduction to OpenTelemetry
* Collecting metrics with OpenTelemetry + **[Lab/Challenges]**
* OpenTelemetry automatic instrumentation + **[Lab/Challenges]**
* **[Final Metric Challenges]**: Monitoring gRPC service and databases with metrics

### Tracing

* Introduction to tracing
* Introduction and setting up Jaeger + **[Lab/Challenges]**
* Collecting trace with OpenTelemetry Part 1 + **[Lab/Challenges]**
* Collecting trace with OpenTelemetry Part 2 + **[Lab/Challenges]**
* Tracing context propagation + **[Lab/Challenges]**
* **[Final Tracing Challenges]**: Enabling tracing for gRPC service and databases with traces

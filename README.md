# Oscar A. Virguez

Electronic engineer · Bogotá, Colombia

I started out designing sensor boards and writing their firmware, then moved on to
networks, servers, data pipelines and AI systems. My graduate research applies deep
learning to side-channel attacks on microprocessors. I now do security research and
bug bounty; that work is at [@teravon](https://github.com/teravon).

## Scrollia

**[scrollia.org](https://scrollia.org)**: a free, ad-free library of public-domain
classics, with its own Android app. I maintain both. The site is available in 6
languages.

## Engineering

Most of this work is in private company repositories.

### Hardware and firmware

- Designed sensor nodes for environmental and water-quality monitoring.
- Wrote their firmware in C on ESP32 (ESP-IDF, FreeRTOS): a shared driver library,
  BLE diagnostics, an embedded web server and secure OTA updates.
- Built a cross-platform BLE companion app for configuring devices in the field.
- Set up a single firmware build system that produces per-site images from generic
  modules plus site configuration.
- Undergraduate capstone: designed and built a Harvard-architecture microprocessor.

### Networks and infrastructure

- Deployed a private LoRaWAN network alongside cellular and WiFi links, with MQTT
  and Node-RED at the edge.
- Ran the cloud side on AWS: time-series and relational databases, dashboards and
  alerting.
- Administered Linux servers: services, TLS, hardening and containers.

### Data

- ETL pipelines in Python handling hundreds of thousands of data points a day from
  a fleet of hundreds of devices.
- Ingestion pipelines with data-quality validation, change detection and
  schema-drift handling.
- Analytics on columnar data (DuckDB, Parquet) with layered models, dashboards and
  a data catalog.

### AI

- Speech analytics: transcription with speaker diarization and LLM-based
  classification, with deterministic guardrails against hallucination.
- LLM agents and multi-agent orchestration with LangChain, RAG over large internal
  datasets, and evaluation of AI outputs before release.

## Where

Freelance firmware and IoT work (2023), Italcol (2024–2025) and Global Hitss
(2025–2026).

## Stack

Languages: C, Python, JavaScript, Kotlin, Bash, SQL

Tools: ESP-IDF, FreeRTOS, MQTT, LoRaWAN, Linux, Docker, AWS, GCP, PostgreSQL,
InfluxDB, DuckDB, BigQuery, LangChain, scikit-learn, Keras, Jetpack Compose

## Background

B.Sc. in Electronic Engineering and graduate studies in Data Science, Escuela
Colombiana de Ingeniería Julio Garavito.

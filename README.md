# Distributed Job Queue System

A distributed backend system for asynchronous task processing built using C++, Apache Kafka, PostgreSQL, Docker, and REST APIs.

## Overview

This project aims to simulate a real-world distributed job processing architecture used by large-scale applications for handling long-running tasks asynchronously.

Users submit jobs through REST APIs, which are queued and processed by worker services. Job status and execution metadata are persisted in PostgreSQL for monitoring and tracking.

## Planned Architecture

Client
↓
REST API Service
↓
Apache Kafka
↓
Worker Services
↓
PostgreSQL

## Planned Features

* Job submission APIs
* Job status tracking
* Apache Kafka-based message queue
* Distributed worker processing
* PostgreSQL-backed persistence
* Dockerized deployment
* Retry and failure handling
* Load testing and performance benchmarking

## Technology Stack

* C++17
* Apache Kafka
* PostgreSQL
* Docker
* REST APIs
* Drogon Framework

### Current Progress

*  Project planning completed
*  REST API concepts learned
*  Backend API implementation
*  PostgreSQL integration
*  Kafka integration
*  Docker deployment
*  Performance testing

## Future Goals

* Process 10K+ asynchronous jobs during load testing
* Implement scalable worker architecture
* Add fault-tolerant job execution
* Benchmark system throughput and latency

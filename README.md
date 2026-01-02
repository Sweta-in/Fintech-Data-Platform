# Fintech-Data-Platform

A backend + data engineering system for ingesting, validating, and analyzing transactional financial data.
The platform combines **real-time REST APIs** with **batch data pipelines** for analytics and reporting.

---

## Tech Stack

**Backend**
- Java 17, Spring Boot
- Spring Data JPA (Hibernate)
- PostgreSQL
- Docker, Maven

**Data Engineering**
- Python (Pandas, NumPy)
- Parquet-based analytics outputs
- SQL-based aggregation and views
- Batch processing pipelines

---

## System Architecture

1. **API Layer**
   - Ingests transactional data via REST APIs
   - Ensures idempotency and request validation

2. **Persistence Layer**
   - ACID-compliant storage using PostgreSQL
   - Indexed tables for efficient querying

3. **Batch Data Pipelines**
   - Periodic extraction of transactional data
   - Cleaning, normalization, and aggregation
   - Generation of analytics-ready datasets

---

## Implemented Features

### Backend
- Transaction ingestion via REST APIs
- Idempotent request handling
- Layered architecture (Controller–Service–Repository)
- Dockerized local environment

### Data Engineering
- Batch ingestion of transaction records
- Data cleaning and normalization
- Daily aggregation pipelines (volume, totals)
- Parquet-based outputs for analytics

---

## Batch Pipeline Overview


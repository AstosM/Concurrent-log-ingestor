# Concurrent Security Log Ingestor & Analyzer

A high-performance log ingestion and real-time security analysis backend engine built with Go.

## Tech Stack
- **Language:** Go (Golang)
- **Framework:** Gin Web Framework
- **ORM & Database:** GORM, PostgreSQL / SQLite
- **Concurrency Model:** Goroutines, Buffered Channels, Worker Pools

## Key Features
- High-throughput asynchronous REST API for log ingestion.
- Concurrent processing pipeline utilizing Go channels to decouple ingestion from I/O storage.
- Database indexing on high-query security attributes (`ip_address`, `timestamp`).
- Real-time sliding-window security analytics for brute-force detection.

> *Source code update in progress.*                                                    

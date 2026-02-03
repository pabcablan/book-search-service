# Book Search Engine

## 🔍 Project Overview

The **Book Search Engine** is a high-performance indexing and querying system designed for large-scale text document collections, with a strong focus on **backend architecture, concurrency, distributed systems, and performance optimization**.

All book data is sourced exclusively from [**Project Gutenberg**](https://www.gutenberg.org/), providing a realistic corpus of extensive and diverse textual content.

This repository functions as a **project portfolio**, demonstrating the system's evolution through **two distinctly different architectural approaches**:

- A **modular single-node solution** emphasizing clean design and component decoupling
- A **distributed cluster solution** focused on scalability, fault tolerance, and high performance

Each architecture has its own dedicated repository with complete code and detailed documentation.

> ℹ️ **Note**  
> The linked repositories represent **different architectural implementations** of the same system,  
> not sequential versions of a monolithic application.


## 📚 Table of Contents

- [📦 Modular Architecture (Single-Node)](#-modular-architecture-single-node)
- [🌐 Distributed Cluster Architecture](#-distributed-cluster-architecture)
- [👥 Team Members](#-team-members)
- [🙏 Acknowledgments](#-acknowledgments)
- [📌 Repository Information](#-repository-information)


## 📦 Modular Architecture (Single-Node)

[![My Skills](https://go-skill-icons.vercel.app/api/icons?i=java,maven,api,mongodb,sqlite,idea,github)](https://go-skill-icons.vercel.app/api/)

### Summary

A search engine built as a collection of modular microservices running on a single node, featuring:

- Well-defined synchronous communication through REST APIs
- Optimized local persistence for indexing and querying operations
- Microservice-based architecture on a unified deployment target

### Technology Stack

- ☕ **Java** — Service implementation language
- 🔗 **REST APIs** — Inter-component communication
- 🗄️ **MongoDB** — Local inverted index storage
- 🗄️ **SQLite** — Metadata persistence layer
- 🧪 **JMH** — Performance benchmarking framework

### Repository Link

📂 Complete code and documentation:  
👉 [Modular Architecture (single-node)](https://github.com/pabcablan/stage_2)

### Core Principles

- Clean, decoupled design patterns
- Well-defined responsibility separation
- Solid architectural foundation for distributed evolution


## 🌐 Distributed Cluster Architecture

[![My Skills](https://go-skill-icons.vercel.app/api/icons?i=java,maven,idea,docker)](https://go-skill-icons.vercel.app/api/) &nbsp;![Hazelcast](assets/badges/hazelcastv3.1.svg) &nbsp;![ActiveMQ](assets/badges/activemq.svg) &nbsp;[![My Skills](https://go-skill-icons.vercel.app/api/icons?i=nginx)](https://go-skill-icons.vercel.app/api/) &nbsp;[![My Skills](https://skills.syvixor.com/api/icons?perline=15&i=apachejmeter)](https://go-skill-icons.vercel.app/api/) &nbsp;[![My Skills](https://go-skill-icons.vercel.app/api/icons?i=github)](https://go-skill-icons.vercel.app/api/)

### Summary

An advanced evolution into a **fully distributed architecture**, engineered to operate across multiple cooperating nodes with:

- In-memory index replication for high availability
- Automated load balancing and partial failure recovery
- Multi-node coordination and orchestration

### Technology Stack

- ☕ **Java** — Distributed service implementation
- ☁️ **Hazelcast** — Distributed in-memory data grid
- 🏗️ **ActiveMQ** — Asynchronous messaging broker
- 🐳 **Docker & Docker Compose** — Reproducible cluster deployment
- 🌐 **Nginx** — Load balancing layer
- 🧪 **Apache JMeter** — Load testing and latency profiling

### Repository Link

📂 Complete code and documentation:  
👉 [Distributed Cluster Architecture](https://github.com/pabcablan/stage_3)

### Key Characteristics

- True horizontal scalability
- No single point of failure design
- Distributed coordination across crawling, indexing, and search operations
- Experimental performance analysis and recovery evaluation


## 👥 Team Members

**Original project developed collaboratively by GuancheData:**

- **Fabio Nesta Arteaga** — 🔗 https://github.com/NestX10  
- **Pablo Cabeza** — 🔗 https://github.com/pabcablan  
- **Joel Ojeda** — 🔗 https://github.com/joelojeda  
- **Enrique Reina** — 🔗 https://github.com/ellupe  
- **Ayoze Ruano** — 🔗 https://github.com/ayozeruanoalc  


## 🙏 Acknowledgments

This repository structure and presentation format is **inspired by** the work of [Ayoze Ruano](https://github.com/ayozeruanoalc).


## 📌 Repository Information

**This repository does not contain source code.**  

Its purpose is to serve as a **central entry point and visual presentation** of the complete project.

Each architecture maintains its own repository with detailed documentation covering:

- Design decisions and rationale
- Architecture diagrams and system models
- Configuration and deployment instructions
- Performance experiments and benchmark results

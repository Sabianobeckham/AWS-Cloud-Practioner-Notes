# Module 07 – AWS Databases

## Overview

This module introduced the different AWS database services and how to choose the right database based on application requirements.

Instead of using one database for every workload, AWS provides purpose-built databases optimized for relational, NoSQL, graph, document, caching, and enterprise backup solutions.

---

## Relational Databases (SQL)

Relational databases organize data into rows and columns and enforce ACID compliance for consistency and reliability.

### Amazon RDS

Amazon RDS is a fully managed relational database service that automates:

- Database provisioning
- Software patching
- Backups
- Scaling
- Monitoring

Supported database engines include:

- Amazon Aurora
- MySQL
- PostgreSQL
- MariaDB
- Oracle
- Microsoft SQL Server

---

## NoSQL & In-Memory Databases

Designed for modern applications requiring high performance and horizontal scalability.

### Amazon DynamoDB

Key features:

- Serverless NoSQL database
- Single-digit millisecond latency
- Automatic scaling
- High availability
- Built-in encryption

Ideal for:

- Mobile apps
- Gaming
- IoT
- Large-scale web applications

---

### Amazon ElastiCache

An in-memory caching service that stores frequently accessed data inside RAM.

Benefits include:

- Faster application performance
- Reduced database load
- Supports Redis
- Supports Memcached

---

## Document Database

### Amazon DocumentDB

A managed document database compatible with MongoDB.

Features:

- JSON document storage
- Automatic scaling
- High read throughput
- Managed backups

---

## Graph Database

### Amazon Neptune

A managed graph database designed for highly connected datasets.

Common use cases:

- Social networks
- Recommendation systems
- Fraud detection
- Knowledge graphs

---

## Enterprise Data Protection

### AWS Backup

Provides centralized backup management for:

- Amazon EC2
- Amazon EBS
- Amazon RDS
- Amazon EFS

Benefits:

- Automated backup policies
- Centralized management
- Disaster recovery

---

## Disaster Recovery

AWS supports:

- Cross-region backup replication
- Secure recovery points
- High availability
- Business continuity

---

## Regulatory Compliance

AWS provides:

- Audit logging
- Compliance reporting
- Data protection
- Security controls for regulated industries

---

## Key Takeaways

- Different workloads require different database technologies.
- Amazon RDS is best for relational databases.
- DynamoDB provides scalable NoSQL storage.
- ElastiCache improves application speed using memory caching.
- DocumentDB stores JSON documents.
- Neptune is designed for graph data.
- AWS Backup simplifies enterprise backup and disaster recovery.

---

## Personal Reflection

This module helped me understand that choosing the right database is an architectural decision. AWS offers specialized database services instead of relying on a single database for every application. Learning when to use SQL, NoSQL, document, graph, and caching databases is essential for building scalable cloud solutions.

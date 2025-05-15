# 103. Components of System Design

System Design involves specifying a system’s architecture, components, interfaces, and data flow. The goal is to create systems that are scalable, efficient, and maintainable. Below are the key components commonly used in modern system designs:

---

## 1. ⚖️ Load Balancer

Load balancers distribute incoming requests across multiple servers to ensure no single server gets overwhelmed. This improves reliability, availability, and performance.

**Types:**
- **Layer 4:** Works at the transport layer (TCP/UDP/IP).
- **Layer 7:** Works at the application layer (HTTP/HTTPS).
- **Global Load Balancer:** Distributes across regions.
- **Application Load Balancer:** Tailored for specific protocols like HTTP/S.

---

## 2. 🚀 Caching

Caching stores frequently requested data temporarily to speed up response times and reduce load on primary storage (like databases).

**Benefits:**
- Faster data retrieval.
- Reduced database load.
- Improved user experience.

---

## 3. 🌍 Content Delivery Network (CDN)

A CDN is a network of geographically distributed servers that cache static assets like images, videos, and scripts to serve users from the closest location.

**Advantages:**
- Faster content delivery.
- Reduced latency.
- Better scalability under heavy loads.

---

## 4. 🌐 API Gateway

Acts as a single entry point for all client requests to backend services.

**Responsibilities:**
- Request routing and aggregation.
- Authentication & authorization.
- Load management and rate limiting.
- Traffic monitoring.

---

## 5. 🗃️ Key-Value Stores

A type of NoSQL database storing data in key-value pairs for fast access.

**Examples:**
- **In-memory:** Fastest (e.g., Redis, Memcached).
- **Persistent:** Disk-backed (e.g., RocksDB).

Used for session management, caching, and real-time analytics.

---

## 6. 💾 Blob Storage & Databases

- **Blob Storage:** Used for storing unstructured data like media files, documents, etc.
- **Databases:** Structured storage for transactional or analytical workloads (SQL, NoSQL).

Choose based on data type, query needs, and scalability.

---

## 7. 🚫 Rate Limiters

Used to control the number of requests a system processes over time, preventing abuse or overload.

**Types:**
- **Request-based**
- **User-based**
- **Token bucket algorithms**

---

## 8. 📊 Monitoring Systems

Track the health, performance, and availability of applications and infrastructure.

**Types:**
- **Network Monitoring:** Routers, switches, bandwidth.
- **System Monitoring:** CPU, memory, disk usage.
- **Application Monitoring:** Server uptime, errors, logs.

---

## 9. 📬 Distributed Messaging Queue

Enables decoupled communication between services by using message queues.

**Types:**
- **Point-to-Point**
- **Publish-Subscribe**
- **Hybrid**

Popular tools: Kafka, RabbitMQ, Amazon SQS.

---

## 10. 🆔 Distributed Unique ID Generator

Generates unique identifiers across distributed systems to avoid collisions.

**Strategies:**
- Centralized ID server
- Timestamp-based (e.g., Twitter’s Snowflake)
- Hashing with uniqueness guarantees

---

## 11. 🔍 Distributed Search

Allows search functionality over massive datasets by distributing indexing and query processing across nodes.

**Tools:**
- **Distributed Search Engines:** Elasticsearch, Solr.
- **Search-capable Databases:** MongoDB, Cassandra.
- **Cloud Search:** AWS Elasticsearch, Google Cloud Search.

---

## 12. 📜 Distributed Logging Services

Aggregates logs from all components for debugging, auditing, and monitoring.

**Options:**
- Centralized logging (e.g., ELK stack)
- Distributed systems (e.g., Fluentd, Loki)
- Cloud-based (e.g., AWS CloudWatch, Google Logging)

---

## 13. ⏰ Distributed Task Scheduler

Executes tasks at specific intervals or events in distributed systems.

**Approaches:**
- Standalone scheduler (e.g., Airflow, Celery)
- Built-in (e.g., Kubernetes CronJobs)
- Cloud-based (e.g., AWS EventBridge, Google Cloud Scheduler)

Choose based on complexity, scalability, and integration needs.

---

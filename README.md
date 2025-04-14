# Francis Docker Development Environment Services Reference

A comprehensive list of common development services, their default ports, and notes for containerized environments.

## Database Services

| Service | Default Port | Notes |
|---------|-------------|-------|
| PostgreSQL | 5432 | Primary SQL database |
| MySQL/MariaDB | 3306 | SQL alternative |
| MongoDB | 27017 | NoSQL document database |
| Redis | 6379 | Caching, pub/sub, in-memory data store |
| Elasticsearch | 9200, 9300 | Full-text search engine |
| SQLite | N/A | File-based SQL database |
| InfluxDB | 8086 | Time series database |
| Cassandra | 9042 | Distributed NoSQL database |
| CouchDB | 5984 | Document-oriented NoSQL database |
| Neo4j | 7474, 7687 | Graph database (HTTP, Bolt) |

## Messaging & Queue Services

| Service | Default Port | Notes |
|---------|-------------|-------|
| RabbitMQ | 5672, 15672 | AMQP protocol, Management UI on 15672 |
| Kafka | 9092 | Event streaming (requires Zookeeper) |
| NATS | 4222 | Lightweight messaging system |
| ZeroMQ | Variable | Distributed messaging library (uses custom ports) |
| ActiveMQ | 61616, 8161 | JMS messaging, Web Console on 8161 |
| Mosquitto (MQTT) | 1883, 8883 | IoT messaging (MQTT protocol) |

## Storage & Object Services

| Service | Default Port | Notes |
|---------|-------------|-------|
| MinIO | 9000, 9001 | S3-compatible object storage |
| Ceph | 8080 | Distributed object/block/file storage |
| GlusterFS | 24007 | Distributed file system |

## Search Services

| Service | Default Port | Notes |
|---------|-------------|-------|
| Meilisearch | 7700 | Fast search engine |
| Solr | 8983 | Apache Solr search platform |

## Coordination Services

| Service | Default Port | Notes |
|---------|-------------|-------|
| Zookeeper | 2181 | Required by Kafka, coordination service |
| etcd | 2379, 2380 | Key-value store for configs |
| Consul | 8500, 8600 | Service discovery and configuration |

## Monitoring & Observability

| Service | Default Port | Notes |
|---------|-------------|-------|
| Prometheus | 9090 | Metrics collection and alerting |
| Grafana | 3000 | Metrics visualization dashboard |
| Jaeger | 16686, 14268 | Distributed tracing system |
| Zipkin | 9411 | Distributed tracing system |
| cAdvisor | 8080 | Container resource usage analyzer |
| Kibana | 5601 | Elasticsearch UI |
| Logstash | 5044, 9600 | Log processing pipeline |

## Web Servers & Proxies

| Service | Default Port | Notes |
|---------|-------------|-------|
| Nginx | 80, 443 | Web server, reverse proxy |
| Apache | 80, 443 | Web server |
| Traefik | 80, 443, 8080 | Modern reverse proxy, web dashboard |
| HAProxy | 80, 443, 1936 | TCP/HTTP load balancer |
| Envoy | 10000, 9901 | Modern proxy |

## Development Tools & UIs

| Service | Default Port | Notes |
|---------|-------------|-------|
| pgAdmin | 5050 | PostgreSQL management UI |
| phpMyAdmin | 8080 | MySQL/MariaDB management UI |
| Adminer | 8080 | Universal database management UI |
| MongoDB Express | 8081 | MongoDB web interface |
| Redis Commander | 8081 | Redis web interface |
| Mailhog | 8025, 1025 | Email testing (UI, SMTP) |
| Portainer | 9000 | Docker management UI |
| Jenkins | 8080 | CI/CD server |
| Vault | 8200 | Secret management |

## API Services

| Service | Default Port | Notes |
|---------|-------------|-------|
| LocalStack | 4566 | AWS mock services |
| JSON Server | 3000 | Fake REST API for prototyping |
| WireMock | 8080 | Mock HTTP services |

## Web Application Development

| Service | Default Port | Notes |
|---------|-------------|-------|
| Node.js | 3000 | Default for Express/Node apps |
| React Dev Server | 3000 | Create React App default |
| Angular Dev Server | 4200 | Angular CLI default |
| Vue Dev Server | 8080 | Vue CLI default |
| Django | 8000 | Python web framework |
| Flask | 5000 | Python micro web framework |
| Ruby on Rails | 3000 | Ruby web framework |
| Spring Boot | 8080 | Java framework |
| Laravel (PHP) | 8000 | PHP web framework with Artisan |
| .NET Core | 5000, 5001 | ASP.NET Core (HTTP, HTTPS) |

## Authentication Services

| Service | Default Port | Notes |
|---------|-------------|-------|
| Keycloak | 8080, 8443 | Identity and access management |
| OpenLDAP | 389, 636 | Directory service (LDAP, LDAPS) |
| Auth0 Mock | 3010 | Local Auth0 simulation |

## Additional Tools

| Service | Default Port | Notes |
|---------|-------------|-------|
| Jupyter Notebook | 8888 | Interactive computing environment |
| SonarQube | 9000 | Code quality and security |
| Minio Browser | 9001 | Web UI for Minio |
| Swagger UI | 8080 | API documentation |
| Hasura | 8080 | GraphQL engine on PostgreSQL |
| Temporal | 7233 | Workflow engine |
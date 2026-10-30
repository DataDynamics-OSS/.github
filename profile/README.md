## Data Dynamics Open Source

Open-source tools, clients, and build tooling from [Data Dynamics Inc](https://www.data-dynamics.io) for running data platforms in production: MPP databases, data flow, governance, and the UI components around them.

### Data platform & infrastructure

| Repository | Description | Language |
|---|---|---|
| [WarehousePG](https://github.com/DataDynamics-OSS/WarehousePG) | Reproducible builds of WarehousePG (Greenplum-compatible MPP database) and PXF for Rocky Linux 9, with RPMs and an Ansible install playbook | Shell |
| [patroni-postgresql-ha](https://github.com/DataDynamics-OSS/patroni-postgresql-ha) | Ansible playbook for PostgreSQL high availability with Patroni, etcd, and PgBouncer | Shell |
| [haproxy3-rpm-builder](https://github.com/DataDynamics-OSS/haproxy3-rpm-builder) | RPM builder for HAProxy 3 | Shell |

### Apache NiFi

| Repository | Description | Language |
|---|---|---|
| [argus-flow](https://github.com/DataDynamics-OSS/argus-flow) | Apache NiFi 2.10 monorepo: custom NARs (Iceberg, Delta Lake, Debezium CDC, Hive, Kudu, Parquet), tar.gz/RPM/container packaging, and a Kubernetes operator | Java |
| [nifi-client](https://github.com/DataDynamics-OSS/nifi-client) | Java and Python clients for Apache NiFi 1.x and 2.x | Python |
| [nifi-monitoring](https://github.com/DataDynamics-OSS/nifi-monitoring) | Monitoring system for Apache NiFi and Cloudera CFM | Python |

### Data governance & catalog

| Repository | Description | Language |
|---|---|---|
| [argus-catalog](https://github.com/DataDynamics-OSS/argus-catalog) | Catalog for AI, data, and API assets | TypeScript |
| [ranger-client](https://github.com/DataDynamics-OSS/ranger-client) | Java and Python clients for Apache Ranger | Java |
| [atlas-client](https://github.com/DataDynamics-OSS/atlas-client) | Java client for Apache Atlas | Java |

### UI components & applications

| Repository | Description | Language |
|---|---|---|
| [trino-monaco-sql-editor](https://github.com/DataDynamics-OSS/trino-monaco-sql-editor) | Monaco Editor for Trino SQL with auto-completion | TypeScript |
| [oracle-monaco-sql-editor](https://github.com/DataDynamics-OSS/oracle-monaco-sql-editor) | Monaco Editor for Oracle SQL and PL/SQL with auto-completion | TypeScript |
| [scatter-sharp](https://github.com/DataDynamics-OSS/scatter-sharp) | High-performance visualization component for manufacturing sensor data | C# |
| [orbit-works](https://github.com/DataDynamics-OSS/orbit-works) | Collaboration and management service for small and mid-sized teams (up to ~100 people) | TypeScript |

### Contributing

Issues and pull requests are welcome on each repository. Please read the repository's README (and CONTRIBUTING / SECURITY files where present) before opening a pull request, and report security issues privately rather than in public issues.

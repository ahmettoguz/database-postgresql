<h1 id="top" align="center">🚢 v1.1.0 🚢</h1>

<br>

## 🔍 Table of Contents

- [Features](#features)
- [Next Release Features](#next-release-features)
- [System Startup](#system-startup)

<br/>

<h2 id="features">🔥 Features</h2>

- **Docker Containerization:** The application is containerized for consistent deployment and scaling.
- **Persistent Data:** Binds the data directory from the host machine to the container, ensuring persistent data storage even with container restarts.
- **.env Configuration:** All environment variables are easily configurable using the `.env` file, simplifying configuration management.
- **pgAdmin Backup:** Exports from pgAdmin are stored in the bind mount directory `/backup` for easy access and management.
- **Docker Compose Deployment:** Deployment is made easy with `docker-compose` for simple and reproducible setup, eliminating the need for long commands.
- **Relational Database Guide:** A comprehensive guide on relational database structure, including one-to-one, one-to-many, and many-to-many relationships, is available detailed reference.

<br/>

<h2 id="next-release-features">🚧 Next Release Features</h2>

- Not planning further features.

<br/>

<h2 id="system-startup">🚀 System Startup</h2>

- Create a new directory named `core`.
- Clone the `core-docker-config` and `core-postgresql` repositories into the `core` directory.

```
git clone https://github.com/ahmettoguz/core-docker-config
git clone https://github.com/ahmettoguz/core-postgresql
```

- Refer to the documentation provided in the [`core-docker-config`](https://github.com/ahmettoguz/core-docker-config) project for the system startup commands.

<br/>

### [🔝](#top)

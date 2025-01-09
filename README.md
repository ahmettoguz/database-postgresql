<h1 id="top" align="center">Core PostgreSQL</h1>

<br>

<div align="center">
    <img height=250 src="assets/banner.png">
</div>

<br>

## 🔍 Table of Contents

- [About Project](#intro)
- [Technologies](#technologies)
- [Features](#features)
- [Releases](#releases)
- [System Startup](#system-startup)
- [Contributors](#contributors)

<br/>

<h2 id="intro">📌 About Project</h2>

This project provides a Dockerized PostgreSQL image with customizable environment configuration. Designed to simplify database setup and management, it incorporates flexibility and scalability using Docker's containerization features. Additionally, a guide on relational database structure is available at `/guide`.

<br/>

<h2 id="technologies">☄️ Technologies</h2>

&nbsp; [![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)](https://www.docker.com/)

&nbsp; [![Postgresql](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)](https://www.postgresql.org/)

<br/>

<h2 id="features">🔥 Features</h2>

+ **Docker Containerization:** The application is containerized for consistent deployment and scaling.
+ **Persistent Data:** Binds the data directory from the host machine to the container, ensuring persistent data storage even with container restarts.
+ **.env Configuration:** All environment variables are easily configurable using the `.env` file, simplifying configuration management.
+ **Docker Compose Deployment:** Deployment is made easy with `docker-compose` for simple and reproducible setup, eliminating the need for long commands.
+ **Relational Database Guide:** A comprehensive guide on relational database structure, including one-to-one, one-to-many, and many-to-many relationships, is available detailed reference.

<br/>

<h2 id="releases">🚢 Releases</h2>

&nbsp; [![.](https://img.shields.io/badge/1.2.0-233838?style=flat&label=version&labelColor=470137&color=077521)](https://github.com/ahmettoguz/core-postgresql/tree/v1.2.0)

&nbsp; [![.](https://img.shields.io/badge/1.1.0-233838?style=flat&label=version&labelColor=470137&color=077521)](https://github.com/ahmettoguz/core-postgresql/tree/v1.1.0)

&nbsp; [![.](https://img.shields.io/badge/1.0.0-233838?style=flat&label=version&labelColor=470137&color=077521)](https://github.com/ahmettoguz/core-postgresql/tree/v1.0.0)

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

<h2 id="contributors">👥 Contributors</h2>

<a href="https://github.com/ahmettoguz" target="_blank"><img width=60 height=60 src="https://avatars.githubusercontent.com/u/101711642?v=4"></a>

### [🔝](#top)

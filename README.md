<h1 id="top" align="center">PostgreSQL <br/> 🚢 v2.1.0 🚢</h1>

<br>

<div align="center">
    <img height=250 src="assets/banner.png">
</div>

<br>

## 🔍 Table of Contents

- [Features](#features)
- [System Startup](#system-startup)

<br/>

<h2 id="features">🔥 Features</h2>

- **Docker Containerization:** The application is containerized using Docker to ensure consistent deployment, scalability, and isolation across different environments.
- **Docker Compose Deployment:** Simplifies deployment with Docker Compose configuration, enabling easy setup and service orchestration without complex commands.
- **Network Compatibility:** Uses shared Docker network to work with other services.
- **Persistent Data:** Utilizes a named Docker volume to ensure persistent storage of application data, allowing data to persist across container restarts, rebuilds, and removals.
- **.env Configuration:** All environment variables are easily configurable using the `.env` file, simplifying configuration management.
- **Relational Database Guide:** A comprehensive guide on relational database structure, including one-to-one, one-to-many, and many-to-many relationships, is available detailed reference.

<br/>

<h2 id="system-startup">🚀 System Startup</h2>

- Create a new directory named `database`.

```
mkdir database
cd database
```

- Clone project.

```
git clone https://github.com/ahmettoguz/database-postgresql
cd database-postgresql
```

- Create `.env` file based on the `.env.example` file with credentails.

```
cp .env.example .env
nano .env
```

- Create `network-database` network if not exists.

```
docker network create network-database
```

- Run container.

```
docker stop                      database-postgresql-c
docker rm                        database-postgresql-c
docker volume rm                 volume-postgresql
docker compose -p database up -d postgresql
docker logs -f                   database-postgresql-c
```

- Refer to [`pgAdmin`](https://github.com/ahmettoguz/database-pgadmin) repository to launch pgAdmin to interact with database using GUI.

- Refer to [`PostgreSQL Initializer`](https://github.com/ahmettoguz/database-initializer-postgresql) repository to easily initialize and reset the database using SQL scripts.

<br/>

### [🔝](#top)

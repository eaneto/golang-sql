# Golang Migration

Very basic tool to manage database migrations for PostgreSQL written in go.

## Usage

```bash
make
./bin/golang-migration <user> <password> <database_name>
```

### With docker compose example

```bash
docker-compose up -d
make
./bin/golang-migration user 123 test
```
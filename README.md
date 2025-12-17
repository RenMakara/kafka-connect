### Register source connetor

```
curl -X POST http://localhost:8083/connectors \
  -H "Content-Type: application/json" \
  -d @source-connector.json
```
Kafka UI → http://localhost:8080

Debezium Connect REST API → http://localhost:8083

PostgreSQL (psql) → localhost:5432 with postgres/postgres

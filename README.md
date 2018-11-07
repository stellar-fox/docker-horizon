# horizon
horizon dockerization

Usages:
## Init the horizon-db postgres
```bash
$ docker run \
  --network="compose_default" \
  horizon:latest /bin/bash -c \
    "horizon db init --db-url=\"dbname=horizon user=horizon password=horizon host=fox_horizon_db port=5432 sslmode=disable\""
```



# Setup Confluent Cloud
```
brew tap confluentinc/ccloud
brew install ccloud
```

# Setup kSQL locally
https://ksqldb.io/quickstart.html?_ga=2.210293397.1451584626.1625345213-882315242.1625345213

```
docker-compose up
docker exec -it ksqldb-cli ksql http://ksqldb-server:8088
```

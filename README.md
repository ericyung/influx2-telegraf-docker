# Influx 2.0 Telegraf Docker Compose
The docker compose setup for InfluxDB2 and Telegraf

To launch the containers run the followings at working directory:
```
docker compose up -d
```

To stop and remove the containers run the followings at working directory:
```
docker compose down
```

The .env file specifies the default InfluxDB and Telegraf version, and the initial settings of admin user, organization and bucket.
Please customize the settings for your own usage.

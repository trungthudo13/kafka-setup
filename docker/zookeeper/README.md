# Kafka Zookeeper Architecture

## Structure
```sh
docker/
├─ docker-compose.yml
├─ .env
├─ jaas/
│  ├─ broker-jaas.conf
│  └─ client-jaas.conf
└─ configs/
   ├─ server.properties    # bổ sung tham số mặc định (tùy chọn)
   └─ log4j.properties     # (tùy chọn)
```
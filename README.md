## Guide

Just run below command for a set of ElasticSearch docker instance with SSL/TLS security
```
docker-compose up -d
```

- Folder `certs` will be generated, containing the required certificates for connection
- All passwords are configurable in `.env`
- Use Kibana at `https://localhost:5601`
# docker-ent

```
# Run
docker-compose \
    -f docker-compose-elasticsearch.yml \
    -f docker-compose-enterprise-search.yml \
    up -d
```

Enterprise Search: http://localhost:3002/
u: enterprise_search
p: ELASTIC_PASSWORD (changeme)
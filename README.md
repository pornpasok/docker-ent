# docker-ent

```
# Run
docker-compose \
    -f docker-compose-elasticsearch.yml \
    -f docker-compose-enterprise-search.yml \
    up -d
```

- Elasticsearch: http://localhost:9200/
u: elastic
p: ELASTIC_PASSWORD (changeme)

- Enterprise Search: http://localhost:3002/
u: enterprise_search
p: ELASTIC_PASSWORD (changeme)

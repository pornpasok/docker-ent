# docker-ent

```
# Run
docker-compose \
    -f docker-compose-elasticsearch.yml \
    -f docker-compose-enterprise-search.yml \
    up -d
```

- Elasticsearch: http://localhost:9200/ <br>
u: elastic <br>
p: ELASTIC_PASSWORD (changeme) <br><br>

- Enterprise Search: http://localhost:3002/ <br>
u: enterprise_search <br>
p: ELASTIC_PASSWORD (changeme) <br>

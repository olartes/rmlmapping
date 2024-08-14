# rmlmapping



### Run Jena

```
docker compose up -d
```
or
```
podman compose up -d
```


### Uploading large RDF data to Apache Jena Fuseki server

```
curl -XPOST -T DATA.ttl --header "Content-type: text/turtle" http://localhost:3030/ds
```
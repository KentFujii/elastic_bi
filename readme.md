# elastic_bi

elastic-stackを用いたBI環境です

https://www.docker.elastic.co/#

```
docker-compose build
```

## beats

## elasticsearch

```
sudo sysctl -w vm.max_map_count=262144
docker build . -t elasticsearch
docker run -it elasticsearch bin/elasticsearch
curl http://elasticsearch:9200/?pretty
curl http://elasticsearch:9200/logstash-*/_search?pretty
curl http://elasticsearch:9200/logstash-*/_count
```

## kibana

## logstash

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
curl http://127.0.0.1:9200/_cat/health
```

## kibana

## logstash

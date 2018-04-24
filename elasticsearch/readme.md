```
sudo sysctl -w vm.max_map_count=262144
docker build . -t elasticsearch
docker run -it elasticsearch bin/elasticsearch
```

# Docker Killing-Floor Server


```bash
docker build -t kf-server --build-arg username='' --build-arg password='' .

docker run --rm -it -p 0.0.0.0:7707:7707/udp -p 0.0.0.0:7708:7708/udp -p 0.0.0.0:7717:7717/udp -p 0.0.0.0:28852:28852/udp -p 0.0.0.0:8075:8075/tcp -p 0.0.0.0:20560:20560/udp kf-server
```

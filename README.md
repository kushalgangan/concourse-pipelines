# concourse-pipelines

### Install Concourse using docker-compose
```
curl -O https://concourse-ci.org/docker-compose.yml
docker-compose up -d
```

### Install fly

https://concourse-ci.org/quick-start.html#install-fly

### fly login
```
fly -t tutorial login -c http://<ip-addr>:8080 -u test -p test
```
# Docker image for php 5.2 legacy projects

The features are
* Based on Ubuntu 12.04
* Apache MPM Prefork
* PHP 5.2.17 as apache mod
* Zend Optimizer

```
docker built -t bb .
docker-compose -f stack.yml up -d
```

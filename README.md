#### Steps to reproduce
```
docker build -t test-firefox-103 .
docker run -it -v $PWD:/e2e -w /e2e test-firefox-103
```
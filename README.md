# docker-puppeteer

Docker image with puppeteer and chrome installed.

## Build image

```bash
docker build \
    --build-arg=http_proxy --build-arg=https_proxy \
    -t puppeteer .
```

## Resources

* [Puppeteer - Troubleshooting](https://pptr.dev/troubleshooting)
  * [Running Puppeteer on GitlabCI](https://pptr.dev/troubleshooting#running-puppeteer-on-gitlabci)


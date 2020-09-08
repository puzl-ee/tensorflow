# This is old version. Please, find the actual version [here](https://github.com/puzl-ee/docker-images/tree/dev/images/tensorflow-2).

Tensorflow 2 framework with various python runtime. Used by puzl.ee Kubernetes cloud provider. 

#### Build:

```
docker build \
    --build-arg INTERPRETER=python3.8 \
    -t puzlcloud/tensorflow-2:python3.8 .
```

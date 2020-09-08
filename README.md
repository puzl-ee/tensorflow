# This is old version. Please, find the actual version [here](https://github.com/puzl-ee/docker-images/tree/dev/images/tensorflow-1).

Tensorflow 1 framework with various python runtime. Non-root Docker image with CUDA, used by [puzl.ee](https://puzl.ee) Kubernetes cloud provider. 

#### Build:

```
docker build \
    --build-arg INTERPRETER=python3.8 \
    -t puzlcloud/tensorflow-1:python3.8 .
```

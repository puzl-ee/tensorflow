Tensorflow 2 framework with various python runtime. Used by puzl.ee Kubernetes cloud provider. 

#### Build:

```
docker build \
    --build-arg INTERPRETER=python3.8 \
    -t puzlcloud/tensorflow-1:python3.8 .
```

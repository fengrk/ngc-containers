# 英伟达 NGC 容器加速

将英伟达 ngc 容器拉到 hub.docker.com 中，再利用阿里云等加速工具加速下载。

加速容器列表

- tensorflow:19.07-py3

```
docker pull frkhit/ngc:tensorflow-19.07-py3

# 等价于
# docker pull nvcr.io/nvidia/tensorflow:19.07-py3
```

- pytorch:19.07-py3

```
docker pull frkhit/ngc:pytorch-19.07-py3

# 等价于
# docker pull nvcr.io/nvidia/pytorch:19.07-py3
```


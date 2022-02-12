# Linux標準教科書

## DockerでCentOSをダウンロード

```bash
$ docker pull centos:latest
```



## コンテナを起動

```bash
$ docker run -d -it centos:latest /bin/bash
$ docker exec -it [CONTAINER ID] bash
```


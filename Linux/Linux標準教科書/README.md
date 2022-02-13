# Linux標準教科書

## DockerでCentOSをダウンロード

```bash
$ docker pull centos:7
```



## コンテナを起動

```bash
$ docker run -d -it centos:7 /bin/bash
$ docker exec -it [CONTAINER ID] bash
```


# docker-practice1
Docker/Kubernetes実践開発入門のサンプルコード

## build

```
$ docker image build -t example/echo:latest .
```

## run

```
$ docker container run -d -p 9000:8080 example/echo:latest
```

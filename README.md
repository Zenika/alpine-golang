# alpine-golang
Golang Docker images built on official Golang Alpine Linux
Size: ??? MB (All Layers: 268.2 MB)

Layers:
- alpine:3.4 5 MB
- git 16.99 MB
- golang:1.7 235.1 MB
- govendor 10.63 MB

# Golang version

```
docker run --rm zenika/alpine-golang go version
go version go1.7.5 linux/amd64
```

# Govendor version

```
docker run --rm zenika/alpine-golang govendor -version
V1.0.8
```

# GIT version

```
docker run --rm zenika/alpine-golang git --version
git version 2.8.3
```

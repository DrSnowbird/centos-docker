# CentOS 8 Docker with Non-root users

[![](https://images.microbadger.com/badges/image/openkbs/centos-docker.svg)](https://microbadger.com/images/openkbs/centos-docker "Get your own image badge on microbadger.com") [![](https://images.microbadger.com/badges/version/openkbs/centos-docker.svg)](https://microbadger.com/images/openkbs/centos-docker "Get your own version badge on microbadger.com")
```
IF [ you are looking for basic centos 8 (or other version) with "non-root' user setup+ as basic Docker image ]:
    THEN 'this is the Container for you'
```
# Components:
* CentOS 8
* Non-root User setup (with 'sudo' - you can disable it later in your child Container)
* Collection of Bash scripts or options with Makefile to easily use in command line of your like.

# Run (recommended for easy-start)
Default to bring you into the Container in Shell mode.
```
./run.sh
```

# RUN the Docker instance for Unix command
```
./run.sh <unix-command>
e.g.
./run.sh /bin/bash
```

# INTO Container
```
./shell.sh
```

# Pull the image from Docker Repository

```
docker pull openkbs/centos-docker
```

# Build your own image from this

```
FROM openkbs/centos-docker
```



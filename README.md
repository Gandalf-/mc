# Minio Client (mc) [![Build Status](https://travis-ci.org/minio/mc.svg)](https://travis-ci.org/minio/mc)

``mc`` provides minimal tools to work with Amazon S3 compatible object storage and filesystems. It has features to resume partial downloads, progress bar, parallel copy and network reconnect. ``mc`` is written in golang and released under [Apache license v2](./LICENSE).

## Commands

``mc`` implements the following commands 
```
  ls		List files and folders
  mb		Make a bucket or folder
  cat		Display contents of a file
  cp		Copy files and folders from many sources to a single destination
  sync		Copy files and folders from a single source to many destinations
  diff		Compute differences between two files or folders 
  access	Set access permissions
  config	Generate default configuration file [~/.mc/config.json]
  update	Check for new software updates
```

## Install 

### From Binary

Download ``mc`` from http://dl.minio.io:9000/updates/2015/Jun/mc.linux.amd64

~~~
$ wget http://dl.minio.io:9000/updates/2015/Jun/mc.linux.amd64 -O mc
$ chmod +x mc
$ ./mc
...
~~~

### From Source

```go
# go get github.com/minio/mc
```

## Public Minio Server (http://play.minio.io:9000)

Minio server is hosted at http://play.minio.io:9000 for public use. This service is primarily intended for developers and users to familiarize themselves with Amazon S3 compatible object storage. Minio runs in memory mode with auto expiry of objects in about an hour.  No account signup is required, which means S3 compatible tools and applications can access this service without access and secret keys. 

## How to use mc? 

[![asciicast](https://asciinema.org/a/19318.png)](https://asciinema.org/a/19318)

## Join The Community
* Community hangout on Gitter    [![Gitter](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/minio/minio?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
* Ask questions on Quora  [![Quora](http://upload.wikimedia.org/wikipedia/commons/thumb/5/57/Quora_logo.svg/55px-Quora_logo.svg.png)](http://www.quora.com/Minio)

## Contribute

[Contribute to mc](./CONTRIBUTING.md)

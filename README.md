# docker-unar

Note: Fork of original repository to control changes applied to repository.

You can use the unar command as docker.
http://unarchiver.c3.cx/commandline


## USAGE

```
$ docker run --rm \
  --name docker-unar \
  -u $UID:$UID \
  -v $PWD:/opt/unar \
  latiosu/docker-unar \
  [archive file path(under pwd)]
```

## AUTHOR

Sadayuki-Matsuno

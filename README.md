This image is for setup the build enviorment for Tomato

Example:

```
$ docker run -ti --rm -v <tomato-src>:/app weyou/tomato-build-env
# cd release/src-rt
# make V1=9052 V2=beta23 e3000
```


Hello BrainShare
===========

Sample Usage
------------

### Starting a web server on port 80

```bash
$ docker run -d --rm --name web-test -p 80:8000 ffsws/hello-brainshare
```

You can now interact with this as if it were a dumb web server:

```
$ curl localhost


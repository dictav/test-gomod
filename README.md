# testing Go module

```
$ curl https://proxy.golang.org/github.com/dictav/test-gomod/v4/@v/v4.0.1.info
{"Version":"v4.0.1","Time":"2021-02-04T11:38:46Z"}

$ curl https://proxy.golang.org/github.com/dictav/test-gomod/v4/@v/list
v4.0.1
```

v0, v1 と v2 以降は別扱いなので注意

```
$ curl https://proxy.golang.org/github.com/dictav/test-gomod/@v/list
(empty)
```

Dockerized `protoc-gen-julia`
=============================

Julia's `protoc-gen-julia` (from [ProtoBuf.jl](https://github.com/tanmaykm/ProtoBuf.jl/)), dockerized.

Use it by making a very simple `protoc-gen-julia` shell script somewhere and adding it to your `PATH`.  _E.g._:

```sh
#!/bin/sh
#
docker run -i --rm oeuftete/protoc-gen-julia:latest
```

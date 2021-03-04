# protobuf

Tool chain management for developing protobuf based projects.

## Hack the `PATH` environment varible

Since `buf` uses native `protoc` when builtin plugins are invoked such as builtin plugins for cpp, js, etc. See [link](https://github.com/bufbuild/buf/issues/241).

```shell
export PATH="./bin:$PATH"
```

## You need to create directory `gen/` and `proto/` before compilation

## Compilation

```
buf generate -o gen
```

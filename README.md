# onnxruntime-arm-build

Dockerfile to build ONNX Runtime for ARM CPU

- https://github.com/microsoft/onnxruntime

## Build binary

```shell
sudo rm -rf build/
make build-armhf CONFIG=RelWithDebInfo
```

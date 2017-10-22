# tensorflow-aarch64

Compiled for aarch64 architecture. This compiled tensorflow-cpu is based on https://github.com/tensorflow/tensorflow/tree/r1.4.

Hardware specifications that's being used to compile this tensorflow
---------

- rock64 board (https://www.pine64.org/?page_id=7147)
- RK3328 Quad-Core ARM Cortex A53 64-Bit Processor


How to install?
-----

1. Install pip:

```shell
curl -sL https://bootstrap.pypa.io/get-pip.py | python3 -
```

2. Install tensorflow from the provided wheel

```shell
curl -L https://github.com/lherman-cs/tensorflow-aarch64/releases/download/r1.4/tensorflow-1.4.0rc0-cp35-cp35m-linux_aarch64.whl > /tmp/tensorflow-1.4.0rc0-cp35-cp35m-linux_aarch64.whl
python3 -m pip install /tmp/tensorflow-1.4.0rc0-cp35-cp35m-linux_aarch64.whl
```

# vc4-toolchain
vc4-none-elf toolchain for VideoCore4 processor. It is a stripped down fork of [itszor's toolchain](https://github.com/itszor/vc4-toolchain), it includes:

- binutils v2.23.51 (20121030)
- gcc v6.2.1 (20161217)
- newlib v2.2.0 (20150121)

Fetch with:

```bash
$ git clone --recursive https://github.com/itszor/vc4-toolchain.git
```

Build with:

```bash
build.sh <num of parallel processes available to build, defaults to 2>
```

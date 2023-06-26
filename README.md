A [Clash.Meta](https://github.com/MetaCubeX/Clash.Meta) Alpha version OpenWrt package.

## Build

```
tar xjf openwrt-sdk-22.03.3-x86-64_gcc-11.2.0_musl.Linux-x86_64.tar.xz
cd OpenWrt-SDK-22.03.3-x86-64_gcc-11.2.0_musl.Linux-x86_64
git clone https://github.com/EkkoG/clash-meta-alpha-for-openclash.git ekko/clash
./build.sh
```

Or use docker to build:

```
git clone https://github.com/EkkoG/clash-meta-alpha-for-openclash.git
cd clash-meta-alpha-for-openclash
docker-compose up
```
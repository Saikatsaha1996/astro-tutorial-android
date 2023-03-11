# astro-tutorial-android

### How to install Astrominer For Android

# for android 2 typers of installation options available

`1) inside pure Android`
`2) inside Android with linux aarch64 distro`


# For android with linux distro

`first install Userland application from Google-Playstore & open userland & install ubuntu distro & run this cmd inside userland terminal`

```
apt update;apt install wget build-essential
```

```
mkdir astro && cd astro && wget https://github.com/dero-am/astrobwt-miner/releases/download/V1.8_BETA2/astrominer-V1.8_BETA2_aarch64_linux.tar.gz --no-check-certificate && tar -xvf astrominer-V1.8_BETA2_aarch64_linux.tar.gz
```

`now you can see inside astrominer directory some .sh file and Astrominer application so just edit pool url & your own wallet address`

# and fireup your miner with

`./XYZ.sh`

# For pure android

`first install termux from F-droid app store & run this cmd inside termux terminal`

```
pkg up;pkg upg;
```

```
apt install build-essential wget git libmicrohttps*
```

```
mkdir astrominer;cd astrominer && wget https://github.com/dero-am/astrobwt-miner/releases/download/V1.8_BETA2/astrominer-V1.8_BETA2_aarch64_android9.tar.gz && tar -xvf astrominer-V1.8_BETA2_aarch64_android9.tar.gz
```
`now you can see inside astrominer directory some .sh file and Astrominer application so just edit pool url & your own wallet address`

# and fireup your miner with

`./XYZ.sh`

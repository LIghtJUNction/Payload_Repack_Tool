# payload.bin repack tool

Using delta_generator to repack `payload.bin`.

### Requirements

- A compatible Linux system (x86_64/aarch64)
- git
- openjdk-jre
- python
- python-protobuf 
- zip
- unzip
- openssl
- openssl-tool

### Linux X86-64 (Ubuntu)
```bash
sudo apt-get install git openssl openjdk-17-jre-headless python-protobuf python unzip zip
```

### Termux
```bash
pkg install git openssl-tool zip unzip python openjdk-17
```

## Installation
```bash
git clone https://github.com/snowwolf725/Payload_Repack_Tool.git
```

## Usage

### repack `payload.bin`

```bash
cd Payload_Repack_Tool
#copy *.img into IMAGES folder
#cp -a *.img IMAGES
./repackPayload.sh
```

### repack `payload.bin` with dynamic partition info

```bash
cd Payload_Repack_Tool
#copy *.img into IMAGES folder
#cp -a *.img IMAGES
#modify META/dynamic_partitions_info.txt
#vi META/dynamic_partitions_info.txt
./repackPayload_withDpart.sh
```

### repack `OTA.zip`

```bash
cd Payload_Repack_Tool
#copy *.img into IMAGES folder
#cp -a *.img IMAGES
#modify META/*.txt SYSTEM/build.prop
#vi META/*.txt SYSTEM/build.prop
./repackZip.sh
```

https://gauss-componentotacostmanual-cn.allawnfs.com/remove-f8f3a50549d773ee1cf0a341f5273f5a/component-ota/25/05/12/34cf28d983f24e0d9621d69ff04e60f6.zip

链接1：https://gauss-compotacostauto-cn.allawnfs.com/remove-f8f3a50549d773ee1cf0a341f5273f5a/component-ota/25/05/12/34cf28d983f24e0d9621d69ff04e60f6.zip
链接2：https://gauss-componentotacostmanual-cn.allawnfs.com/remove-f8f3a50549d773ee1cf0a341f5273f5a/component-ota/25/05/12/34cf28d983f24e0d9621d69ff04e60f6.zip
更新日志：https://gauss-compotacostauto-cn.allawnfs.com/remove-f8f3a50549d773ee1cf0a341f5273f5a/component-ota/25/06/13/165e6472c9d941c7a1f9188eb8171542.html

## Demo
【Android payload.bin 打包-哔哩哔哩】 

https://b23.tv/W166gqz

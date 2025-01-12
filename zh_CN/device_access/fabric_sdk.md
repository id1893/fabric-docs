# fabric SDK 安装及使用

## 依赖

fabric sdk 依赖以下组件

- [json-c](https://github.com/json-c/json-c.git)
- [paho.mqtt.c](https://github.com/eclipse/paho.mqtt.c.git)
- [openssl](https://www.openssl.org/source/)

具体安装方式可参照相关页面

## 获取SDK

[emqx-platform-sdk](https://static.emqx.net/fabric/sdk/emqx-platform-sdk-0.6.1.tar.gz)

## 编译

```shell
cd path/emqx-platform-sdk
mkdir build
cmake ..
make
```

## 安装

```shell
make install
```

## 使用

具体使用可参照[设备端数据上报](../quick_start/device_data_upload.md)

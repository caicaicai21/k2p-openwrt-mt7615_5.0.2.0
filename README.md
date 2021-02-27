# k2p-openwrt-mt7615_5.0.2.0
For openwrt 19.07

Put directory **mtk** into **/pacagke**</br>
write to **.config**
```
CONFIG_PACKAGE_mtk-luci-plugin=y
CONFIG_PACKAGE_kmod-mt_wifi=y
CONFIG_MTK_FIRST_IF_MT7615E=y
CONFIG_MTK_MT_WIFI=y
CONFIG_MTK_WIFI_MODE_AP=m
```

**OR**

**Make menuconfig**
## Driver:
**MTK Properties > Drivers , select kmod-mt_wifi**
![屏幕截图 2021-02-27 155504](https://user-images.githubusercontent.com/26214093/109381523-e2b94980-7915-11eb-9a52-8f923a5089dd.png)
**config kmod-mt_wifi**
![屏幕截图 2021-02-27 160307](https://user-images.githubusercontent.com/26214093/109381542-fd8bbe00-7915-11eb-8c57-150e3151e128.png)
**WiFi Operation Modes, select AP**
![屏幕截图 2021-02-27 160912](https://user-images.githubusercontent.com/26214093/109381568-2ca22f80-7916-11eb-8d7d-e6978c75b22b.png)

## LUCI:
**MTK Properties > Misc**
![屏幕截图 2021-02-27 160448](https://user-images.githubusercontent.com/26214093/109381626-6ffc9e00-7916-11eb-8630-d9925915ce92.png)

## Test:
![屏幕截图 2021-02-27 125425](https://user-images.githubusercontent.com/26214093/109381700-d7b2e900-7916-11eb-99c9-d2c4d0eb7a03.png)
![屏幕截图 2021-02-27 163340](https://user-images.githubusercontent.com/26214093/109382164-b7385e00-7919-11eb-9e12-1c830a43e8a9.jpg)

## Net test:
**base network: 300M(down)/30M(up)**
![屏幕截图 2021-02-27 163746](https://user-images.githubusercontent.com/26214093/109382238-42195880-791a-11eb-8cf0-9f1c71a92b62.png)

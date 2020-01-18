# Genymotion_ARM_Translate

## Genymotion各版本ARM翻译器

```
├── LICENSE
├── README.md
└── tools
    ├── ARM_Translation_4.1.zip
    ├── ARM_Translation_4.4.zip
    ├── ARM_Translation_5.0.zip
    ├── ARM_Translation_5.1(20160402).zip
    ├── ARM_Translation_6.0.zip
    └── ARM_Translation_8.0.zip
```

## Android版本对应

* [4.1](/tools/ARM_Translation_4.1.zip)
* [4.4](/tools/ARM_Translation_4.4.zip)
* [5.0](/tools/ARM_Translation_5.0.zip)
* [5.1](/tools/ARM_Translation_5.1.zip)
* [6.0](/tools/ARM_Translation_6.0.zip)
* [8.0](/tools/ARM_Translation_8.0.zip)

## Genymotion无法安装APK解决方案：

1. 下载Genymotion-ARM-翻译 -[version]
2. 将直接下载工具箱拖放到Genymotion中,
3. 如果失败
```
  1. adb shell
  2. cd /sdcard/Download/
  3. sh /system/bin/flash-archive.sh /sdcard/Download/Genymotion-ARM-Translation.zip
  4. adb reboot
```
4. 重置模拟器

## 安装Adb

```bash
  brew cask install android-platform-tools
```

## 样本和常见问题
```
  An error occured while deploying the file.
  This probably means that the app contains ARM native code and your Genymotion device cannot run ARM instructions. You should either build your native code to x86 or install an ARM translation tool in your device.
```

## 可用的genymotion

https://mega.nz/#!ko5CHKjB!sKvk5l9RWNb-k84-KfmWSW3j-Aq1ZfUd2gBr1sottxM

```
1. 先安装genymotion-2.12.0-vbox.exe，点击next直到安装结束

2. 再安装 genymotion-2.12.0.exe

3、到桌面找到对应的软件，点击鼠标右键——打开文件位置

4、将注册机genymotion2.x-patch.exe复制到上一步打开的目录下并运行，然后点击“应用”即可
```
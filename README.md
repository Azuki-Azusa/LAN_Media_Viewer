# Readme

A micro Web server for watching videos/images on PC with other devices conecting to the same LAN.
一个用于在其他连接同一局域网的设备上观看PC上的视频/图片的微Web服务器。



#### Language
- Go
- HTML
- JavaScript
- CSS

#### Tool
- Gin
- Vue.js
- Element-UI
- Axios
- jQuery

#### OS
- Windows 10



## Table of Contents

- [Background](#background)
- [Install](#install)
- [Usage](#usage)
- [Contributors](#contributors)
- [Developing](#developing)
- [Log](#log)


## Background

家里的PS4接着电视。打火锅的时候想一边看着电脑里的视频一边吃，但电脑桌放不下火锅。于是写了这个，在PS4上开浏览器看电脑里的视频。

## Install

### git

```sh
$ git clone https://github.com/Azuki-Azusa/LAN_Media_Viewer.git
```

### download zip

Click `Code` and select `Download ZIP` on this GitHub Page.
Unzip it.

在GitHub上点击`Code`下拉菜单，点选`Download ZIP`。
本地解压即可。

## Usage

### Ready

- Create a folder named `video` in folder named `public`.
Put all videos(or folders) you want to watch in folder `public/video`.
- Create a folder named `image` in folder named `public`.
Put all images(or folders) you want to watch in folder `public/image`.

### Usage
Open `main.exe` and connect to the showed ip address via the browser on your device.
Choose the video you want to view.
Choose the folder containing the images you want to view. (The window will scroll if click the image file name)

### 准备

- 在`public`中创建名为`video`的文件夹。
将视频放进根目录的`public\video`文件夹中。
可多个文件夹存入。
- 在`public`中创建名为`image`的文件夹。
将图片放进根目录的`public\image`文件夹中。
可多个文件夹存入。

### 使用
打开`main.exe`，记住出现的ip地址。
在你希望观看的终端的浏览器上输入上述ip地址（加上端口）。
- 选择你想看的视频视频。
- 点击存放了图片的文件夹。（点击图片文件将移动滚动条到对应位置）

## Contributors

Azu機

[Weibo](https://weibo.com/cj980129)

[Twitter](https://twitter.com/c980129)

[GitHub](https://github.com/Azuki-Azusa)

## Developing
- 在PC本地保存播放进度。
- 添加音乐播放器。

## Log

- 2021.4.13 ImageViewer
- 2021.4.11 First Commit
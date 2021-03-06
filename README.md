# 私语 - 语音日记本

## 描述

使用了一段时间的微信小程序，感觉用起来挺方便，于是花了几天时间自己做了一个简易的语音日记本小程序（服务器语言选的PHP）。以语音的方式记录生活点滴。替代文字日记的理由是我觉得语音可以记录更多的信息，而不仅仅是文字。
该项目创建于2017.1.10，之后就放弃更新，因此学习价值有限。
现本人有意愿深入学习微信小程序，故决定开发一个小商店微信小程序练习。有需要共同学习微信小程序的朋友请转向 [Shop-WX](https://github.com/WalkingFrog/Shop-WX)（包含服务器端代码和数据库）。

## 功能

- 登录
- 录音、播放录音（最长一分钟）
- 上传语音日记
- 查看语音日记
- 搜索语音日记
- 删除语音日记


## 其他

这个小程序是在小相册Demo的基础上修改的。因为不熟悉JS，所以代码风格很差，照葫芦画瓢还画的很丑。
小程序的服务器是用的官方PHP环境镜像，因为后端PHP代码使用了Mysqli扩展，镜像里PHP没有Mysqli扩展，所以我把它卸载重装了。
~~欢迎小程序爱好者一起交流~~（该项目年久失修，学习价值有限，故希望大家等待最新的学习项目完成。）

## 小程序截图

![首页](https://github.com/WalkingFrog/SiYu-WX/blob/master/other/page1.png)
![我的](https://github.com/WalkingFrog/SiYu-WX/blob/master/other/page2.png)

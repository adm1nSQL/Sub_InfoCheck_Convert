# 订阅信息查询&订阅转换 Telegram Bot

## DEMO

[@houhuayuan_bot](https://t.me/houhuayuan_bot)

## 安装教程

先去botfather获取bot token，然后在vps内使用一下命令安装bot

```
git clone https://github.com/adm1nSQL/Sub_InfoCheck_Convert
```


### Debian | Ubuntu:

```
apt-get upgrade -y 
apt install -y python3 python3-pip 
pip3 install -r requirements.txt
```

### CentOS 

```
yum update -y
yun install -y python3 python3-pip
pip3 install -r requirements.txt
```

### 运行方式

直接使用Python命令调用Bot即可

```
python3 subinfo2.py
```

建议使用`screen`、`systemd`、`PM2`等工具将Bot挂在后台运行。

## 其他

### subinfo.py

> 推荐个人使用，直接发送`订阅链接`就可以返回结果

### subinfo2.py

> `/subinfo URL`

> `/sub 回复一条URL消息`

> `/dyzh URL`

> `/zh 回复一条URL消息`

## 感谢

subinfo的主要代码来源自`telegram-PGM`模块<br>
Subinfo_Checker project via. [RenaLio](https://github.com/RenaLio/SubinfoChecker)

# subscribe-yun
自动订阅云盘分享

# 声明<br><br>


# 使用教程
## 下载docker镜像
   docker push kivenray/subscribe-yun:tagname<br>

## 环境变量配置
TG_BOT_TOKEN: TG机器人token<br>
TG_BOT_USER_NAME: TG机器人名称<br>
TG_BOT_CHAT_USER_ID:你的TG账号id<br>
ALIYUN_REFRESH_TOKEN:阿里云盘的refresh_token<br>
SAVE_RESOURCE: TRUE （保存在资源盘，默认为FALSE）<br>

## 说明
需要在资源盘或备份盘创建映射目录，目前支持两种形式<br>
第一种：<br>
   资源盘/备份盘 ---> 电视剧<br>
   资源盘/备份盘 ---> 电影<br>
   资源盘/备份盘 ---> 动漫<br>

第二种：<br>
   资源盘/备份盘 --->Video ---->电视剧<br>
   资源盘/备份盘 --->Video ---> 电影<br>
   资源盘/备份盘 --->Video ---> 动漫<br>

目前仅支持自动保存<br>

## TODO
1. 根据名字识别资源信息，自动改名
2. 取出重复文件

![image](https://github.com/KivenRay/subscribe-yun/assets/24477423/7c5041e2-f4d9-461d-b02c-c90556d255dc)

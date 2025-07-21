# 表情收集

## 简介

本项目会收集一些表情包并提供 Artalk 形式的表情引用（位于 page 分支的 json/ 文件夹内）。

托管于自有服务器上，加载速度尚可😺

预览：https://emoticons.hzchu.top/

## 表情一览

| 名称         | 路径           | 出处/来源                                                    |
| ------------ | -------------- | ------------------------------------------------------------ |
| azukisan     | azukisan       | 由 [Summer](https://www.flyalready.com/) 整理                   |
| Blob         | Blob           | 由 [Summer](https://www.flyalready.com/) 整理                   |
| neko         | neko           | 由 [Summer](https://www.flyalready.com/) 整理                   |
| 小恐龙       | littledinosaur | https://t.me/addstickers/reaalLittleDinosaurHD               |
| 什么猫       | wtfcat         | https://t.me/addstickers/wtfcat2                             |
| 多洛狼       | dorow0lf   | https://t.me/addstickers/sticker_6f2be407_by_moe_sticker_bot |
| Capoo        | capoo_world    | https://t.me/addstickers/capoo_world123_by_moe_sticker_bot   |
| 克莱恩礼帽猫 | kelaien_cat    | https://t.me/addstickers/kelaien_cat_by_moe_sticker_bot      |
| 抹茶旦旦2    | mochadandan2   | https://t.me/addstickers/mochadandan2                        |
| 小熊虫3 | xiaoxiongchong3 | 微信@小熊虫com |
| 阿龙来咯 | feilong | https://t.me/addstickers/in_FDCFDC_by_NaiDrawBot |
| Strange_Fox | Strange_Fox | https://t.me/addstickers/Strange_Fox_by_moe_sticker_bot |
| blobcat_fu  | blobcat_fu      | 网络    |
| blobcat_pnd | blobcat_pnd     | 网络    |
| 猫猫虫         | bugcat          | 网络    |
| 咖波          | capoo           | 网络    |
| 酷安          | coolapk         | 网络    |
| dokomo      | dokomo          | 网络    |
| 花！          | flowerhd        | 网络    |
| mongmong    | mongmong_rabbit | 网络    |
| nobeko      | nobeko          | 网络    |
| 日行一牡丹       | rxy             | 网络    |

## 使用指南

Artalk 支持以 JSON 文件形式加载表情，理论上允许一个数组内同时包含多个对象和外部链接。在 Artalk 初始化时配置表情路径为：

```
["https://cdn.jsdelivr.net/gh/qwqcode/huaji/huaji.json","https://raw.hzchu.top/thun888/assets/refs/heads/master/static/artalk/main.json"]
```


## 自托管

修改 build.py 下配置的域名后提交即可，action 会自动为每个表情包目录生成对应的 JSON 文件。

```diff build.py
#域名
- domain = "emoticons.hzchu.top"
+ domain = "emoticons.example.com"  # 可修改为你的域名
```


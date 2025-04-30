# 4o-image-web-deploy 🖼️

![License](https://img.shields.io/badge/license-Proprietary-red)
![Status](https://img.shields.io/badge/status-Development-orange)
![Framework](https://img.shields.io/badge/framework-Vue3-green)
![Backend](https://img.shields.io/badge/backend-SpringBoot3-blue)

## 📝 项目介绍

4o-image-web-deploy 是一个基于 OAI 生图 API 开发的专业图片创作平台，可用于商业化网站运营。系统兼容 OAPI 生图格式的中转服务和直连服务。

## ✨ 功能列表

| 功能 | 状态 | 描述 |
|------|------|------|
| 👤 登录注册 | ✅ | 用户账号系统 |
| 🎨 文生图/图生图 | ✅ | AI 图像生成功能 |
| 🖼️ 我的作品 | ✅ | 用户创作管理 |
| 💰 页面购买 | ✅ | 内容付费系统 |
| 👥 用户管理 | ✅ | 后台用户控制 |
| 📢 公告管理 | ✅ | 系统通知功能 |
| 💳 支付管理 | ✅ | 支持易支付，后续将支持更多 |
| 📋 售卖计划管理 | ✅ | 商业化方案配置 |
| 🎟️ 优惠券管理 | ✅ | 促销活动支持 |
| 📊 订单管理 | ✅ | 交易记录系统 |
| ⏱️ 用户限速 | 🚧 | 正在开发中 |
| 🚫 违禁词过滤 | 🚧 | 正在开发中 |

## 演示地址
https://aphrodite.987234.xyz/index/#/paint
账号 admin
密码 123
后台地址 
https://aphrodite.987234.xyz/index/#/backend
## 🛠️ 技术栈

### 后端
- Java SpringBoot 3
- MySQL
- Redis

### 前端
- Vue 3
- Element Plus
- 绘图页面采用纯原生 HTML

## 📦 快速安装

### 执行脚本
```bash
curl -sSfL https://raw.githubusercontent.com/xiaomifengD/4o-image-web-deploy/refs/heads/main/quick-install.sh | bash
```

### 新建nginx 反代
安装后nginx 新建反代 http://127.0.0.1:8400(如果你修改了docker-compose 的映射端口，这里也要修改)


![预览](preview2.jpg)

访问地址 https://域名/
后台地址 https://域名/paint/#/backend

## ⚠️ 授权说明

本程序为专有软件，不开源。目前处于开发阶段，可申请免费授权使用。

## 📞 联系方式

如果您对本项目感兴趣，欢迎通过微信联系我进行交流：

<img src="wx.jpg" width="200px" alt="添加我的个人微信">
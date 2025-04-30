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
## 🌐 演示站点

| 类型 | 地址 | 凭据 |
|------|------|------|
| 🖼️ 前台演示 | [https://aphrodite.987234.xyz](https://aphrodite.987234.xyz) | 账号: `admin`<br>密码: `123456` |
| ⚙️ 后台管理 | [https://aphrodite.987234.xyz/paint/#/backend](https://aphrodite.987234.xyz/paint/#/backend) | 同上 |
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
### Nginx 配置说明

安装完成后，请在 Nginx 中添加反向代理配置，指向 `http://127.0.0.1:8400`  
(注意：如果您在 docker-compose.yml 中修改了映射端口，请相应调整此处配置)

![系统预览](preview2.jpg)

### 访问信息
- 🌐 前台访问：`https://您的域名/`
- 🔧 管理后台：`https://您的域名/paint/#/backend`

## ⚠️ 授权说明

本程序为专有软件，不开源。目前处于开发阶段，可申请免费授权使用。

## 📞 联系方式

<table>
  <tr>
    <td><img src="https://raw.githubusercontent.com/xiaomifengD/xiaomifengD/refs/heads/main/img/qun.jpg" width="300"/></td>
    <td><img src="https://raw.githubusercontent.com/xiaomifengD/xiaomifengD/refs/heads/main/img/contactme.jpg" width="300"/></td>
  </tr>
</table>
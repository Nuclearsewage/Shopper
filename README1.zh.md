
🛍️ Shopper — 电子商务平台
https://img.shields.io/badge/Stack-MERN-61DAFB
https://img.shields.io/badge/License-MIT-green
Shopper 是一个使用 React.js、Node.js、Express 和 MongoDB 构建的全功能电子商务平台。它支持用户注册、认证、产品管理、过滤和购物车功能，同时支持访客和登录用户。
🛍️ 功能
🔐 认证与安全
使用 JWT 进行用户认证）
使用环境变量进行敏感配置
使用 bcrypt 进行密码哈希
基于角色的路由访问（管理员 vs 用户
🛒 购物体验
带有过滤器的产品列表（颜色、尺寸、价格、类别）
支持访客和登录用户的购物车系统
可扩展的订单放置和结账逻辑
排序选项（价格、受欢迎程度）
🖥️ 管理员功能
管理员路由保护
使用 Mongoose 模型的 MongoDB 数据库
RESTful API 结构
📸 截图
表格
复制
页面	预览
首页	https://private-user-images.githubusercontent.com/133094989/433041941-d22c8504-4182-4a62-81a5-581613242b0f.png
收藏	https://private-user-images.githubusercontent.com/133094989/435084691-9dae9241-5bbd-4e2b-a376-4cd5f9b806c8.png
产品视图	https://private-user-images.githubusercontent.com/133094989/435085065-30fd9a5f-8cea-4f9d-8770-d8455ba9b8ba.png
管理员面板	https://private-user-images.githubusercontent.com/133094989/435085475-cf8c5db8-bc24-4a12-8ba8-20538fc8f8c7.png
🚀 快速开始
前提条件
Node.js (v14+)
MongoDB（本地或 Atlas）
npm 或 yarn
安装
bash
复制
# 克隆仓库
git clone https://github.com/2205308070309shenziwei/Shopper.git

# 安装依赖
<<<<<<< HEAD
=======

🛍️ Shopper —— 电子商务平台
MERN技术栈
许可证

Shopper是一个基于React.js、Node.js、Express和MongoDB构建的全功能电子商务平台。它支持用户注册、认证、商品管理、筛选功能，并为访客和登录用户提供购物车功能。

✨ 功能特性
🔐 认证与安全
基于JWT的用户认证

使用bcrypt加密密码

基于角色的路由访问控制（管理员vs普通用户）

敏感配置使用环境变量

🛒 购物体验
支持多种筛选的商品列表（颜色、尺寸、价格、类别）

访客和登录用户通用的购物车系统

可扩展的订单提交与结算逻辑

多种排序选项（价格、受欢迎程度）

🖥️ 管理功能
受保护的管理员路由

基于Mongoose模型的MongoDB数据库

RESTful API架构

📸 界面截图
页面	预览

首页	![image](https://github.com/user-attachments/assets/d22c8504-4182-4a62-81a5-581613242b0f) |
商品集合	![image](https://github.com/user-attachments/assets/9dae9241-5bbd-4e2b-a376-4cd5f9b806c8) |
商品详情	![image](https://github.com/user-attachments/assets/30fd9a5f-8cea-4f9d-8770-d8455ba9b8ba) |
管理面板	![image](https://github.com/user-attachments/assets/cf8c5db8-bc24-4a12-8ba8-20538fc8f8c7) |
🚀 快速开始
先决条件
Node.js (v14及以上版本)

MongoDB (本地或Atlas云服务)

npm或yarn包管理器

安装步骤
bash
# 克隆仓库
git clone https://github.com/yourusername/shopper.git

# 安装依赖
>>>>>>> 7bf3635d51b4bd103575a2085ab35d52336b1886
cd shopper
npm install
cd client
npm install
配置

在根目录创建一个 .env 文件：

env
MONGO_URI=mongodb://localhost:27017/shopper
JWT_SECRET=your_jwt_secret_here
PORT=5000
运行应用程序
bash
# 启动后端服务器（从根目录）
npm start

# 启动前端（从 client 目录）
cd client
npm start
🛡️ 安全特性
密码保护：bcrypt 哈希
安全认证：JWT 令牌
访问控制：管理员/用户角色分离
安全配置：环境变量
📌 未来改进
支付网关集成
产品评论系统
订单历史和运输跟踪
高级分析仪表板
👨‍💻 作者
Aakash Pawar
GitHub 个人资料 | 作品集 | 联系方式
=======
在根目录创建.env文件：

env
MONGO_URI=mongodb://localhost:27017/shopper
JWT_SECRET=你的JWT密钥
PORT=5000
运行应用
bash
# 启动后端服务（在根目录）
npm start

# 启动前端（在client目录）
cd client
npm start
🛡️ 安全特性
密码保护：bcrypt哈希加密

安全认证：JWT令牌机制

访问控制：管理员/用户角色分离

安全配置：使用环境变量

📌 未来改进计划
支付网关集成

商品评价系统

订单历史与物流追踪

高级数据分析看板

👨‍💻 作者
Aakash Pawar
GitHub个人主页 | 作品集 | 联系方式****


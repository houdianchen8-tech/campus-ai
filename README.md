# Campus AI - 智慧园区AI智慧助手系统

## 项目简介

Campus AI 是一个基于人工智能技术的智慧园区/校园智能助手系统，提供 AI 对话、PDF 智能阅读、智能客服、舒适度模拟等多种智能化服务，帮助园区/校园实现数字化与智能化管理。

## 技术栈

### 后端
- **Spring Boot** 2.5.15 — 微服务框架
- **RuoYi** 4.7.8 — 后台权限管理系统
- **Shiro** — 安全认证与权限管理
- **MyBatis** — 数据持久化
- **Druid** — 数据库连接池
- **RabbitMQ** — 消息队列
- **MySQL** — 关系型数据库
- **Redis** — 缓存

### 前端（Vue）
- **Vue 3** — 渐进式 JavaScript 框架
- **Vite** — 前端构建工具
- **Pinia** — 状态管理
- **Vue Router** — 路由管理

### 前端（Java）
- **Java Spring MVC** — 管理后台前端

## 功能特性

- 🤖 **AI 智能对话** — 基于大语言模型的智能问答交互
- 📄 **PDF 智能阅读** — 上传 PDF 文档，AI 辅助阅读与分析
- 🎮 **游戏化聊天** — 趣味互动聊天模式
- 🛋️ **舒适度模拟** — 园区环境舒适度评估与模拟
- 💬 **智能客服** — 自动化客服问答系统
- 🔐 **权限管理** — 基于 Shiro 的角色与权限控制

## 快速开始

### 环境要求
- JDK 1.8+
- MySQL 5.7+
- Redis
- Node.js 16+（Vue 前端）

### 数据库初始化
```
source campusai.sql
```

### 启动后端
```
cd backend
mvn clean package -Dmaven.test.skip=true
java -jar target/backend.jar
```

### 启动 Vue 前端
```
cd vue
npm install
npm run dev
```

### 访问地址
- Vue 前端：http://localhost:5173
- 管理后台：http://localhost:8080

## 项目结构

```
campus-ai/
├── backend/          # Java Spring Boot 后端
│   ├── src/          # 源代码
│   ├── docker/       # Docker 部署配置
│   └── pom.xml       # Maven 依赖配置
├── frontend/         # Java 管理后台前端
├── vue/              # Vue 3 前端应用
│   ├── src/          # 源代码
│   ├── dist/         # 构建产物
│   └── package.json  # 依赖配置
├── campusai.sql      # 数据库初始化脚本
└── README.md         # 项目文档
```

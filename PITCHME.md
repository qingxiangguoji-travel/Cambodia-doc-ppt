---
theme: default
background: https://images.unsplash.com/photo-1519389950473-47ba0277781c?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1740&q=80
class: text-center
highlighter: shiki
lineNumbers: false
info: |
  ## 柬埔寨证件业务管理系统
  多语言智能化证件管理解决方案
drawings:
  persist: false
transition: slide-left
title: 柬埔寨证件业务管理系统
---

# 🇰🇭 柬埔寨证件业务管理系统

## 多语言 · 智能化 · 全平台支持

<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    开始体验 <carbon:arrow-right class="inline"/>
  </span>
</div>

---

## 目录

- 📋 系统概述
- 🎯 核心功能
- 🛠️ 技术架构  
- 🌐 多语言支持
- 🚀 部署方案
- 💼 用户价值

---

## 系统概述

### 数字化转型的智能解决方案

- **🎯 目标**: 为柬埔寨证件业务提供全流程数字化管理
- **🌍 语言**: 完整支持中文、英文、柬文三语界面
- **📱 平台**: 网页版 + PWA移动端 + 桌面端
- **⚡ 特性**: 实时同步、离线支持、自动更新

```mermaid
graph LR
A[客户咨询] --> B[业务受理]
B --> C[证件办理]
C --> D[状态跟踪]
D --> E[完成交付]
E --> F[客户反馈]

登录界面
https://via.placeholder.com/800x400/1890ff/ffffff?text=%E5%A4%9A%E8%AF%AD%E8%A8%80%E7%99%BB%E5%BD%95%E7%95%8C%E9%9D%A2+-+%E6%94%AF%E6%8C%81%E4%B8%AD%E8%8B%B1%E6%9F%AC%E4%B8%89%E8%AF%AD

功能特点
🔐 安全的JWT身份认证

🌐 实时语言切换

📱 响应式设计

🔒 密码强度验证

用户体验: 30秒内完成登录流程

系统仪表板
https://via.placeholder.com/800x400/52c41a/ffffff?text=%E6%99%BA%E8%83%BD%E6%95%B0%E6%8D%AE%E4%BB%AA%E8%A1%A8%E6%9D%BF+-+%E5%AE%9E%E6%97%B6%E4%B8%9A%E5%8A%A1%E6%A6%82%E8%A7%88

核心指标
客户总数: 1,248人

在办证件: 356件

待处理: 34件

本月完成: 287件

Diagram
Code
客户管理
https://via.placeholder.com/800x400/faad14/ffffff?text=%E5%AE%A2%E6%88%B7%E4%BF%A1%E6%81%AF%E7%AE%A1%E7%90%86+-+%E5%AE%8C%E6%95%B4%E7%9A%84%E5%AE%A2%E6%88%B7%E6%A1%A3%E6%A1%88%E7%B3%BB%E7%BB%9F

功能模块
👥 客户信息完整档案

🔍 智能搜索与筛选

📊 客户业务历史

📞 联系记录跟踪

数据字段: 姓名、护照号、联系方式、地址、备注

业务流程
https://via.placeholder.com/800x400/722ed1/ffffff?text=%E8%AF%81%E4%BB%B6%E4%B8%9A%E5%8A%A1%E6%B5%81%E7%A8%8B+-+%E7%8A%B6%E6%80%81%E8%B7%9F%E8%B8%AA%E4%B8%8E%E7%AE%A1%E7%90%86

状态流转
Diagram
Code






文件管理
https://via.placeholder.com/800x400/13c2c2/ffffff?text=%E6%96%87%E4%BB%B6%E7%AE%A1%E7%90%86%E7%B3%BB%E7%BB%9F+-+%E4%B8%8A%E4%BC%A0%E4%B8%8B%E8%BD%BD%E9%A2%84%E8%A7%88

支持功能
📤 多文件同时上传

👀 在线预览文档

📥 一键下载

🔄 版本控制

🗂️ 分类管理

格式支持: PDF, JPG, PNG, DOC, DOCX
大小限制: 最大10MB/文件

移动端体验
<div style="display: flex; justify-content: center;"> <img src="https://via.placeholder.com/300x600/ff4d4f/ffffff?text=PWA移动应用" alt="移动端" style="height: 400px;"> </div>
移动特色
📱 添加到主屏幕

📷 拍照上传证件

📶 离线工作支持

🔔 推送通知提醒

安装方式: Safari → 分享 → 添加到主屏幕

多语言支持
https://via.placeholder.com/800x400/eb2f96/ffffff?text=%E5%AE%8C%E6%95%B4%E5%A4%9A%E8%AF%AD%E8%A8%80%E6%94%AF%E6%8C%81+-+%E4%B8%AD%E8%8B%B1%E6%9F%AC%E6%97%A0%E7%BC%9D%E5%88%87%E6%8D%A2

语言特性
🌐 界面元素完全本地化

⚡ 实时切换无需刷新

💾 记住用户语言偏好

🎨 文化适配的UI设计

翻译覆盖: 100%界面元素 + 业务术语

技术架构
现代化技术栈
Diagram
Code












安全架构
多层次安全防护
🔐 身份认证: JWT Token + 密码加密

🛡️ 数据安全: HTTPS + 数据加密

📊 权限控制: 角色基于权限管理系统

📝 操作审计: 完整操作日志记录

🔄 自动备份: 每日数据备份机制

部署方案
灵活部署选项
环境	推荐方案	特点
开发	Localhost	快速迭代调试
测试	GitHub Pages	免费自动部署
生产	VPS + Nginx	高性能高可用
bash
# 一键部署命令
npm run deploy
自动化工作流
CI/CD流水线
Diagram
Code






部署频率: 每日多次，零停机更新

用户价值体现
业务效益提升
⏱️ 效率提升: 减少70%手工操作

📋 错误减少: 自动化验证防止错误

💼 客户满意: 实时状态跟踪提升体验

📊 决策支持: 数据驱动业务优化

💰 成本节约: 减少纸质文档使用

开始使用
三步快速上手
🌐 访问系统: 打开浏览器输入网址

🔐 登录账户: 使用管理员账号登录

🎯 开始使用: 添加客户和创建订单

bash
# 演示账号
用户名: admin
密码: password
感谢观看
柬埔寨证件业务管理系统
高效 · 安全 · 智能 · 多语言

📧 联系邮箱: support@doc-system.com
🌐 官方网站: https://doc-system.com
📞 咨询电话: +855-12345678

Q&A环节
问题与解答
🙋 欢迎提问任何关于系统的问题

⏰ 预计时间: 15分钟

📝 我们将记录所有问题并后续提供解答

下载链接
获取相关资源
📥 完整用户手册

📥 技术文档

📥 API参考

📥 演示数据

<div style="text-align: center;"> <img src="https://via.placeholder.com/200x200/ffffff/000000?text=Scan+for+Info" alt="QR Code" style="width: 200px;"> <br> <small>扫描二维码获取最新信息</small> </div>
谢谢！
期待与您合作
数字化转型，从今天开始

text

### 2. 创建配置文件 (可选)
创建 `PITCHME.yaml` 进行高级配置：

```yaml
theme: default
background: https://images.unsplash.com/photo-1519389950473-47ba0277781c?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1740&q=80
class: text-center
highlighter: shiki
lineNumbers: false
info: |
  ## 柬埔寨证件业务管理系统
  多语言智能化证件管理解决方案
drawings:
  persist: false
transition: slide-left
title: 柬埔寨证件业务管理系统

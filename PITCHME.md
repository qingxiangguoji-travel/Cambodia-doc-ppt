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

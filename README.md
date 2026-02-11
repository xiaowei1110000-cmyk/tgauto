# 全自动群组链接检测系统 - 专业版

[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![GitHub stars](https://img.shields.io/github/stars/yourusername/telegram-group-detector)](https://github.com/yourusername/telegram-group-detector/stargazers)
[![GitHub issues](https://img.shields.io/github/issues/yourusername/telegram-group-detector)](https://github.com/yourusername/telegram-group-detector/issues)

## 📌 项目简介

**全自动群组链接检测系统** 是一个基于浏览器的专业级自动化检测工具，专为Telegram群组管理员设计。它能够：

- ✅ **自动化检测**：定时检测指定网站，自动点击Logo/按钮
- ✅ **OCR文字识别**：识别网页中的特定文字内容（如“澳门新葡京”、“505.com”）
- ✅ **跨域解决方案**：内置多代理服务器，完美解决iframe跨域限制
- ✅ **截图发送**：自动捕获页面截图并通过Telegram机器人发送
- ✅ **批量链接检测**：支持批量URL解析和匹配检测
- ✅ **数据持久化**：自动保存配置和检测结果，支持导入/导出

**完全开源，无需服务器，直接浏览器运行！**

---

## 🎯 功能特性

### 1. 群组管理
- 添加/编辑/删除群组配置
- 每个群组独立设置检测规则
- 支持自定义Logo选择器、目标文字

### 2. 自动化检测
- 内嵌代理浏览器，解决跨域限制
- 自动查找并点击指定元素
- OCR文字识别验证
- 定时/手动检测模式

### 3. 链接匹配
- 完整URL关键词匹配
- CID参数精准匹配
- 批量解析与检测队列

### 4. Telegram集成
- 自动发送检测截图
- 实时检测通知
- 支持自定义API服务器

### 5. 数据管理
- 本地存储自动保存
- JSON格式导入/导出
- 检测结果统计

---

## 🚀 快速开始

### 方法一：直接使用（推荐）

1. 访问 GitHub Pages 在线版本：[立即体验](https://yourusername.github.io/telegram-group-detector)
2. 点击“加载示例配置”快速体验
3. 配置Telegram机器人Token
4. 添加群组，开始检测

### 方法二：本地运行

```bash
# 克隆项目
git clone https://github.com/yourusername/telegram-group-detector.git
cd telegram-group-detector

# 使用Python启动简易服务器
python -m http.server 8080

# 或使用Node.js
npx http-server -p 8080

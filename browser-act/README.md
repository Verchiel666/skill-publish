# Browser Act Skill

**Version**: 2.0.2 | **Author**: BrowserAct / Verchiel | **License**: MIT

---

## 概述

AI Agent 浏览器自动化 CLI。提供完整的浏览器引擎：导航交互、数据提取与网络捕获、截图、表单自动化、多浏览器并行操作、代理支持和人机协作。

## 核心卖点

| 功能 | 说明 |
|------|------|
| 🌐 轻量提取 | 快速获取 JS 渲染内容，无需打开浏览器会话 |
| 🔐 会话管理 | 多浏览器隔离，多账号并行操作 |
| 🧩 复杂交互 | DOM 内容提取、截图、表单填写、文件上传 |
| 🛡️ Confirmation Gate | 创建/删除浏览器及敏感操作需用户确认 |
| 👥 人机协作 | headed 模式 + remote assist 处理人工步骤 |

## 安装

```bash
uv tool install browser-act-cli --python 3.12
```

## 适用场景

- 获取需要 JavaScript 渲染的页面内容
- 处理验证码/反爬页面
- 保持登录态的自动化操作
- 表单填写和工作流点击
- 多 URL 并行抓取

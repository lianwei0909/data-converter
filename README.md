# 📊 数据转换工具

Excel / CSV 原始数据 → 标准化模板一键转换，纯浏览器端运行，无需安装任何软件。

## 🚀 在线使用

👉 **https://lianwei0909.github.io/data-converter/**

## 📁 三个模块

| 模块 | 功能 |
|------|------|
| ✅ 过审 | 提取 `dispute_task_id` / `feed_id` / `evidence_text` / `pruned_desc` → 导出 8 列模板 |
| ❌ 不过审 | 提取同上字段 → 导出 6 列模板（operator 和 evidence_text 间含空白列）|
| 🎵 音乐 | 上传两个 CSV 文件，自动合并筛选「同一 feed_id 但标注结果不同」的争议数据 |

## ✨ 功能特点

- 🖱️ 支持**拖拽上传**和点击选择文件
- 📋 数据预览 + 分页浏览
- ⚡ 一键转换导出 Excel（字体 10 号）
- 🚨 「转化错误」统计：自动检测 `feed_id` / `dispute_task_id` 为空的数据行
- 🌐 完全在浏览器端运行，数据不上传服务器

## 🛠️ 本地使用

直接双击打开 `index.html` 即可，无需服务器。

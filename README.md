# quant-web-push
A PowerShell script to automatically generate quant community promos and push URLs to Baidu &amp; IndexNow.（一句话解释：自动生成量化社群推广文案并推送到百度和 IndexNow 的脚本）
# 数智量化 · 自动推广与 SEO 推送脚本

这是一个用于全站自动化推广和搜索引擎收录的 PowerShell 脚本。适用于基于静态页面生成的量化数据站点。

## ✨ 功能特性
- 自动读取当天的 `_index.json` 数据，生成合规的社群推广文案（自动复制到剪贴板）。
- **智能动态抓取**：自动扫描 24 小时内修改过的 HTML 页面，避免漏推。
- **百度主动推送**：自动去重，按优先级截断推送到百度 API。
- **IndexNow 聚合推送**：全量推送最新页面到 Bing/Yandex，极大加速收录周期。

## 🛠 使用方法
1. 修改脚本顶部的 `$Local` 和 `$Domain` 配置。
2. 替换为你自己的百度推送 Token 和 IndexNow Key。
3. 运行 `.\promote.ps1`。

## 🌐 实战案例
本脚本目前运行在 [数智shzqh.cn - 期货量化研究站](https://shzqh.cn)，实现了每日数千个品种数据页面的自动化 SEO 推送。

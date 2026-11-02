# 卡片购汇成本计算器（网页版）

按 Gate C2C 的 USDT 买单价与卡片折算率，计算：

- 实付人民币 = 目标美元金额 × USDT 单价 ÷ 卡片折算率
- 有效汇率 = USDT 单价 ÷ 卡片折算率
- 溢价差 = 有效汇率 − 真实汇率（没填折算率时用 USDT 单价 − 真实汇率）

## 手机安装

1. 用手机浏览器打开本仓库的 GitHub Pages 地址
2. iPhone：Safari 分享 -> 添加到主屏幕
   Android：Chrome 菜单 -> 添加到主屏幕 / 安装应用
3. 装好后离线也能用（service worker 已缓存）

## 文件

- index.html        计算器本体（单文件，无外部依赖）
- manifest.json     PWA 配置
- sw.js             离线缓存
- icon-*.png        主屏幕图标

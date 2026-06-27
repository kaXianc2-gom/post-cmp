# PostCmp — 岗位深度对比

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Version](https://img.shields.io/badge/version-1.2.0-brightgreen)](https://github.com/kaXianc2-gom/post-cmp/releases)
[![Pages](https://img.shields.io/badge/demo-online-0078D4)](https://kaXianc2-gom.github.io/post-cmp/)

> 拖入 Excel，选两个岗位，雷达图加多维评分对比。帮你决定报哪个。

单文件 HTML，双击即用。上传职位表后选择岗位 A 和 B，六维雷达图直观对比。

## 怎么用

1. 下载 index.html，双击打开
2. 拖入职位表（从 SheetLens 导出或直接用原始表）
3. 在下拉菜单选两个岗位
4. 看雷达图 + 分项评分 + 推荐结论

## 评分维度

| 维度 | 说明 |
|------|------|
| 竞争比 | 招考人数越少、热门地区 → 分越低 |
| 专业匹配 | 专业要求越窄 → 越匹配 → 分越高 |
| 学历优势 | 学历要求与你的学历对比 |
| 偏远度 | 一线 1 档 / 二线 2 档 / 三线以下 3 档 |
| 基层经验 | 要求基层年限越短 → 门槛越低 |
| 面试比例 | 面试占比越低 → 笔试优势越明显 |

每维度 1-5 分，加权总分直接告诉你该选哪个。

## 🌐 在线体验

无需下载，直接使用：**[🔗 在线 Demo](https://kaXianc2-gom.github.io/post-cmp/)**

## 🔐 隐私声明

- **数据不上传**：所有岗位对比、评分计算均在浏览器本地内存中完成
- **无网络请求**：ECharts 已内联，运行时零外部请求
- **无持久化存储**：关闭浏览器后数据自动清除

> ⚠️ **免责声明**：本工具仅供岗位信息对比参考，不构成报考决策建议。以官方发布信息为准。

## 技术

纯 HTML + JS，ECharts 内联（离线可用），单文件约 1MB。

## 生态位置

TableNorm → DataVeil → SheetLens → PostCmp → AppTrack

MIT License

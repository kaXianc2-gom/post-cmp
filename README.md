# ⚖ PostCmp — 岗位深度对比器

[![License](https://img.shields.io/badge/license-MIT-blue)](LICENSE)
[![Version](https://img.shields.io/badge/version-v1.0.0-green)](https://github.com/kaXianc2-gom/post-cmp/releases)

> SheetLens 筛选出候选岗后，用雷达图 + 6 维加权评分帮你做出最优选择。支持手动填写、CSV 导入、Excel 直传。

## 🎯 解决的痛点

筛选后拿到 5-10 个候选岗位，每个都有不同的特点——有的招人多但地点偏，有的在城市但竞争激烈。怎么比较？光看表格不够直观。

PostCmp 把多维对比变成一张雷达图 + 一个排名，一目了然。

## ✨ 功能

### 📝 灵活输入（三种方式）
- **手动填写**：输入部门、职位、地点、层级、人数、学历
- **📤 上传 Excel**：直接上传原始职位表，自动解析
- **📥 导入 CSV**：从 SheetLens 导出 CSV 一键导入
- **🎲 加载示例**：西部基层岗位示例数据

### 🕸 雷达图可视化
- 6 维度雷达图：偏远友好度 / 招录人数 / 城市层级 / 机构层级 / 学历匹配 / 专业匹配
- 每个岗位不同颜色，面积越大越适合

### 🎚 权重自定义
- 6 个滑块自由调整权重（0-40%）
- 拖动滑块实时重算排名

### 🏅 综合排名
- 加权总分排序，🥇🥈🥉 奖牌显示
- 卡片式展示：部门 + 职位 + 评分

### 📋 逐项对比表
- 所有字段并排对比
- 原始值 + 评分值双行显示

### 🌆 城市层级数据
- 内置 50+ 城市层级（一线→县域→乡镇）
- 偏远友好度自动计算

## 🚀 快速开始

1. [下载 index.html](https://github.com/kaXianc2-gom/post-cmp/releases/latest)
2. 双击打开
3. 点「🎲 加载示例」试效果，或「📤 上传 Excel」
4. 调整权重 → 点「⚖ 开始对比」

## 🔧 技术架构

| 项目 | 说明 |
|------|------|
| 语言 | 纯 HTML + CSS + JavaScript (ES5) |
| 图表 | ECharts 5.5.0 雷达图 |
| 表格 | SheetJS 解析 Excel |
| 隐私 | 浏览器本地计算，不上传 |

## 🏛 在生态中的位置

```
TableNorm → DataVeil → SheetLens → PostCmp → AppTrack
                                     (对比)     (追踪)
```

## ⚠ 免责声明

竞争预估基于城市层级 + 招录人数的简单模型，**仅供参考**，不构成报考建议。以官方数据为准。

## 🤖 AI 辅助

本项目使用 Claude（Anthropic Claude Code）辅助开发。

## 📄 许可证

MIT License

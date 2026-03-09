# OpenClaw 办公技能集

本项目包含适用于 OpenClaw 的办公文档处理技能集。

## 已安装的 Skills

| Skill | 功能 | 文件 |
|-------|------|------|
| docx | Word 文档创建、编辑、转换 | docx/SKILL.md |
| pptx | PPT 演示文稿制作 | pptx/SKILL.md |
| pdf | PDF 读取、转换、编辑 | pdf/SKILL.md |
| xlsx | Excel 表格处理、数据分析 | xlsx/SKILL.md |

## 安装方法

将 SKILL.md 文件复制到 OpenClaw 的 skills 目录：

```bash
cp -r docx ~/.openclaw/workspace/skills/
cp -r pptx ~/.openclaw/workspace/skills/
cp -r pdf ~/.openclaw/workspace/skills/
cp -r xlsx ~/.openclaw/workspace/skills/
```

## 使用方法

### Word 文档
- 触发词：Word、docx、文档
- 示例："把这个内容生成Word"

### PPT 演示
- 触发词：PPT、slides、presentation、deck
- 示例："做一个PPT"

### PDF 处理
- 触发词：PDF、pdf
- 示例："提取这个PDF的内容"

### Excel 表格
- 触发词：Excel、xlsx、表格
- 示例："生成一个Excel表格"

## 依赖安装

```bash
# Python 依赖
pip install python-docx python-pptx pypdf openpyxl

# Node.js 依赖
npm install docx pptxgenjs
```

## 创建时间

2026-03-09

## 作者

张志钢

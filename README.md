# CodeGate 文档

CodeGate 激活码管理服务的文档，基于 [Mintlify](https://mintlify.com) 构建。

## 多语言支持

站点支持 **中文（简体）** 与 **English**。在页面顶部可通过语言切换器切换。中文内容位于仓库根目录，英文内容位于 `en/` 目录，导航在 `docs.json` 的 `navigation.languages` 中配置。AI/LLM 索引：中文使用根路径 `/llms.txt`，英文使用 `/en/llms.txt`。

## 内容概览

- **入门**：简介、快速开始、llms.txt（AI/LLM 索引）
- **SDK**：Python、JavaScript/TypeScript 客户端使用说明
- **API 参考**：REST API 端点文档（OpenAPI）
- **AI 工具**：Cursor、Claude Code、Windsurf 配置指南（文档贡献者）

## 预览文档

在文档根目录运行 `mint dev`（需先安装 Mintlify CLI：`npm i -g mint`），在浏览器打开 `http://localhost:3000` 预览。

## 发布

安装 Mintlify GitHub App 后，推送到默认分支即可自动部署。

## 相关链接

- [CodeGate 项目](https://github.com/pfeak/codegate)
- [Mintlify 文档](https://mintlify.com/docs)

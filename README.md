# AI Code Editor

一个类似 Cursor 的 AI 代码编辑器，基于 Electron 和 Monaco Editor 开发。

## 功能特性

- ✅ 代码编辑器（基于 Monaco Editor）
- ✅ AI 聊天助手（支持 OpenAI 和 Anthropic）
- ✅ API 密钥管理
- ✅ MCP (Model Context Protocol) 服务器支持
- ✅ 代码上下文感知
- ✅ 流式 AI 响应

## 安装依赖

```bash
npm install
```

## 开发模式

```bash
npm run dev
npm run start
```

## 构建

```bash
npm run build
npm run package
```

## 配置

### API 配置

1. 点击左侧设置图标
2. 选择 "API Configuration" 标签
3. 选择 AI 提供商（OpenAI/Anthropic）
4. 输入你的 API 密钥
5. 设置模型名称

### MCP 服务器配置

1. 点击设置图标
2. 选择 "MCP Servers" 标签
3. 填写服务器名称、命令和参数
4. 点击添加

## 使用说明

- 点击聊天图标打开 AI 助手面板
- 在编辑器中编写代码
- 向 AI 提问，AI 会自动获取当前代码上下文
- 支持实时流式响应

## 技术栈

- Electron
- React
- TypeScript
- Monaco Editor
- OpenAI SDK
- Anthropic SDK
- MCP SDK

## License

MIT

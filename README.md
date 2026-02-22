# AI Code Reviewer

基于 DeepSeek API 的 AI 代码审查工具，纯前端单页应用。

## 功能

- 粘贴代码，AI 自动审查并给出改进建议
- 支持多种语言：JavaScript、TypeScript、Python、Java、Go、Rust、C/C++、PHP、Ruby、Swift、Kotlin、SQL、Shell
- 审查维度：代码质量、安全漏洞、性能优化、最佳实践
- 流式输出，实时显示审查结果
- 代码高亮（highlight.js）+ Markdown 渲染
- 响应式设计，支持移动端
- API Key 本地存储，无后端依赖

## 使用

1. 浏览器打开 `index.html`
2. 输入 DeepSeek API Key（[申请地址](https://platform.deepseek.com/)）
3. 粘贴代码，选择语言
4. 点击「开始审查」或按 `Ctrl/Cmd + Enter`

## 技术栈

- HTML + CSS + JavaScript（零依赖构建）
- [DeepSeek API](https://platform.deepseek.com/)（deepseek-chat 模型，流式响应）
- [highlight.js](https://highlightjs.org/) 代码高亮
- [marked.js](https://marked.js.org/) Markdown 渲染

## License

MIT

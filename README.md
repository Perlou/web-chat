# Web Chat

一个基于 Next.js 15 和 Vercel AI SDK 构建的现代化 AI 聊天应用，支持流式响应和优雅的用户界面。

**在线演示**: [https://webchat-rho-nine.vercel.app/](https://webchat-rho-nine.vercel.app/)

## ✨ 特性

- 🚀 **流式响应** - 实时显示 AI 生成的内容
- 💬 **现代化 UI** - 简洁优雅的聊天界面
- ⚡ **Next.js 15** - 使用最新的 React 服务器组件
- 🎨 **Tailwind CSS** - 响应式设计，支持暗色模式
- 🤖 **Google Gemini** - 由 Gemini 2.0 Flash 提供支持
- 🔄 **多轮对话** - 支持上下文记忆

## 🚀 快速开始

### 1. 克隆项目

```bash
git clone https://github.com/Perlou/web-chat.git
cd web-chat
```

### 2. 安装依赖

```bash
npm install
```

### 3. 配置环境变量

创建 `.env.local` 文件：

```bash
GOOGLE_GENERATIVE_AI_API_KEY=your_api_key_here
```

获取 API Key: [Google AI Studio](https://aistudio.google.com/apikey)

### 4. 运行开发服务器

```bash
npm run dev
```

打开浏览器访问 [http://localhost:3000](http://localhost:3000)

## 📦 技术栈

- **框架**: [Next.js 15](https://nextjs.org/)
- **UI 库**: [React 18](https://react.dev/)
- **样式**: [Tailwind CSS 4](https://tailwindcss.com/)
- **AI SDK**: [Vercel AI SDK](https://sdk.vercel.ai/)
- **LLM**: [Google Gemini 2.0 Flash](https://deepmind.google/technologies/gemini/)

## 🛠️ 可用脚本

```bash
# 开发模式
npm run dev

# 构建生产版本
npm run build

# 运行生产版本
npm start

# 代码检查
npm run lint
```

## 📁 项目结构

```
web-chat/
├── app/
│   ├── api/
│   │   └── chat/
│   │       └── route.ts      # Chat API 路由 (Edge Runtime)
│   ├── globals.css           # 全局样式
│   ├── layout.tsx            # 根布局
│   └── page.tsx              # 主页面
├── public/                   # 静态资源
└── package.json
```

## 🌐 部署

### Vercel (推荐)

1. 在 [Vercel](https://vercel.com) 上 Import 项目
2. 添加环境变量 `GOOGLE_GENERATIVE_AI_API_KEY`
3. 点击 Deploy

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/Perlou/web-chat)

## 📝 相关项目

- [ai-learning-ts](https://github.com/Perlou/ai-learning-ts) - AI 学习项目主仓库

## 📄 License

MIT

## 🤝 贡献

欢迎提交 Issue 和 Pull Request！

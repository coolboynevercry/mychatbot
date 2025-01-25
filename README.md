## Getting Started
First, run the development server:
```bash
npm install
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.
You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.


基于RAG的智能文档问答系统chatbot
基于 RAG（检索增强生成）架构开发的智能文档问答系统，支持PDF文档上传、智能检索、上下文感知对话及多轮对话历史追踪功能。
 职责描述 ：
1. 前端开发 ：使用 Next.js 14 和 TypeScript 构建现代化前端界面，实现实时对话流式响应，优化用户交互体验，集成文件上传组件，支持大规模PDF文档处理，使用 TailwindCSS 开发响应式设计界面。
2. 向量存储与检索 ：集成 Pinecone 向量数据库，实现高效的语义检索，优化文档分块策略，提升检索准确度，实现文档向量化存储和相似度检索功能，设计缓存机制提升检索性能。
3. 对话链设计 ：基于 Langchain 框架设计对话链路，集成 Deepseek 大语言模型，实现智能问答，优化提示工程（Prompt Engineering），提升回答质量，实现多轮对话上下文管理。
4. 数据持久化 ：使用 Supabase 构建用户认证和文档管理系统，通过 Drizzle ORM 实现类型安全的数据操作，设计文档元数据存储结构，支持文档版本管理，实现对话历史记录持久化存储。
5. 系统优化 ：实现文档处理的异步队列机制，优化大文件上传和处理流程，设计智能分块策略，提升检索效果，实现用户会话管理和权限控制。

 项目成果 ：
1.实现毫秒级的文档智能检索响应，支持多种文档格式的智能问答，达到90%以上的问答准确率。
2.系统可扩展性强，支持大规模文档处理，用户交互体验良好，对话流畅自然。

 技术亮点 ：
1. 创新的文档分块策略，提升检索准确度
2. 高效的向量检索算法，优化响应速度
3. 智能的上下文管理机制，提升对话连贯性
4. 完善的错误处理和回退机制
5. 类型安全的全栈TypeScript实现

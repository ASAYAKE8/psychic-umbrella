MacroEcon Pro | 宏观经济研习站
https://vercel.com/new/clone?repository-url=https://github.com/your-org/macro-econ-pro
洞察宏观，决策先人一步。
一个专业的宏观经济学学习平台，提供系统化的课程、知识点解析和政策追踪功能。
✨ 特性
📚 系统化课程 - 20+ 精品课程，从基础到高级
🧠 知识库 - 200+ 知识点，每条300字精讲
📋 政策雷达 - 实时追踪政策动态，影响评级
🔄 间隔重复 - 基于艾宾浩斯曲线的智能复习
📱 Anki导出 - 支持移动端离线学习
🔍 全文搜索 - 智能搜索，实时高亮
🌙 深色模式 - 护眼设计，支持无障碍
📊 数据可视化 - 图表展示经济关系
🚀 技术栈
前端框架: Next.js 14 (App Router)
语言: TypeScript
样式: Tailwind CSS
动画: Framer Motion
图表: Recharts
搜索: Fuse.js
存储: localStorage
部署: Vercel
📦 快速开始
本地开发
bash
复制
# 克隆项目
git clone https://github.com/your-org/macro-econ-pro.git
cd macro-econ-pro

# 安装依赖
npm install

# 启动开发服务器
npm run dev

# 访问 http://localhost:3000
构建生产版本
bash
复制
# 构建项目
npm run build

# 启动生产服务器
npm start
运行测试
bash
复制
# 运行测试
npm test

# 监听模式
npm run test:watch
🗂️ 项目结构
复制
├── src/
│   ├── app/              # Next.js App Router
│   │   ├── api/         # API路由
│   │   ├── globals.css  # 全局样式
│   │   ├── layout.tsx   # 根布局
│   │   └── page.tsx     # 首页
│   ├── components/      # React组件
│   │   ├── ui/         # 基础UI组件
│   │   └── *.tsx       # 功能组件
│   ├── data/           # 静态数据
│   │   ├── courses.json
│   │   ├── knowledge.json
│   │   ├── policies.json
│   │   └── favorites.json
│   ├── hooks/          # 自定义Hook
│   ├── types/          # TypeScript类型定义
│   └── utils/          # 工具函数
├── public/             # 静态资源
├── tests/              # 测试文件
└── docs/               # 文档
📱 页面结构
/ - 首页，展示精选内容和功能介绍
/courses - 课程中心，支持筛选和搜索
/knowledge - 知识库，按分类浏览知识点
/policy - 政策雷达，追踪最新政策动态
/favorites - 收藏夹，管理学习内容
/search - 全局搜索，支持高级筛选
/about - 关于页面，项目介绍和联系方式
🔧 核心功能
1. 间隔重复学习系统
基于艾宾浩斯遗忘曲线，智能安排复习时间：
新内容：1天后复习
困难：3天后复习
良好：7天后复习
简单：15天后复习
2. Anki卡片导出
一键生成Anki学习卡片：
正面：知识点标题
背面：摘要 + 核心内容
标签：分类 + 关键词
3. 智能搜索
全文搜索，支持模糊匹配
实时高亮显示匹配结果
按相关性排序
支持筛选和分类
4. 深色模式
自动检测系统主题
手动切换主题
无障碍设计，符合WCAG标准
🎨 设计系统
颜色方案
主色调: 深蓝 (#0B1426, #1E3A8A)
强调色: 金色 (#F59E0B)
状态色: 红/橙/绿 (影响评级)
字体
英文: SF Pro Display
中文: 思源黑体
动效
页面切换：opacity + slide (0.25s)
卡片悬停：y-1 shadow-md (200ms)
打字机效果：3秒动画
📊 性能优化
图片优化: 自动WebP格式，懒加载
字体优化: 子集化，≤120KB
代码分割: 动态导入，按需加载
缓存策略: 合理设置缓存头
压缩: Gzip压缩，减少传输体积
🔒 安全与隐私
无第三方追踪器
本地存储学习数据
符合GDPR隐私规范
支持PWA离线访问
🤝 贡献指南
欢迎贡献代码、报告问题或提出改进建议！
Fork 项目
创建特性分支 (git checkout -b feature/AmazingFeature)
提交更改 (git commit -m 'Add some AmazingFeature')
推送到分支 (git push origin feature/AmazingFeature)
开启 Pull Request
📄 许可证
本项目采用 MIT 许可证 - 查看 LICENSE 文件了解详情。
🙏 致谢
感谢以下开源项目和资源：
Next.js - React框架
Tailwind CSS - CSS框架
Framer Motion - 动画库
Recharts - 图表库
Lucide - 图标库
📞 联系方式
📧 邮箱: contact@macro-econ-pro.com
🐙 GitHub: your-org/macro-econ-pro
🌐 官网: https://macro-econ-pro.vercel.app

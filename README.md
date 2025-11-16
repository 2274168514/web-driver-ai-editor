# Web Driver - 智能代码生成平台

一个基于 AI 的智能代码生成平台，支持多种编程语言和实时预览功能。

## 🚀 功能特性

- **智能代码生成** - 基于 AI 技术生成高质量代码
- **多语言支持** - 支持 HTML、CSS、JavaScript、React、Vue 等
- **实时预览** - 即时查看代码效果
- **用户认证** - 完整的用户注册登录系统
- **历史记录** - 保存和管理生成历史
- **响应式设计** - 适配各种设备屏幕
- **现代化界面** - 玻璃化设计和流畅动画

## 🎯 项目展示

### 主界面
- 代码编辑器：支持语法高亮和自动补全
- 实时预览：在 iframe 中即时查看代码效果
- 智能生成：根据自然语言描述生成代码
- 历史管理：查看和恢复历史生成记录

### 认证系统
- **注册页面** (`welcome.html`)：美观的登录注册界面
- **Supabase 集成**：安全的用户认证和数据存储
- **状态管理**：自动检测和保持用户登录状态

## 🛠️ 技术栈

### 前端技术
- **HTML5 + CSS3 + JavaScript (ES6+)**
- **Tailwind CSS** - 现代化 CSS 框架
- **Font Awesome** - 图标库

### 后端服务
- **Supabase** - 认证服务和数据库
- **RESTful API** - 代码生成接口

### 开发工具
- **Live Server** - 本地开发服务器
- **Git/GitHub** - 版本控制和部署

## 📦 项目结构

```
web-driver-ai-editor/
├── welcome.html              # 注册登录页面
├── index.html                # 主应用界面
├── style/
│   └── main.css             # 主样式文件
├── js/
│   ├── main.js              # 主逻辑
│   ├── editor.js            # 编辑器功能
│   ├── preview.js           # 预览功能
│   ├── history.js           # 历史记录
│   └── auth.js              # 认证功能
├── lib/                     # 第三方库
├── assets/                  # 静态资源
└── README.md               # 项目说明
```

## 🚀 快速开始

### 1. 克隆项目
```bash
git clone https://github.com/2274168514/web-driver-ai-editor.git
cd web-driver-ai-editor
```

### 2. 配置 Supabase
1. 访问 [Supabase Dashboard](https://supabase.com/dashboard)
2. 创建新项目或选择现有项目
3. 在项目设置中获取 **Project URL** 和 **anon key**
4. 替换 `welcome.html` 中的配置（第 265-267 行）

```javascript
const supabase = createClient(
  'https://your-project-id.supabase.co',
  'your-anonymous-key'
);
```

### 3. 启动项目

#### 方法一：使用 Serve
```bash
# 安装 serve
npm install -g serve

# 启动服务器
serve -p 8080
```

#### 方法二：使用 Python
```bash
python -m http.server 8080
```

#### 方法三：使用 VS Code
1. 安装 **Live Server** 扩展
2. 右键点击 `welcome.html`
3. 选择 "Open with Live Server"

### 4. 访问应用
- **注册登录页面**: http://localhost:8080/welcome.html
- **主应用界面**: http://localhost:8080/index.html

## 📖 使用指南

### 注册和使用
1. 访问 `welcome.html` 注册账号
2. 登录后点击"开始使用"进入主应用
3. 在主界面中：
   - 选择编程语言
   - 描述代码需求
   - 点击"生成代码"
   - 在右侧预览效果
   - 保存到历史记录

### 主要功能
- **代码生成**: 支持自然语言描述生成代码
- **实时预览**: 在 iframe 中查看代码效果
- **历史管理**: 查看、恢复和删除历史记录
- **代码保存**: 保存生成的代码到本地
- **全屏预览**: 支持全屏查看预览效果

## 🎨 界面设计

### 设计理念
- **现代化**: 采用最新的设计趋势
- **响应式**: 完美适配各种屏幕尺寸
- **用户友好**: 直观的交互和清晰的视觉层次
- **高性能**: 优化的动画和流畅的用户体验

### 视觉特性
- **玻璃化效果**: 现代化的毛玻璃设计
- **渐变背景**: 动态的背景动画效果
- **深色主题**: 护眼且专业的配色方案
- **微交互**: 细腻的按钮和元素动画

## 🔐 安全特性

- **JWT 认证**: 基于 Supabase 的安全认证
- **邮箱验证**: 用户注册需要邮箱验证
- **密码加密**: 安全的密码存储机制
- **CORS 保护**: 跨域请求安全防护
- **输入验证**: 前端和后端双重验证

## 🚀 部署指南

### GitHub Pages 部署
1. 推送代码到 GitHub 仓库
2. 在仓库设置中启用 GitHub Pages
3. 选择源分支和根目录
4. 访问 `https://username.github.io/repository-name`

### Vercel 部署
```bash
npm install -g vercel
vercel --prod
```

### Netlify 部署
1. 连接 GitHub 仓库
2. 配置构建设置
3. 自动部署和 HTTPS

## 🤝 贡献指南

欢迎提交 Issue 和 Pull Request！

### 开发环境设置
1. Fork 项目
2. 创建功能分支
3. 提交更改
4. 发起 Pull Request

### 代码规范
- 使用 ES6+ 语法
- 遵循 Prettier 代码格式
- 添加适当的注释
- 确保响应式设计

## 📄 许可证

本项目由 中国石油大学（华东）学生 开发

## 👥 团队成员

- **孙光宇 (guangyu sun)** - 项目负责人、前端开发
  - [GitHub](https://github.com/2274168514)
  - China University of Petroleum (East China)

- **李波涛** - UI/UX 设计、前端开发
  - China University of Petroleum (East China)

- **杨健** - 后端开发、API 集成
  - China University of Petroleum (East China)

- **指导老师：李昕** - 项目指导、技术顾问
  - China University of Petroleum (East China)

## 📞 联系方式

- **项目地址**: https://github.com/2274168514/web-driver-ai-editor
- **问题反馈**: [GitHub Issues](https://github.com/2274168514/web-driver-ai-editor/issues)
- **邮箱**: 2274168514@qq.com

## 🙏 致谢

- [Supabase](https://supabase.com) - 提供认证和数据库服务
- [Tailwind CSS](https://tailwindcss.com) - 优秀的 CSS 框架
- [Font Awesome](https://fontawesome.com) - 丰富的图标库
- [GitHub](https://github.com) - 代码托管和协作平台

---

*© 2025 Web Driver Team. All rights reserved.*

*让编程更简单，让创意更自由 🚀*
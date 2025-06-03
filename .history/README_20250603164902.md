# Synote: 轻量级协作编辑器
Synote 是一款轻量级、灵感来自Notion的协作编辑器，支持实时文档协作和丰富的文本编辑功能。专为需要简单而强大写作体验的团队和知识工作者设计。

## ✨ 核心功能
### 富文本编辑
- 基础格式：粗体、斜体、颜色、标题（H1-H6）、列表、表格、分割线
- Markdown快捷键： # 标题、 - [ ] 待办事项及其他快速格式化
- 媒体嵌入：拖放图片、粘贴截图（自动Base64）、视频链接
- 模板：预设会议记录、阅读笔记等模板
- 字数统计：实时字符和单词统计
- 键盘快捷键：Ctrl+B加粗、 / 插入菜单等
### 文档与工作区管理
- 多工作区：按项目或主题组织文档
- 收藏夹：星标重要文档以便快速访问
- 最近文件：显示最近编辑的10个文档及时间戳
- 文档重命名：双击标题即可重命名
- 回收站：已删除文档保留7天
- 搜索：按标题或内容查找文档
### 实时协作
- 多用户编辑：实时查看他人的更改
- 在线状态指示：协作者的可视状态（在线/离线）
- 权限级别：所有者（完全控制）、编辑者（修改）、查看者（只读）
- @提及：通过应用内提醒通知协作者
- 版本历史：每日快照与文本差异比较
- 邀请：通过电子邮件链接共享文档
### 用户体验增强
- 主题切换：支持浅色/深色模式
- 自动保存指示：已保存更改的视觉确认
- 大纲导航：文档结构侧边栏（H1-H6）
- 响应式设计：针对桌面端（三栏）和移动端（全屏）优化
### 导入/导出
- 智能粘贴：清理来自Word/HTML内容的格式
- 导出选项：PDF（保留布局）和Markdown格式
## 🚀 快速开始
### 前提条件
- Node.js v18+
- PostgreSQL
- Redis
### 安装 克隆仓库
```
git clone https://github.com/yourname/Synote.git
cd Synote
```
### 安装依赖
```
cd backend && npm install
cd ../frontend && npm install
``` 
### 配置环境变量
```
cp backend/.env.example backend/.env
cp frontend/.env.example frontend/.env
``` 
### 启动开发服务器
```
cd backend && npm run start:dev
cd frontend && npm run dev
```
### 访问编辑器： http://localhost:3000

## 🛠️ 技术栈
- 前端：Vue 3 + TypeScript + Pinia + TipTap (ProseMirror)
- 后端：NestJS + Socket.IO + PostgreSQL
- 实时协作：Yjs (CRDT)
- AI集成：LangChain + OpenAI API
- 部署：Docker + Kubernetes
## 🌐 在线演示
- 体验Synote： https://synote.app
- 文档： https://docs.synote.app
## 🤝 贡献
我们欢迎贡献！请按照以下步骤操作：

1. Fork仓库
2. 创建功能分支（ git checkout -b feat/your-feature ）
3. 提交更改（ git commit -m 'Add some feature' ）
4. 推送到分支（ git push origin feat/your-feature ）
5. 开启Pull Request
详情请参阅我们的 贡献指南 。

## 📄 许可证
本项目采用MIT许可证 - 详情请参阅LICENSE文件。

Synote - 让协作写作变得简单。 ✍️🤝
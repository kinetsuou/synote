Synote: Lightweight Collaborative Editor
https://img.shields.io/badge/License-MIT-blue.svg
https://img.shields.io/badge/PRs-welcome-brightgreen.svg

​Synote​ is a lightweight, Notion-inspired collaborative editor that enables real-time document collaboration with rich text editing capabilities. Designed for teams and knowledge workers who need a simple yet powerful writing experience.

https://via.placeholder.com/1200x600?text=Synote+Editor+Interface+Showcase

✨ Key Features
Rich Text Editing
​Basic formatting: Bold, italic, colors, headings (H1-H6), lists, tables, dividers
​Markdown shortcuts: # Headings, - [ ] Todo lists, and other quick formatting
​Media embedding: Drag-and-drop images, paste screenshots (auto Base64), video links
​Templates: Pre-built templates for meeting notes, reading notes, and more
​Word count: Real-time character and word statistics
​Keyboard shortcuts: Ctrl+B for bold, / for insert menu, etc.
Document & Workspace Management
​Multiple workspaces: Organize documents by projects or topics
​Favorites: Star important documents for quick access
​Recent files: Last 10 edited documents with timestamp
​Document renaming: Double-click titles to rename
​Recycle bin: 7-day retention for deleted documents
​Search: Find documents by title or content
Real-time Collaboration
​Multi-user editing: See others' changes in real-time
​Presence indicators: Visual status (online/offline) for collaborators
​Permission levels: Owner (full control), Editor (modify), Viewer (read-only)
​​@mentions: Notify collaborators with in-app alerts
​Version history: Daily snapshots with text diff comparison
​Invitations: Share documents via email links
UX Enhancements
​Theme switching: Light/dark mode support
​Auto-save indicator: Visual confirmation of saved changes
​Outline navigation: Document structure sidebar (H1-H6)
​Responsive design: Optimized for desktop (3-column) and mobile (full-screen)
Import/Export
​Smart paste: Clean formatting from Word/HTML content
​Export options: PDF (preserves layout) and Markdown formats
🚀 Getting Started
Prerequisites
Node.js v18+
PostgreSQL
Redis
Installation
bash
复制
# Clone repository
git clone https://github.com/yourname/Synote.git
cd Synote

# Install dependencies
cd backend && npm install
cd ../frontend && npm install

# Configure environment variables
cp backend/.env.example backend/.env
cp frontend/.env.example frontend/.env

# Start development servers
cd backend && npm run start:dev
cd frontend && npm run dev
Access the editor at: http://localhost:3000

🛠️ Tech Stack
​Frontend: Vue 3 + TypeScript + Pinia + TipTap (ProseMirror)
​Backend: NestJS + Socket.IO + PostgreSQL
​Real-time Collaboration: Yjs (CRDT)
​AI Integration: LangChain + OpenAI API
​Deployment: Docker + Kubernetes
🌐 Live Demo
Experience Synote: https://synote.app
Documentation: https://docs.synote.app

🤝 Contributing
We welcome contributions! Please follow these steps:

Fork the repository
Create your feature branch (git checkout -b feat/your-feature)
Commit your changes (git commit -m 'Add some feature')
Push to the branch (git push origin feat/your-feature)
Open a pull request
See our Contribution Guidelines for details.

📄 License
This project is licensed under the MIT License - see the LICENSE file for details.

​Synote​ - Collaborative writing made simple. ✍️🤝

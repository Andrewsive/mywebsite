# Yichen Chen - 个人作品集网站

这是一个现代化的个人作品集网站，使用 React、Tailwind CSS 和 Framer Motion 构建。

## 如何在本地运行

### 方法 1：直接打开（推荐）

1. 直接双击 `main.html` 文件，在浏览器中打开即可
2. 或者右键 `main.html` → "打开方式" → 选择你的浏览器（Chrome、Edge、Firefox等）

### 方法 2：使用本地服务器（推荐用于开发）

如果你遇到跨域问题或想要更好的开发体验，可以使用本地服务器：

#### 使用 Python（如果已安装）

```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```

然后在浏览器访问：`http://localhost:8000/main.html`

#### 使用 Node.js（如果已安装）

安装 `http-server`：
```bash
npm install -g http-server
```

运行服务器：
```bash
http-server -p 8000
```

然后在浏览器访问：`http://localhost:8000/main.html`

#### 使用 VS Code Live Server 插件

1. 在 VS Code 中安装 "Live Server" 插件
2. 右键 `main.html` 文件
3. 选择 "Open with Live Server"

## 项目结构

```
mywebsire/
├── main.html          # 主页面文件
├── portrait.jpg       # 个人照片
└── 作品集/            # 作品集图片文件夹
    ├── 中药配伍/
    ├── A design版面/
    ├── Blueclip Buddies/
    ├── Shared Dwelling/
    └── 墨迹/
```

## 技术栈

- **React 18**: 用于构建交互式用户界面
- **Tailwind CSS**: 快速构建现代化样式
- **Framer Motion**: 流畅的动画效果
- **CDN 引入**: 所有依赖通过 CDN 加载，无需 npm 安装

## 特性

- ✨ 现代化极简设计风格
- 🎨 自定义鼠标光标效果
- 📱 完全响应式设计
- 🎭 流畅的动画和过渡效果
- 🖼️ 作品集展示和详情页
- 📧 联系方式和社交媒体链接

## 浏览器兼容性

- Chrome/Edge（推荐）
- Firefox
- Safari
- 需要支持 ES6+ 和现代 CSS 特性

## 自定义内容

如果你想修改网站内容：

1. **个人信息**：搜索 "Yichen Chen" 并替换为你的名字
2. **作品集数据**：在 `projects` 数组中修改（第 129-191 行）
3. **个人简介**：在 "About" 部分修改文字（第 335-396 行）
4. **联系方式**：修改邮箱地址和社交媒体链接（第 493-524 行）
5. **个人照片**：替换 `portrait.jpg` 文件

## 注意事项

- 确保 `作品集` 文件夹中的图片文件存在
- 图片路径区分大小写
- 建议使用现代浏览器以获得最佳体验
- 所有外部依赖（React、Tailwind、Framer Motion）都通过 CDN 加载，需要网络连接

## 问题排查

如果网站无法正常显示：

1. **检查浏览器控制台**：按 F12 打开开发者工具，查看是否有错误
2. **检查图片路径**：确认 `作品集` 文件夹和图片文件都在正确位置
3. **网络连接**：确保可以访问 CDN 资源（unpkg.com、googleapis.com）
4. **浏览器缓存**：尝试清除缓存或使用隐私/无痕模式

---

© 2026 Yichen Chen


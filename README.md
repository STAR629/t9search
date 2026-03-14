# T9快捷拨号 - 应用介绍页面

简洁的应用介绍静态页面，展示T9快捷拨号的核心功能和联系方式。

## 页面结构

```
support-page/
├── index.html          # 主HTML文件
├── css/
│   └── styles.css      # 样式文件
└── README.md           # 项目说明文档
```

## 页面内容

- **导航栏**: 品牌Logo和名称
- **Hero区域**: 应用标题和副标题
- **关于应用**: 应用简介
- **核心功能**: 4个功能卡片展示
  - T9智能搜索
  - 多种搜索方式
  - 收藏夹
  - 隐私保护
- **联系我们**: 邮箱联系方式 (t9search@163.com)
- **页脚**: 版权信息和ICP备案号

## 本地预览

直接在浏览器中打开 `index.html` 文件即可预览。

或使用本地服务器:

```bash
# Python
python -m http.server 8000

# Node.js
npx http-server -p 8000
```

访问 http://localhost:8000 查看页面。

## GitHub Pages 部署

### 步骤1: 创建GitHub仓库

1. 登录 [GitHub](https://github.com)
2. 点击 **+** → **New repository**
3. 填写信息:
   - Repository name: `t9-dialer-support`
   - 选择 **Public**
4. 点击 **Create repository**

### 步骤2: 上传文件

```bash
cd support-page
git init
git add .
git commit -m "Initial commit"
git remote add origin https://github.com/YOUR_USERNAME/t9-dialer-support.git
git branch -M main
git push -u origin main
```

### 步骤3: 启用GitHub Pages

1. 进入仓库 **Settings** → **Pages**
2. Source: **Deploy from a branch** → **main** → **/(root)**
3. 点击 **Save**

### 步骤4: 访问网站

等待2分钟后访问:
```
https://YOUR_USERNAME.github.io/t9-dialer-support/
```

## 技术栈

- HTML5
- CSS3 (CSS变量、Flexbox、Grid)
- 响应式设计 (桌面、平板、手机)
- 纯静态页面，无需JavaScript

## 浏览器兼容性

- Chrome 80+
- Firefox 75+
- Safari 13+
- Edge 80+
- iOS Safari 13+
- Android Chrome 80+

## 联系方式

邮箱: t9search@163.com

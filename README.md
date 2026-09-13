# 第一次随堂任务 —— 万物互联 · 极致体验

按素材设计图还原的网页布局，纯 HTML + CSS 实现，不含任何框架与外部依赖。

## 一、目录结构

```
html5-layout/
├── index.html        页面结构
├── style.css         页面样式
├── images/           素材图片（图标）
│   ├── 1.png         HTML5 盾牌徽标（左栏大图标）
│   ├── 2.png         HTML5 徽标（右栏大图标）
│   ├── 3.png         苹果图标（原生移动APP开发）
│   ├── 4.png         微信图标（微信公共平台开发）
│   ├── 5.png         显示器图标（网站开发）
│   └── 6.png         笔记本图标（桌面应用开发）
└── fonts/
    └── 书法.ttf      标题“万物互联 极致体验”使用的书法字体
```

## 二、制作要点

1. **标题字体**：使用素材中的 `fonts/书法.ttf`，通过 `@font-face` 引入，配合 `text-shadow` 制作投影效果。
2. **图标**：使用素材中的图片实现（题目提示允许“插入图片”或使用 iconfont 两种方式，本作品采用图片方式，与设计图完全一致）。
3. **整体布局**：容器宽 1240px 居中；两栏文字各 596px、栏间距 48px；“平台支持”为四等分横向排列。
4. **文字排版**：正文 20px、行高 46px、居中；因设计图每行文字断行位置固定，正文按设计图逐行断行，保证与设计稿完全一致。
5. **字体兼容**：正文使用“微软雅黑 / Microsoft YaHei”，并保留 Arial 等后备字体。

## 三、本地查看

双击 `index.html` 用浏览器打开即可（建议使用 Chrome / Edge）。

## 四、推送到 GitHub / Gitee

仓库已经在本地初始化并完成首次提交，只需创建远程仓库后执行：

```bash
# GitHub（把用户名和仓库名换成自己的）
git remote add origin https://github.com/你的用户名/html5-layout.git
git branch -M main
git push -u origin main

# 或者 Gitee
git remote add origin https://gitee.com/你的用户名/html5-layout.git
git branch -M main
git push -u origin main
```

推送完成后，把仓库链接（例如 `https://github.com/你的用户名/html5-layout`）连同源文件一起提交到随堂任务即可。

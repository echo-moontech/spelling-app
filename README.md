# PWA 图标生成说明

由于当前环境没有图像处理工具，请使用以下方法生成图标：

## 方法一：在线工具（推荐）

1. 访问 **https://realfavicongenerator.net/** 或 **https://favicon.io/**
2. 上传一张图片或使用文字生成图标
3. 下载生成的图标包
4. 将 `icon-72.png` 到 `icon-512.png` 放入 `icons` 文件夹

## 方法二：使用 Canva

1. 打开 Canva (https://www.canva.com/)
2. 创建 512x512 的画布
3. 设计你的图标（建议用渐变背景 + 📝 或 ABC 文字）
4. 导出为 PNG
5. 使用在线工具缩放到不同尺寸

## 方法三：使用图标占位符

PWA 仍然可以工作，只是图标可能不显示。你可以先用 SVG 图标临时替代。

## 推荐图标设计

- 背景：紫色渐变 (#667eea → #764ba2)
- 图标：📝 或 "ABC" 文字
- 风格：简洁、现代、易识别

## 临时方案

我已经生成了 SVG 格式的图标 (icon-72.svg)，你可以：
1. 用浏览器打开 SVG 文件
2. 截图保存为 PNG
3. 调整到不同尺寸

---

## 文件结构

```
spelling-app-pwa/
├── index.html          (主应用)
├── words.js            (词库)
├── manifest.json       (PWA配置)
├── sw.js               (Service Worker)
├── icons/
│   ├── icon-72.png
│   ├── icon-96.png
│   ├── icon-128.png
│   ├── icon-144.png
│   ├── icon-152.png
│   ├── icon-192.png
│   ├── icon-384.png
│   └── icon-512.png
└── README.md           (本文件)
```

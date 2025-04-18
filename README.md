# CSS3 照片墙特效 🖼️

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Deployed-brightgreen)](https://trying-c.github.io/CSS3-Photo-Wall/)

一个基于纯 CSS3 实现的动态照片墙项目，通过优雅的悬停动画展现图片交互效果。

👉 **在线预览**：<https://trying-c.github.io/CSS3-Photo-Wall/>

## ✨ 核心特性

- 🎨 **纯 CSS3 动画**  
  无 JavaScript 依赖，完全通过 CSS 实现旋转缩放效果
- 🖱️ **悬停交互**  
  鼠标悬停触发图片立体旋转 + 放大动画
- 📱 **响应式布局**  
  自适应不同屏幕尺寸（桌面/平板/手机）
- 🌈 **视觉层次感**  
  错落有致的图片排列与投影效果

## 🛠️ 技术实现

| 技术点           | 实现方式                      | 关键代码片段                 |
|------------------|-----------------------------|------------------------------|
| **悬停动画**     | `transform: rotate() scale()` | 使用 `transition` 平滑过渡   |
| **立体效果**     | `perspective` + `rotate3d`   | 创建 3D 空间透视            |
| **图片布局**     | CSS Grid 布局                | 定义行列间距与对齐方式       |
| **阴影效果**     | `box-shadow` 多层叠加        | 增强立体层次感              |

## 📂 项目结构

```text
CSS3-Photo-Wall/
├── index.html          # 网页主结构
├── style.css           # 核心动画样式
├── images/             # 图片资源目录
│   ├── photo1.jpg
│   ├── photo2.jpg
│   └── ... 
└── README.md           # 项目说明文档

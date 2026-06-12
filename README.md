# 🧧 2026 农历马年春节专属好运测试 (New Year Luck Test 2026)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](#)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)](#)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)](#)

一个纯原生（HTML5 + CSS3 + Vanilla JS）开发的**2026马年春节主题**趣味好运测试单页面。拥有浓郁的国潮中国风视觉设计、丝滑的移动端交互体验以及趣味十足的“玄学”测试结果，极适合用于春节期间的朋友圈互动、群聊分享或个人主页整蛊。

---

## ✨ 项目特性

* **🏮 纯正中国风视觉**：采用经典的“中国红 + 璀璨金”配色，搭配细腻的渐变与阴影，秒入新春氛围。
* **📱 完美移动端适配**：原生支持流式布局与 `Viewport` 锁定，防误触放大，专为微信、手机浏览器触控优化。
* **🎉 动态粒子特效**：首个选项独家触发**“暴富金币雨”**动画，采用原生 JS 动态生成，不依赖任何第三方动画库。
* **🎭 趣味互动文案**：
    * **红包盒**：触发大吉大利的财运金币雨。
    * **礼物盒**：幽默的“未充值”整蛊提示。
    * **生肖盒**：当代打工人的“搬砖姿势更帅”扎心现实。
    * **钻石盒**：需要对朋友说“大笨猪”才能解密的隐藏强制互动。
* **⚡ 极简轻量**：单文件全内联结构，无任何外部依赖，秒速加载。

---

## 📸 界面预览

> **💡 说明**：项目在移动端展现效果最佳。

| 📊 首页布局 (Grid) | 🎁 测试弹窗 & 金币雨特效 (Modal & Animation) |
| :---: | :---: |
| <img src="https://via.placeholder.com/300x600/a51c1c/ffffff?text=Main+Interface" width="240" alt="主界面预览"/> | <img src="https://via.placeholder.com/300x600/a51c1c/ffd700?text=Lucky+Rain+Effect" width="240" alt="弹窗特效预览"/> |

---

## 🚀 快速启动

由于本项目属于**零依赖**的纯前端页面，你可以通过以下几种非常简单的方式运行或部署它：

### 1. 本地运行
1. 克隆或下载本项目到本地。
2. 双击 `index.html` 文件，即可直接在任意浏览器中打开体验。

### 2. 静态部署 (推荐)
你可以直接把代码托管到免费的静态网站服务中：
* **GitHub Pages**：直接在仓库的 `Settings -> Pages` 中开启即可。
* **Vercel / Netlify**：导入此仓库，无需任何构建命令，直接一键发布。

---

## 🛠️ 技术实现细节

* **CSS Grid & Flexbox**：实现完美居中的九宫格（2x2）布局与弹窗垂直居中。
* **CSS 变量 (`:root`)**：提取主题红（`--primary-red`）和黄金色（`--gold`），方便一键换肤。
* **`@keyframes` 动画**：通过控制 `translateY` 和 `rotate` 属性，实现表情符号从天而降的物理抛物感。
* **Backdrop Filter**：弹窗背景启用 `backdrop-filter: blur(5px)`，营造高级的高斯模糊遮罩质感。

---

## 📜 开源协议

本项目基于 **[MIT License](LICENSE)** 协议开源。你可以自由地修改文案、添加新的盒子选项或用于你的个人非商业项目，期待你的奇思妙想！

---

祝大家在 2026 马年：**马到成功，好运连连！🐴✨**

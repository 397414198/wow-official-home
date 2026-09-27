# ⚔️ LoneWalkerLee · Azeroth

> **一个属于自己的艾泽拉斯。**
>
> 闲着没事，给自己做了一个魔兽世界。

这是 `LoneWalkerLee` 的私人《魔兽世界》入口首页。

它不是商业服务器官网，也没有试图把自己包装成什么“大型魔兽世界”。  
这里更像是一扇门——推开之后，是一台 NAS、一套 Docker、AzerothCore、PlayerBots，以及一个自己慢慢搭出来的小世界。

## 🌌 首页设计

这一版首页采用 **Wrath of the Lich King / 诺森德 / 冰霜魔法** 视觉方向：

- ❄️ 冰冠、诺森德、冰霜色调
- ⚔️ 联盟 / 部落双阵营视觉
- 🗺️ 诺森德装饰地图
- ✦ `MY AZEROTH` 私人世界故事区
- 🧙 PlayerBots 冒险者展示
- 🏰 “进入艾泽拉斯”主入口
- 📜 三步进入游戏流程
- 🌨️ 轻量雪花与首屏视差效果
- 📱 手机端适配
- ♿ 支持 `prefers-reduced-motion`

## 🧩 技术

纯前端静态页面：

- HTML
- CSS
- Vanilla JavaScript
- Google Fonts
- 无数据库
- 无后端 API
- 无额外构建工具
- 无额外运行时依赖

**这一版不需要修改 AzerothCore 数据库，也不会读取服务器实时状态。**

## 📁 文件

```text
.
├── index.html
├── style.css
└── assets/
    ├── hero.jpg
    ├── banner.png
    ├── bg-texture.png
    ├── icons.png
    ├── logo.png
    └── wechat-qr.png
```

## 🚀 部署

如果使用 Cloudflare Pages：

1. 将仓库内容提交到 GitHub。
2. Cloudflare Pages 连接仓库。
3. 构建命令留空。
4. 输出目录使用项目根目录。
5. 保存并部署。

本项目没有构建步骤，提交 `index.html` / `style.css` 后即可直接发布。

## 🔗 页面入口

- 官网首页：由本项目部署
- 账号注册：`https://wow.lonewalkerlee.dpdns.org/`

游戏客户端不会直接放在网页上，需要联系服主获取。

## ⚔️ 关于这个世界

服务器基于：

- AzerothCore
- PlayerBots
- Docker
- Linux / NAS

版本定位为：

**World of Warcraft · Wrath of the Lich King · 3.3.5a**

这是一个个人折腾项目。

没有商业化运营，没有充值商城，也没有“万人在线”的目标。

只是因为喜欢，所以把它重新点亮。

## 📜 说明

《魔兽世界》及相关角色、素材、商标等知识产权归其相应权利人所有。

本项目为个人学习、折腾与朋友之间体验用途，并非暴雪娱乐官方项目。

---

### For Azeroth. ⚔️

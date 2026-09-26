# LoneWalkerLee 官方首页 v1.1（带图片版）

80年代像素复古 + 魔兽主题官方门户，纯静态，适合 GitHub + Cloudflare Pages。

## 文件结构

```
wow-official-home/
├── index.html
├── style.css
├── README.md
└── assets/
    ├── logo.png          ← 主 Logo（文字+剑盾）
    ├── banner.png        ← 宽横幅（艾泽拉斯夜景）
    ├── icons.png         ← 按钮图标组（可选）
    └── bg-texture.png    ← CRT 背景纹理
```

## 使用方法

1. 把生成的图片保存到 `assets/` 文件夹，按上面文件名命名。
2. 上传整个文件夹到 GitHub 私有仓库。
3. 用 Cloudflare Pages 连接仓库部署（Framework: None，输出目录: `/`）。
4. 绑定你的 `.dpdns.org` 子域名。

## 图片说明

- `logo.png`：主视觉 Logo（最重要）
- `banner.png`：页面中间宽横幅
- `bg-texture.png`：深色 CRT 背景纹理（会平铺）
- `icons.png`：可选，当前版本按钮用了 emoji，不依赖它

## 与注册站融合

大按钮已指向：`https://wow.lonewalkerlee.dpdns.org/`

注册成功后建议跳回本首页：

```html
<script>
  setTimeout(() => {
    window.location.href = 'https://你的首页地址/';
  }, 2500);
</script>
```

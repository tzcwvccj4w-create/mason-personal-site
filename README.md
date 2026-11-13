# Mason Personal Site V2.4

李彦熙（Mason Li）的中英双语独立个人介绍网站，未来用于二维码和 NFC 访问。

网站采用三段式结构：

- 认识我
- 我做过的事
- 找到我

## 目录结构

```text
.
├── index.html   # 网站首页，CSS、交互脚本、人物照片与社交二维码均已内嵌
├── README.md    # 项目与部署说明
└── .gitignore   # 本地缓存和无关文件排除规则
```

这是一个无框架、无后端依赖的静态网站。页面资源均包含在 `index.html` 中；作品、文章、旅行和音乐链接会跳转到相应的外部平台。

网站支持中文与英文切换，会记住访客最近选择的语言；首次访问时会参考浏览器语言显示中文或英文。

## 本地查看

直接用 Safari、Chrome、Edge 或 Firefox 打开根目录的 `index.html`。

## 更新网站

1. 修改根目录的 `index.html`。
2. 分别检查电脑和手机尺寸下的页面显示。
3. 确认图片、按钮和外部链接正常。
4. 提交并推送到 `main` 分支。

## Cloudflare Pages 部署准备

在 Cloudflare Pages 中连接本仓库，并填写：

- GitHub 仓库：`tzcwvccj4w-create/mason-personal-site`
- Production branch：`main`
- Framework preset：`None`
- Build command：留空（如界面要求填写，可使用 `exit 0`）
- Build output directory：`.`
- Root directory：留空，使用仓库根目录

仓库根目录已包含 `index.html`，不需要安装依赖或运行构建程序。

## 隐私说明

公开版本不包含手机号码、微信号和 QQ 邮箱；联系邮箱仅保留 `liyanximason@gmail.com`。

## 版本

当前版本：V2.4

# GitHub Pages 单页说明

这是一个可直接发布到 GitHub Pages 的单页模板，适合做简洁的专题介绍页、购买决策页或说明型落地页。

页面特点：

- 单文件结构，直接复制 `index.html` 即可使用
- 纯静态页面，无需安装依赖
- 适合在 GitHub Pages、静态托管或自定义域名下发布
- 已包含基础标题、描述、结构化数据和页面交互

## 文件结构

```text
github-pages-chatgpt-landing/
├── index.html
└── README.md
```

## 使用方式

如果你使用的是个人 GitHub Pages 仓库：

```text
https://github.com/yourname/yourname.github.io
```

把 `index.html` 放到仓库根目录即可。

如果你使用的是项目仓库 Pages，例如：

```text
https://yourname.github.io/project-name/
```

请记得同步更新页面中的网址配置。

## 发布前需要修改

打开 `index.html`，将以下内容改成你自己的实际信息：

1. 页面正式访问地址
2. 页面中的对外跳转链接
3. 页面中的来源参数或统计参数

如果你后续绑定了自定义域名，例如：

```text
https://guide.example.com/
```

也请把页面中的 `github.io` 地址一并替换为正式域名。

## GitHub Pages 发布步骤

1. 创建或进入 GitHub 仓库
2. 上传 `index.html`
3. 提交到默认分支
4. 在仓库 `Settings -> Pages` 中启用 Pages
5. 等待几分钟后访问线上地址

## 适合怎么用

这份单页模板更适合：

- 做独立专题页
- 做产品介绍页
- 做购买方案对比页
- 做简洁的品牌承接页

如果你想继续扩展，也可以在后面补充：

- `robots.txt`
- `sitemap.xml`
- `CNAME`
- 更多子页面

## 提示

- 页面上线后，请先检查标题、描述、链接和按钮是否都已替换正确
- 如果你修改了域名，记得同步检查 `canonical`、`og:url` 和结构化数据中的地址
- 发布完成后，建议先自己完整点一遍页面，确认展示和跳转都正常


# 个人主页

纯 HTML / CSS 学术个人主页，无需安装依赖或构建。采用窄版文字排版、纯白背景和深蓝链接，旧 Hexo 文章保留原路径。

布局参考 https://jiajunwu.com/ 与 https://tairanhe.com/ ，未使用参考网站的个人资料、论文或图片。主页采用全英文内容，背景为纯白 `#ffffff`。

## 本地预览

在仓库目录运行 `python3 -m http.server 8000`，浏览器打开 http://localhost:8000 。

## 内容修改

- `index.html`：姓名、介绍、专业背景、项目与联系链接。个人简介、教育经历和邮箱已填写；尚未提供的论文信息保留占位文案。
- `css/home.css`：配色、布局与手机适配。
- 当前联系链接使用已知 GitHub 账号 `xiaoxiaoabo`；更换账号后请同步更新。

## 发布

将变更推送到 `main`。仓库 Settings → Pages 设置为 Deploy from a branch、main、/(root)。

## 关于 yiboyuan.github.io

GitHub 用户或组织主页的域名必须对应账号名。要使用 `yiboyuan.github.io`，需要拥有 `yiboyuan` 用户或组织，并在其中创建或迁移为 `yiboyuan.github.io` 仓库，再启用 Pages。是否可注册该名称需要在 GitHub 确认。仅修改当前仓库名称或添加 CNAME 不会取得该域名。

官方说明：https://docs.github.com/en/pages/getting-started-with-github-pages/what-is-github-pages

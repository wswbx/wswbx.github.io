# Boxiao Wang | 王博霄 - Personal Homepage

这是基于 [AcadHomepage](https://github.com/RayeRen/acad-homepage.github.io) 与 [jinzhuoran.github.io](https://github.com/jinzhuoran/jinzhuoran.github.io) 制作的个人学术主页。

部署地址：[https://wswbx.github.io/](https://wswbx.github.io/)

## 已完成

- 更新姓名、研究简介、学校、公开邮箱、Google Scholar 与 DBLP。
- 重写研究方向、英文新闻、论文、简洁的实习与项目经历、教育经历、荣誉和技能。
- 加入 PiT-PO 与 DrSR 的论文链接，以及 PiT-PO 的开源代码链接。
- 新增响应式研究卡片、论文卡片、时间线和移动端样式。
- 使用本人西装照作为头像，并为 PiT-PO 增加 KDD 2026 海报视觉卡片。
- 未在网页中公开手机号，也未复制带手机号的简历 PDF。

## 本地预览

安装 Ruby 与 Bundler 后运行：

```bash
bundle install
bundle exec jekyll serve
```

随后访问 <http://127.0.0.1:4000>。

## GitHub Pages 发布

本仓库通过 `main` 分支根目录发布。在仓库的 **Settings → Pages** 中选择 **Deploy from a branch**、`main` 与 `/(root)` 即可。

## 内容入口

- 网站资料：`_config.yml`
- 主页正文：`_pages/about.md`
- 自定义样式：`assets/css/main.scss`
- 头像：`images/boxiao-wang.png`
- PiT-PO 海报：`images/publication/pit-po-kdd-2026-poster.png`

## Attribution

This site preserves the original MIT license and is based on AcadHomepage, which in turn incorporates components from Minimal Mistakes and Academic Pages.

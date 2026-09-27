# Minimal Light 默认预览

本站用于预览 Minimal Light 学术主页模板，保留上游示例姓名、简介、论文和栏目，尚未填写个人资料。

- 网站地址：https://shuang-sec.github.io/
- 模板来源：https://github.com/yaoyao-liu/minimal-light
- 使用上游提供的 `html_source_file` 静态版本。
- 授权文件见 `LICENSE`。

## 本次调整

将 canonical 地址改为本站地址，移除模板作者的 Google Analytics 代码，并将视口辅助脚本改为相对路径。其余示例正文保留。

## 修改与预览

内容在 `index.html` 中，样式、图片、脚本和简历示例放在 `assets/`。在仓库根目录运行：

```bash
python3 -m http.server 8000 --bind 127.0.0.1
```

浏览器打开 `http://127.0.0.1:8000/`。后续如需 Markdown 和 YAML 编辑方式，可再切换为上游 Jekyll 源码版本。

## 发布方式

GitHub Pages 从 `main` 分支根目录发布。`.nojekyll` 表明文件已经是静态产物；无需自定义构建工作流。GitHub 平台仍会执行 Pages 自带部署流程。

## 回退

后续内容修改可通过 Git revert 回退到本次默认模板提交。本站使用独立仓库，原有 `dignity666.github.io` 仓库继续保留。

最后核验日期：2026-09-27。

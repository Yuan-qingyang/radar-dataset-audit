# 车载雷达数据验收台

单文件静态页面，源码在 `index.html`。

## 修改方式

直接修改 `index.html`（HTML / CSS / JS 都在这一个文件里），然后 commit 并 push 到 `main` 分支。`.github/workflows/deploy-pages.yml` 会自动把最新内容部署到 GitHub Pages，不需要手动发布。

线上地址：https://nanoandluna.github.io/radar-dataset-audit/

## 注意事项

- 页面内的数据保存在访问者浏览器的 `localStorage`，不会跨设备同步。
- 页面里的外部链接只作参考，不依赖它们加载页面。

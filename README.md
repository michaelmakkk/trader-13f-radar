# 大佬最新持仓雷达

这是一个可直接发布到 GitHub Pages 的静态网页，用来跟踪投资大佬和相关机构的季度 13F 持仓。

## 文件

- `index.html`：完整网页，包含黑底信息图样式、数据和交互逻辑。
- `.nojekyll`：告诉 GitHub Pages 直接按静态文件发布。

## 发布到 GitHub Pages

1. 打开 GitHub，新建一个仓库，例如 `trader-13f-radar`。
2. 上传本文件夹里的 `index.html`、`README.md`、`.nojekyll`。
3. 进入仓库的 `Settings`。
4. 打开左侧 `Pages`。
5. 在 `Build and deployment` 里选择 `Deploy from a branch`。
6. Branch 选择 `main`，目录选择 `/root`，点 `Save`。
7. 等 1 到 3 分钟，GitHub 会生成一个类似这样的链接：

```text
https://你的GitHub用户名.github.io/trader-13f-radar/
```

## 更新数据

每个季度 13F 通常在季末后 45 天内披露。更新时直接编辑 `index.html` 里的 `managers` 数据即可。

下一轮重点更新日：

- Q2 2026：2026-08-14 附近
- Q3 2026：2026-11-14 附近
- Q4 2026：2027-02-14 附近

## 口径说明

页面使用公开 13F 信息和第三方聚合页整理。13F 有延迟，且不覆盖空头、现金、海外本地股票和多数衍生品。本页面仅用于资料整理和研究，不构成投资建议。

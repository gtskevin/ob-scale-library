# OB量表检索库

这是用于 GitHub Pages 发布的静态网页版本。

## 文件说明

- `index.html`：在线访问入口，也是完整的单文件离线版网页。
- `version.json`：当前发布版本信息，后续可用于“检查更新”。

## 发布方式

1. 在 GitHub 新建一个公开仓库，例如 `ob-scale-library`。
2. 上传本目录中的文件到仓库根目录。
3. 在仓库设置中打开 Pages，Source 选择 `Deploy from a branch`，Branch 选择 `main` 和 `/root`。
4. 发布后访问地址通常是 `https://<你的用户名>.github.io/<仓库名>/`。

## 更新方式

每次更新量表库后，重新生成 `index.html`，并同步更新 `version.json` 的版本号和说明，然后推送到 GitHub。

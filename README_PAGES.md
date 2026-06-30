# GitHub Pages 部署说明

本仓库可以直接作为 GitHub Pages 数据面板使用。

设置方式：

1. 进入 `biubiubiu_data` 仓库。
2. 打开 `Settings` → `Pages`。
3. `Source` 选择 `Deploy from a branch`。
4. `Branch` 选择 `main`，目录选择 `/ root`。
5. 保存后访问 `https://deerinwild.github.io/biubiubiu_data/`。

`index.html` 会读取：

```text
archive/summary/latest.json
```

该文件由新版 `biubiubiu_monitor/server.js` 在写入 GitHub 时自动维护。

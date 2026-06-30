# biubiubiu GitHub Pages 数据面板

将 `index.html` 放在 `biubiubiu_data` 仓库根目录，并在 GitHub 仓库 Settings → Pages 中选择 `main / root` 发布。

本版面板支持三种读取方式：

1. 打开页面时优先读取 `archive/summary/latest.json`。
2. 如果最新索引不存在或读取失败，可手动选择日期并点击“加载当天”，读取 `archive/counters/YYYY/MM/YYYY-MM-DD.json`。
3. 可点击“加载本月”，读取 `archive/summary/YYYY/YYYY-MM.json`。

因此，即使 Render 暂时还没有生成 `latest.json`，面板也不会完全不可用。

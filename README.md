# lyx 情报看板

由本地知识蒸馏流水线自动重建并推送。

- 数据源：3 个知识星球（工程芯一 / 击球区小能手 / 曹博士 Micro-LED）+ 14 层公开信源（Google News / 东财 / 启信宝 / Bing 等 WebFetch 替代）
- 维度：AI 基础设施 · 大模型算法 · 市场商业 · 工作相关
- 看板：`lyx-intel-board.html`（单文件、自包含 CSS+JS+数据）

由 `deploy_pages.sh` 在每次本地重建后自动 commit + push 同步。
<div align="center">

# shijianjs

[English](https://github.com/shijianjs/shijianjs/blob/main/README.md) | [简体中文](https://github.com/shijianjs/shijianjs/blob/main/README.zh-CN.md)

用 Rust 写 DuckDB 扩展，给 npm 包写 Kotlin/JS wrapper，顺手做了几个思源笔记插件。

[![Rust](https://img.shields.io/badge/Rust-000?logo=rust&logoColor=white)](https://github.com/shijianjs?tab=repositories&q=duckfn)
[![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?logo=kotlin&logoColor=white)](https://github.com/shijianjs?tab=repositories&q=ktjs)
[![DuckDB](https://img.shields.io/badge/DuckDB-FFF100?logo=duckdb&logoColor=black)](https://github.com/shijianjs?tab=repositories&q=duckfn)
[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)](https://github.com/shijianjs?tab=repositories&q=siyuan)

</div>

## DuckDB 扩展

- **[duckfn](https://github.com/shijianjs/duckfn)** — 用纯 Rust 写 DuckDB 扩展，不用 C++。 [文档](https://shijianjs.github.io/duckfn/) · [crates.io](https://crates.io/crates/duckfn)
- **[duckfn-kuva](https://github.com/shijianjs/duckfn-kuva)** — 一条 SQL 出一张 SVG 统计图，统计语义类似 seaborn / ggplot2，不需要 Python 或 R 环境。 [文档](https://shijianjs.github.io/duckfn-kuva/)
- **[duckfn-palette](https://github.com/shijianjs/duckfn-palette)** — 160 个颜色函数：44 个色彩空间、CSS Color Level 4、d3 调色板。 [文档](https://shijianjs.github.io/duckfn-palette/)
- **[duckfn-statrs](https://github.com/shijianjs/duckfn-statrs)** — 把 statrs 搬进 SQL：描述统计、分布、抽样、假设检验、特殊函数。 [文档](https://shijianjs.github.io/duckfn-statrs/)
- **[duckfn-quantstats](https://github.com/shijianjs/duckfn-quantstats)** — quantstats-rs 的 SQL 版，用来算量化回测指标。 [文档](https://shijianjs.github.io/duckfn-quantstats/)
- **[duckfn-open](https://github.com/shijianjs/duckfn-open)** — 在 SQL 里打开路径、URL 或查询结果，另有文件名清洗函数。 [文档](https://shijianjs.github.io/duckfn-open/)

## Kotlin/JS wrappers

- **[ktjs-vaadin](https://github.com/shijianjs/ktjs-vaadin)** — Vaadin 免费 Web Components 的 Kotlin 封装：65 个 npm 包、92 个自定义元素。 [演示](https://shijianjs.github.io/ktjs-vaadin/)
- **[ktjs-echarts](https://github.com/shijianjs/ktjs-echarts)** — echarts 生态的 Kotlin/JS wrapper，另有 ECharts option 的 multiplatform 数据模型。 [演示](https://shijianjs.github.io/ktjs-echarts/) · [API](https://shijianjs.github.io/ktjs-echarts/api/)
- **[ktjs-iconify](https://github.com/shijianjs/ktjs-iconify)** — Iconify 生态（types / utils / tools / iconify-icon）的 Kotlin/JS wrapper。

## 思源笔记插件

- **[siyuan-plugin-markmap-view](https://github.com/shijianjs/siyuan-plugin-markmap-view)** [![stars](https://img.shields.io/github/stars/shijianjs/siyuan-plugin-markmap-view?style=flat)](https://github.com/shijianjs/siyuan-plugin-markmap-view/stargazers) — 把当前笔记用思维导图展示。
- **[siyuan-plugin-iconify-emoji](https://github.com/shijianjs/siyuan-plugin-iconify-emoji)** [![stars](https://img.shields.io/github/stars/shijianjs/siyuan-plugin-iconify-emoji?style=flat)](https://github.com/shijianjs/siyuan-plugin-iconify-emoji/stargazers) — 在思源 emoji 面板里用 Iconify 的 20 万+ 图标。

## 自用工具

- **[maven-central-publishing](https://github.com/shijianjs/maven-central-publishing)** — 自用的发布中枢：几个项目的归档登记到一处，去重后合并成一次 Maven Central 部署，不负责编译。
- **[dev-agent-skills](https://github.com/shijianjs/dev-agent-skills)** — 自用的 Agent Skills 集合，`npx skills add shijianjs/dev-agent-skills` 安装。
- **[userscripts](https://github.com/shijianjs/userscripts)** — 自用的油猴脚本和 Stylus 样式，带 Playwright 验证用例。

<div align="center">

# shijianjs

写 **DuckDB 扩展**、**Kotlin/JS wrapper**，还有一些**思源笔记插件**。

[![Rust](https://img.shields.io/badge/Rust-000?logo=rust&logoColor=white)](https://github.com/shijianjs?tab=repositories&q=duckfn)
[![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?logo=kotlin&logoColor=white)](https://github.com/shijianjs?tab=repositories&q=ktjs)
[![DuckDB](https://img.shields.io/badge/DuckDB-FFF100?logo=duckdb&logoColor=black)](https://github.com/shijianjs?tab=repositories&q=duckfn)
[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)](https://github.com/shijianjs?tab=repositories&q=siyuan)

</div>

## 🦆 DuckDB extensions

用 Rust 写的 DuckDB 可加载扩展，都能从 DuckDB 官方社区扩展仓库直接 `INSTALL`。

| 项目 | 一句话 |
| --- | --- |
| [**duckfn**](https://github.com/shijianjs/duckfn) | 用纯 Rust 写 DuckDB 扩展的框架，不碰 C++。<br>[文档](https://shijianjs.github.io/duckfn/) · [crates.io](https://crates.io/crates/duckfn) |
| [**duckfn-kuva**](https://github.com/shijianjs/duckfn-kuva) | 一条 SQL 出一张统计图：把图表描述渲染成 SVG，统计语义跟 seaborn / ggplot2 一致，但不需要 Python 或 R。<br>[示例](https://shijianjs.github.io/duckfn-kuva/) |
| [**duckfn-palette**](https://github.com/shijianjs/duckfn-palette) | 160 个颜色函数：44 个色彩空间、CSS Color Level 4 解析与输出、d3 调色板。<br>[示例](https://shijianjs.github.io/duckfn-palette/) |
| [**duckfn-statrs**](https://github.com/shijianjs/duckfn-statrs) | 把 Rust 的 statrs 搬进 SQL：描述统计、分布、抽样、假设检验、特殊函数。<br>[示例](https://shijianjs.github.io/duckfn-statrs/) |
| [**duckfn-quantstats**](https://github.com/shijianjs/duckfn-quantstats) | quantstats-rs 的 SQL 封装，在查询里直接算量化回测指标。<br>[示例](https://shijianjs.github.io/duckfn-quantstats/) |
| [**duckfn-open**](https://github.com/shijianjs/duckfn-open) | 从 SQL 打开路径、URL 或查询结果，附带文件名清洗函数。<br>[示例](https://shijianjs.github.io/duckfn-open/) |

## 🟪 Kotlin/JS wrappers

把 npm 生态包装成类型安全的 Kotlin：一个 Gradle 模块对应一组上游包，发布到 Maven Central。

| 项目 | 一句话 |
| --- | --- |
| [**ktjs-vaadin**](https://github.com/shijianjs/ktjs-vaadin) | 免费的 Vaadin Web Components 的 Kotlin 封装：65 个 npm 包、92 个自定义元素。<br>[演示](https://shijianjs.github.io/ktjs-vaadin/) |
| [**ktjs-echarts**](https://github.com/shijianjs/ktjs-echarts) | echarts 生态的 Kotlin/JS wrapper，另有 ECharts option 的 multiplatform 数据模型。<br>[演示](https://shijianjs.github.io/ktjs-echarts/) · [API](https://shijianjs.github.io/ktjs-echarts/api/) |
| [**ktjs-iconify**](https://github.com/shijianjs/ktjs-iconify) | Iconify 生态（types / utils / tools / iconify-icon）的 Kotlin/JS wrapper。 |

## 📝 思源笔记插件

| 项目 | 一句话 |
| --- | --- |
| [**siyuan-plugin-markmap-view**](https://github.com/shijianjs/siyuan-plugin-markmap-view) | 把当前笔记渲染成可以展开收起的思维导图。 ⭐ 7 |
| [**siyuan-plugin-iconify-emoji**](https://github.com/shijianjs/siyuan-plugin-iconify-emoji) | 在思源的 emoji 面板里直接用 Iconify 的 20 万+ 图标。 ⭐ 3 |

## 🧰 工具

| 项目 | 一句话 |
| --- | --- |
| [**maven-central-publishing**](https://github.com/shijianjs/maven-central-publishing) | Maven Central 发布中枢：各项目登记归档，去重合并后一次上传，不做编译。 |
| [**dev-agent-skills**](https://github.com/shijianjs/dev-agent-skills) | 自用的 Agent Skills 集合，`npx skills add` 即可安装。 |
| [**userscripts**](https://github.com/shijianjs/userscripts) | 自用的油猴脚本和 Stylus 用户样式，带 Playwright 验证用例。 |

<div align="center"><sub>除特别说明外均为 MIT 许可 · 发现问题欢迎开 issue</sub></div>

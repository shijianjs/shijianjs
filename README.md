<div align="center">

# shijianjs

[English](https://github.com/shijianjs/shijianjs/blob/main/README.md) | [简体中文](https://github.com/shijianjs/shijianjs/blob/main/README.zh-CN.md)

Rust extensions for DuckDB, Kotlin/JS wrappers for npm packages, a few SiYuan plugins.

[![Rust](https://img.shields.io/badge/Rust-000?logo=rust&logoColor=white)](https://github.com/shijianjs?tab=repositories&q=duckfn)
[![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?logo=kotlin&logoColor=white)](https://github.com/shijianjs?tab=repositories&q=ktjs)
[![DuckDB](https://img.shields.io/badge/DuckDB-FFF100?logo=duckdb&logoColor=black)](https://github.com/shijianjs?tab=repositories&q=duckfn)
[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)](https://github.com/shijianjs?tab=repositories&q=siyuan)

</div>

## DuckDB extensions

| Project | Description | Links |
| --- | --- | --- |
| **[duckfn](https://github.com/shijianjs/duckfn)** | Write DuckDB loadable extensions in plain Rust, no C++ build. | [Docs](https://shijianjs.github.io/duckfn/) · [crates.io](https://crates.io/crates/duckfn) |
| **[duckfn-kuva](https://github.com/shijianjs/duckfn-kuva)** | Draw statistical charts as SVG from SQL. The semantics are similar to seaborn / ggplot2, with no Python or R runtime. | [Docs](https://shijianjs.github.io/duckfn-kuva/) |
| **[duckfn-palette](https://github.com/shijianjs/duckfn-palette)** | 160 color functions: 44 color spaces, CSS Color Level 4 strings, d3 palettes. | [Docs](https://shijianjs.github.io/duckfn-palette/) |
| **[duckfn-statrs](https://github.com/shijianjs/duckfn-statrs)** | statrs in SQL: descriptive statistics, distributions, sampling, hypothesis tests, special functions. | [Docs](https://shijianjs.github.io/duckfn-statrs/) |
| **[duckfn-quantstats](https://github.com/shijianjs/duckfn-quantstats)** | quantstats-rs as SQL functions for backtest metrics. | [Docs](https://shijianjs.github.io/duckfn-quantstats/) |
| **[duckfn-open](https://github.com/shijianjs/duckfn-open)** | Open a path, a URL, or query output from SQL; also sanitizes filenames. | [Docs](https://shijianjs.github.io/duckfn-open/) |

## Kotlin/JS wrappers

| Project | Description | Links |
| --- | --- | --- |
| **[ktjs-vaadin](https://github.com/shijianjs/ktjs-vaadin)** | Kotlin wrappers for the free Vaadin Web Components: 65 npm packages, 92 custom elements. | [Demo](https://shijianjs.github.io/ktjs-vaadin/) |
| **[ktjs-echarts](https://github.com/shijianjs/ktjs-echarts)** | Kotlin/JS wrappers for the echarts ecosystem, plus a Kotlin Multiplatform model of the ECharts option schema. | [Demo](https://shijianjs.github.io/ktjs-echarts/) · [API](https://shijianjs.github.io/ktjs-echarts/api/) |
| **[ktjs-iconify](https://github.com/shijianjs/ktjs-iconify)** | Kotlin/JS wrappers for @iconify/types, @iconify/utils, @iconify/tools and iconify-icon. | — |

## SiYuan plugins

| Project | Description | Links |
| --- | --- | --- |
| **[siyuan-plugin-markmap-view](https://github.com/shijianjs/siyuan-plugin-markmap-view)** | Show the current note as a markmap mind map. | [![stars](https://img.shields.io/github/stars/shijianjs/siyuan-plugin-markmap-view?style=flat)](https://github.com/shijianjs/siyuan-plugin-markmap-view/stargazers) |
| **[siyuan-plugin-iconify-emoji](https://github.com/shijianjs/siyuan-plugin-iconify-emoji)** | Use Iconify's 200k+ open-source icons in SiYuan's emoji picker. | [![stars](https://img.shields.io/github/stars/shijianjs/siyuan-plugin-iconify-emoji?style=flat)](https://github.com/shijianjs/siyuan-plugin-iconify-emoji/stargazers) |

## Tools I use myself

| Project | Description | Links |
| --- | --- | --- |
| **[maven-central-publishing](https://github.com/shijianjs/maven-central-publishing)** | My release hub: projects register their archives, it drops duplicates and uploads one Maven Central bundle. It builds nothing. | — |
| **[dev-agent-skills](https://github.com/shijianjs/dev-agent-skills)** | My Agent Skills collection; install with `npx skills add shijianjs/dev-agent-skills`. | — |
| **[userscripts](https://github.com/shijianjs/userscripts)** | Tampermonkey scripts and Stylus styles I use, with Playwright checks. | — |

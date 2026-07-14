# nathan-peng.github.io | 个人技术博客

<p align="center">
  <a href="https://nathan-peng.github.io/" target="_blank">
    <img src="https://img.shields.io/badge/🌐 在线访问-Website-%232563eb?style=for-the-badge" alt="在线站点">
  </a>
  <a href="https://pages.github.com/" target="_blank">
    <img src="https://img.shields.io/badge/☁️ 部署平台-GitHub%20Pages-%23181717?style=for-the-badge" alt="部署方式">
  </a>
  <a href="https://stats.uptimerobot.com/yyjrwonmLz" target="_blank" title="点击查看完整站点监控统计">
    <img src="https://img.shields.io/uptimerobot/status/m803446945-df48741faa8606b0e9fab561?style=for-the-badge&label=🟢站点运行状态&labelColor=%23008E87" alt="站点运行状态">
  </a>
  <a href="https://stats.uptimerobot.com/yyjrwonmLz" target="_blank" title="点击查看完整站点监控统计">
    <img src="https://img.shields.io/uptimerobot/ratio/m803446945-df48741faa8606b0e9fab561?style=for-the-badge&label=📊30天可用率&labelColor=%23008E87" alt="30天可用率">
  </a>
  <img src="https://img.shields.io/badge/🔧 项目状态-本地重构中-%23f97316?style=for-the-badge" alt="项目状态">
  <img src="https://img.shields.io/badge/📅 最后更新-2026.07.14-%2306b6d4?style=for-the-badge" alt="最后更新日期">
</p>

## 📖 简介
本仓库为个人技术博客完整源码仓库，依托 [GitHub Pages](https://pages.github.com/) 实现静态站点全自动构建与托管。
**在线站点：[https://nathan-peng.github.io/](https://nathan-peng.github.io/)**

当前线上运行版本：**原生极简单页 HTML**，无框架、无标准化博客体系，拓展性与可维护性受限。

## ⚠️ 重要升级预告（近期上线）
全站重构开发、功能调试均在本地完成，暂未推送远程仓库；
即将全面升级为 **[Hugo](https://gohugo.io/) + [PaperMod](https://github.com/adityatelange/hugo-PaperMod)** 现代化静态博客架构，复核完毕后数日内合并至主分支并自动发布。

### ✨ 本次升级核心亮点
1. **🏗️ 全站架构规范化重构**
- 彻底抛弃单一HTML裸站结构，搭建结构清晰、长期可迭代的 Hugo 工程目录；
- 全站统一 Header 导航与 Footer 页脚，视觉风格一致；
- 首页采用完全自定义布局，脱离主题默认模板，兼顾个性化与全站统一性。

2. **📑 外部文档实时同步**
- 新增独立页面路由：`/about-repo/`、`/intro/`；
- 依托 Hugo 远程资源能力，直接拉取并渲染外部公开仓库 `README.md`；
- 文档外置仓库独立维护，远端更新即时生效，无需改动本站源码、重新部署。

3. **🎯 全局前端体验静默优化**
全站页面统一嵌入两套官方横幅脚本，静默加载不干扰内容阅读：
- 顶部：[KeepAndroidOpen](https://keepandroidopen.org/) 迷你中文公告横幅；
- 底部：[Browser-Update](https://browser-update.org/) 浏览器版本检测横幅，兼容老旧浏览器访问。

### 📊 新旧版本对比
| 版本 | 架构说明 | 核心能力 |
| :--- | :--- | :--- |
| 旧版（线上） | 纯静态单HTML页面 | 仅基础展示，无搜索、归档、评论、统计，难以迭代 |
| 新版（待上线） | Hugo + PaperMod 标准博客架构 | 归档/标签/全文搜索/代码高亮/明暗主题/访问统计/[Giscus评论](https://giscus.app/)，支持一键自动化部署 |

## 📅 上线说明
1. 本次为底层架构迭代，**原有站点内容完整保留，无清空、无重置**；
2. 域名、全部外部访问链接保持不变，不存在页面失效、访问断层；
3. 全部功能本地自测通过，近期推送代码后由 GitHub Pages 自动构建发布。

## 🚀 后续长期规划
架构正式上线稳定后：
- 持续更新技术文章与学习笔记；
- 按需微调页面样式、横幅展示逻辑与远程文档加载策略；
- 长期维护迭代，不断优化全站浏览体验。

> 最后更新：2026-07-14

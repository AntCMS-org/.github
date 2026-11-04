<div align="center">

# AntCMS

[![GitHub Downloads](https://img.shields.io/github/downloads/AntCMS-Org/AntCMS/total)](https://github.com/AntCMS-org/AntCMS/releases)
[![CI Status](https://img.shields.io/github/actions/workflow/status/AntCMS-Org/AntCMS/ci.yml)](https://github.com/AntCMS-org/AntCMS/actions/workflows/ci.yml)
[![License](https://img.shields.io/github/license/AntCMS-Org/AntCMS)](https://github.com/AntCMS-org/AntCMS/blob/main/LICENCE.md)
[![Stars](https://img.shields.io/github/stars/AntCMS-Org/AntCMS)](https://github.com/AntCMS-org/AntCMS/stargazers)

**A super lightweight, flat-file CMS built for the modern web.**

[Website](https://antcms.org/) · [Report an Issue](https://github.com/AntCMS-org/AntCMS/issues) · [Contributing](https://github.com/AntCMS-org/AntCMS)

</div>

---

## About

AntCMS is a flat-file CMS designed to use minimal system resources while delivering website speeds that rival a static site. Your content is just plain Markdown files on disk — **no database required**.

Write your pages in Markdown, configure the infrequent details in YAML, and let AntCMS handle the rest. Out of the box it will automatically generate your sitemap and `robots.txt`, compress your images, and serve your assets with efficient caching — no configuration needed.

## Features

- 🗄️ **Flat-file architecture** — content lives in Markdown files, no database to install or maintain
- ⚡ **Blazing fast** — performance rivaling a static site, with zero tuning required
- 📦 **Built-in compression** — gzip, Brotli, and zstd support for text-based assets (HTML, CSS, JS)
- 🖼️ **Automatic image compression** — JPEG, PNG, and WEBP optimized without lifting a finger
- 🔍 **Easy SEO** — automatic `robots.txt` and sitemap generation
- 🗂️ **Smart caching** — automatic ETags so returning visitors load pages faster
- 🎨 **Custom themes** — with per-theme styling for rendered Markdown content
- 🔌 **Plugin support** — extend AntCMS however you need

## Getting Started

AntCMS requires **PHP 8.4+** with the `curl`, `dom`, and `mbstring` extensions.

For the best performance, also install `opcache`, `zstd`, `brotli`, `zlib`, and `gd`. See the [AntCMS readme](https://github.com/AntCMS-org/AntCMS#readme) for full details.

> **Note:** AntCMS is currently preview software and is being actively rebuilt. Some planned functionality — including the admin UI and user management — is not yet available.

## Plugins

| Plugin | Description |
| ------ | ----------- |
| [GitHub-Sync](https://github.com/AntCMS-org/GitHub-Sync) | Publish your site content to a GitHub repository and have it automatically pulled back down as your content source |
| [Example-Plugin](https://github.com/AntCMS-org/Example-Plugin) | A showcase plugin for developers learning how to build their own custom plugins |

## Themes

| Theme | Description |
| ----- | ----------- |
| [Default-Old](https://github.com/AntCMS-org/Default-Old) | The previous default AntCMS theme, kept available for download |

## Repository

| Repository | Description |
| ---------- | ----------- |
| [AntCMS](https://github.com/AntCMS-org/AntCMS) | The core CMS |
| [.github](https://github.com/AntCMS-org/.github) | This organization profile |

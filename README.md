# Japan Foreigner Job Nav

> Sorry, an English version is planned but not ready yet. Please use your browser's built-in translation feature to read the site in English for now. (｡•́︿•̀｡)

Please feel free to suggest new job websites, career platforms, official resources, or corrections via [Issues](../../issues).<br>
欢迎大家通过 [Issues](../../issues) 踊跃投稿新的招聘网站、求职平台、官方入口或需要修正的信息。<br>
新しい求人サイト、就活サービス、公的窓口、修正すべき情報があれば、ぜひ [Issues](../../issues) から投稿してください。

## Contents / 目录 / 目次

- [Contribution Ideas / 投稿歓迎](#contribution-ideas--投稿歓迎)
- [Project Overview](#project-overview)
- [项目介绍](#项目介绍)
- [プロジェクト概要](#プロジェクト概要)
- [Local Usage / 本地使用 / ローカルで見る](#local-usage--本地使用--ローカルで見る)

## Contribution Ideas / 投稿歓迎

When opening an Issue, please include as much of the following as possible.<br>
Issues 投稿时，建议尽量包含以下信息。<br>
Issue には、可能な範囲で以下の情報を書いてください。

- Service name / 网站名称 / サービス名
- Official URL / 官网 URL / 公式 URL
- Target users / 适合人群 / 想定ユーザー
- Supported languages / 语言支持 / 対応言語
- Use case: foreign residents, bilingual talent, new graduates, career changers, IT, part-time work, Specified Skilled Worker, etc.
- Notes, risks, or corrections / 注意点、风险或修正信息 / 注意点や修正すべき情報

## Project Overview

Japan Foreigner Job Nav is a curated navigation site for people looking for work in Japan, especially foreign residents, bilingual talent, Chinese-speaking job seekers, and people exploring Japanese domestic career platforms.

The project organizes:

- Foreigner-friendly job platforms
- Bilingual, English-speaking, and global-company job sites
- Chinese-speaking community and job channels
- Japanese domestic career-change platforms and recruitment agents
- IT job boards, bilingual recruiters, and public employment services
- A Japanese subpage for new graduates aiming for global companies, consulting, finance, returnee hiring, overseas university backgrounds, and bilingual roles

The main page is `index.html`. It is primarily written in Chinese and supports search, category filters, local favorites, link copying, and direct links to official websites. Platform data is maintained in `data/platforms.js` so that the main page and subpages can share the same source of truth.

Current pages:

- `index.html`: Japan job platform navigation for foreign residents and multilingual job seekers
- `newgrad-gaishi.html`: Japanese navigation page for new graduates aiming for global companies, returnee hiring, overseas university backgrounds, and bilingual careers

## 项目介绍

这是一个面向在日本求职者的招聘平台导航项目，重点整理：

- 外国人友好的求职平台
- 双语、英语、外资相关职位网站
- 中文圈求职渠道
- 日本本土转职平台和 Agent
- IT、猎头、官方公共就业入口
- 面向外资、咨询、金融和归国/海外大新卒的日语子页面

主页面是 `index.html`，以中文为主，提供搜索、分类筛选、收藏、复制链接和官网跳转功能。平台数据集中维护在 `data/platforms.js`，方便主页面和子页面复用。

当前包含的页面：

- `index.html`: 日本外国人招聘平台导航
- `newgrad-gaishi.html`: 面向想进外资的日本新卒、归国子女、海外大和双语学生的日语导航页

## プロジェクト概要

このプロジェクトは、日本で仕事を探す外国人、バイリンガル人材、中国語圏の求職者、日本国内で転職したい人向けの求人・就職サービスナビです。

主に以下のような情報を整理しています。

- 外国人向け求人サイト
- バイリンガル・英語・外資系求人サービス
- 中国語圏コミュニティや求人チャネル
- 日本国内の転職サイト・転職エージェント
- IT、ヘッドハンター、公的就職支援窓口
- 外資系企業、コンサル、金融、帰国子女、海外大生、バイリンガル新卒向けの就活サービス

メインページは `index.html` です。検索、カテゴリ絞り込み、お気に入り、リンクコピー、公式サイトへの移動ができます。サービス情報は `data/platforms.js` にまとめており、メインページと子ページで共通利用しています。

現在のページ:

- `index.html`: 日本外国人招聘平台导航
- `newgrad-gaishi.html`: 外資系企業を目指す新卒向け就活サービスナビ

## Local Usage / 本地使用 / ローカルで見る

Open `index.html` directly in a browser.<br>
直接在浏览器中打开 `index.html`。<br>
ブラウザで `index.html` を直接開いてください。

Ensure that all of the following files are saved locally.<br>
请确保以下文件都保存在本地。<br>
以下のファイルがすべてローカルに保存されていることを確認してください。

```
index.html
newgrad-gaishi.html
data/platforms.js
```

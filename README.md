# 職務経歴書

リポジトリ: [https://github.com/glows/resume](https://github.com/glows/resume)

## 基本信息

|键|值|
|----|-------|
|姓名|罗东川(ラトウセン)/LUO DONGCHUAN/ra tousenn|
|生年月|1994.10|
|GitHub|[github](https://github.com/glows)|
|Twitter|[twitter](https://twitter.com/saphylie)|
|Blog|[https://glows.github.io/](https://glows.github.io/)|

## 概要

2015年8月下旬从重庆交通大学作为应届毕业工程师进入公司。

我的工作包括: 在基于 spring + vue.js + typescript 的内部框架中开发新功能，维护基于 struts 的内部自定义框架的 web 应用程序，在 pl/sql 和 jp1中批量维护和开发，大约有两年半的开发经验。日语、程序设计、礼仪都是在学习的同时应用的，体验着非常充实快乐的日子。

作为一名 web 应用工程师，我希望将来的工作能够围绕现代开发风格，利用技术来挑战大规模服务带来的挑战我想要更深入地体验 web 开发的技术堆栈，也想实践 ruby，node.js，aws，devops 等技术会。

我对编程语言技术、软件开发方法论等很感兴趣。除了技术，我喜欢吉他，科幻和滑雪。

## 技能 Skill スキル

### 语言

* 日本語:
  - N1: 144点/180点(2020年12月)
  - 敬語が大好きなので、正しく使えるように命をかけて頑張っています(上司に「ご苦労様」を使うこととか2度としたくないです！)
* 英語:
  - TOEIC: 935点(2021年2月)；835点(2017年)
  - ドキュメント、技術本などを読むこと、READMEなどを書くことができます
  - 簡単な日常会話ができます
  - 阅读文档，技术书籍等，写自述等
  - 简单的日常会话
* 汉語
  - 母语

### 编程语言

* Golang
* JavaScript
* TypeScript
* PL/SQL

### 框架

* React.js
* Gin/gRpc
* Vue.js

### 工具

* Git 日常使用
* VSCode 

<!-- ### 資格

* 応用情報技術者(2019年10月)
* RPA Developer Advanced(2019年12月) -->

### 其他

Couseraで複数のオンラインコースを修了したことがあります。認定番号は[LinkedIn](https://www.linkedin.com/in/monkeywzr/)で記載しております。

* **Programming Language Part A, B, C** SML、Racket、Rubyを使った、凄く面白いコースだと思います

最近はSwift/iOS開発を勉強しています。

### OSS Projects

* 个人博客 [https://github.com/glows/glows.github.io/](https://github.com/glows/glows.github.io)
  - Hugo + GitHub Pages + Github Action
  - 使用 src 分支管理博客源并且Github Action自动部署

## 工作经历

2018年8月新卒入社から2年半ぐらいの開発実務経験があります。

### 2018/8 - 2021/6 : ベース株式会社

職務: WEBアプリケーションエンジニア(客先常駐)

#### 新規WEBサービスの開発(2020.7 - 2020.12)

店頭、対面等オフライン方式で入会した会員のオンライン登録、及びログインID、パスワードの変更機能を提供するWEBアプリケーション

* Spring BootによるRESTful API + TypeScript + Vue.jsによるSPA + Orcaleデータベース
* 電話発信サービスTwilioの導入と誤送信防止対策、SPAサイトにおけるアナリティクスサービス(gtag、karte)の設置
* 詳細設計と実装を担当しました。下記の課題を解決しました
  - SpringのArgumentResolver、RequestBodyAdviceを使ってサーバ側のAPI項目共通バリデーション
  - Vue.jsのVuelidateのバリデーターを実装して入力フォームのカスタマイズバリデーション
  - TypeScriptの活用でソース闇に隠れているバグがコンパイル時に発見
  - etc.

#### PL/SQLバッチの保守と開発(2019.4 - 2020.6)

消費税増税に伴うデータ作成バッチの修正、新規値引き企画のデータ作成バッチグループの実装なとを担当しました

* PL/SQLによるプロシージャの新規/改修
* JP1によるジョブの運用管理

#### Vue.jsによる既存サイトのレスポンシブ共通化(2018.12 - 2019.4)

既存PCサイト、SPサイト、ネイティブアプリの共通化対応。1つの画面のVue実装と複数画面のバグ修正を担当しました。

* Vue.jsを初めて実務に使いました
* JavaScriptをよりよく理解し、Promiseのコールバックチーンの概念を習得しました

#### 複数既存WEBサービスの保守(2018.10 - 2019.4)

* Strutsベース、S2Clickベースの社内独自フレームワーク
* 画面テンプレート修正、Javaロジック修正とか簡単な作業を担当しました
* 人生初めての実務作業であり、Eclipse + Tomcatでプロジェクトのローカル環境構築が難しかった


## 自我推薦

我对技术有强烈的好奇心。我喜欢学习新的东西，深入探索到令人信服的地步。

从大学开始，我就一直在 github pages 上运用静态博客写个人博客，主要以学习笔记为内容。当我们将生成器工具从 hexo 迁移到 hugo 时，我们也将我们最喜欢的主题迁移到 hugo，并将其作为 oss 项目发布。我得到了很多明星，公关，非常有趣。

今后的目标是提高知识水平，突破瓶颈。具体来说，我想学习设计模式、 OOP 等软件开发方法论，以期能够编写出更好的质量代码。我希望我们可以在实践中阅读业务中的源代码，阅读 oss 项目中的源代码，思考应用哪些方法，需要什么样的重构等等。我想从 java、 typescript 等我最近熟悉的语言出发，学习类型系统、编译器、虚拟机等语言技术。

我希望与对技术充满热情的同事一起工作，在技术含量高的黑客环境中成长，为公司和技术社区贡献自己的热情。制作有趣的项目，参加技术研讨会，参加 oss 项目，结识各种各样的工程师，充分享受技术的乐趣。

## 我以后想做的事

### 业务内

* 基于 Go、Node.js + Typescript 等的服务器开发
* 基于 Ruby/Rails 开发WEB服务
* 利用 AWS 等灵活开发
* 现代开发，引入 DevOps 工具

### 业务外

* 网络技术学习
* 使用 Swift 开发 iOS 应用程序
* 使用 Rust 等新语言进行软件开发
* 在 Atcoder/LeetCode 中练习算法
* 学习类型系统、类型理论、编译器、 VM 等编程语言技术

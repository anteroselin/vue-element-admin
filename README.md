<p align="center">
  <img width="320" src="https://wpimg.wallstcn.com/ecc53a42-d79b-42e2-8852-5126b810a4c8.svg">
</p>

## Introduction

vue-element-admin is a production-ready front-end solution for admin interfaces. It is based on [vue](https://github.com/vuejs/vue) and uses the UI Toolkit [element-ui](https://github.com/ElemeFE/element).

vue-element-admin is based on the newest development stack of vue and it has a built-in i18n solution, typical templates for enterprise applications, and lots of awesome features. It helps you build large and complex Single-Page Applications. I believe whatever your needs are, this project will help you.

- Base template recommends using: vue-admin-template
- Desktop: electron-vue-admin
- Typescript: vue-typescript-admin-template
- awesome-project

**After the `v4.1.0+` version, the default master branch will not support i18n. Please use i18n Branch, it will keep up with the master update**

**The current version is `v4.0+` build on `vue-cli`. If you find a problem, please put issue. If you want to use the old version , you can switch branch to tag/3.11.0, it does not rely on `vue-cli`**

**This project does not support low version browsers (e.g. IE). Please add polyfill by yourself.**

## Preparation

You need to install [node](https://nodejs.org/) and [git](https://git-scm.com/) locally. The project is based on [ES2015+](https://es6.ruanyifeng.com/), [vue](https://cn.vuejs.org/index.html), [vuex](https://vuex.vuejs.org/zh-cn/), [vue-router](https://router.vuejs.org/zh-cn/), [vue-cli](https://github.com/vuejs/vue-cli) , [axios](https://github.com/axios/axios) and [element-ui](https://github.com/ElemeFE/element), all request data is simulated using [Mock.js](https://github.com/nuysoft/Mock).
Understanding and learning this knowledge in advance will greatly help the use of this project.

[![Edit on CodeSandbox](https://codesandbox.io/static/img/play-codesandbox.svg)](https://codesandbox.io/s/github/PanJiaChen/vue-element-admin/tree/CodeSandbox)

<p align="center">
  <img width="900" src="https://wpimg.wallstcn.com/a5894c1b-f6af-456e-82df-1151da0839bf.png">
</p>

## Sponsors

Become a sponsor and get your logo on our README on GitHub with a link to your site. [[Become a sponsor]](https://www.patreon.com/panjiachen)

### Akveo
<a href="https://store.akveo.com/products/vue-java-admin-dashboard-spring?utm_campaign=akveo_store-Vue-Vue_demo%2Fgithub&utm_source=vue_admin&utm_medium=referral&utm_content=github_banner"><img width="500px" src="https://raw.githubusercontent.com/PanJiaChen/vue-element-admin-site/master/docs/.vuepress/public/images/vue-java-banner.png" /></a><p>Get Java backend for Vue admin with 20% discount for 39$ use coupon code SWB0RAZPZR1M
</p>

### Flatlogic

<a href="https://flatlogic.com/admin-dashboards?from=vue-element-admin"><img width="150px" src="https://wpimg.wallstcn.com/9c0b719b-5551-4c1e-b776-63994632d94a.png" /></a><p>Admin Dashboard Templates made with Vue, React and Angular.</p>

## Features

```
- Login / Logout

- Permission Authentication
  - Page permission
  - Directive permission
  - Permission configuration page
  - Two-step login

- Multi-environment build
  - Develop (dev)
  - sit
  - Stage Test (stage)
  - Production (prod)

- Global Features
  - I18n
  - Multiple dynamic themes
  - Dynamic sidebar (supports multi-level routing)
  - Dynamic breadcrumb
  - Tags-view (Tab page Support right-click operation)
  - Svg Sprite
  - Mock data
  - Screenfull
  - Responsive Sidebar

- Editor
  - Rich Text Editor
  - Markdown Editor
  - JSON Editor

- Excel
  - Export Excel
  - Upload Excel
  - Visualization Excel
  - Export zip

- Table
  - Dynamic Table
  - Drag And Drop Table
  - Inline Edit Table

- Error Page
  - 401
  - 404

- Components
  - Avatar Upload
  - Back To Top
  - Drag Dialog
  - Drag Select
  - Drag Kanban
  - Drag List
  - SplitPane
  - Dropzone
  - Sticky
  - CountTo

- Advanced Example
- Error Log
- Dashboard
- Guide Page
- ECharts
- Clipboard
- Markdown to html
```

## Getting started

```bash
# clone the project
git clone https://github.com/PanJiaChen/vue-element-admin.git

# enter the project directory
cd vue-element-admin

# install dependency
npm install

# develop
npm run dev
```

This will automatically open http://localhost:9527

## Build

```bash
# build for test environment
npm run build:stage

# build for production environment
npm run build:prod
```

## Advanced

```bash
# preview the release environment effect
npm run preview

# preview the release environment effect + static resource analysis
npm run preview -- --report

# code format check
npm run lint

# code format check and auto fix
npm run lint -- --fix
```
Copyright (c) 2017-present Antero

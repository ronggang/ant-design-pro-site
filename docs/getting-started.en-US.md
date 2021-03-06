---
order: 0
title: Getting Started
type: Introduction
---

## Foreword

Ant Design Pro is a production-ready solution for admin interfaces. Continue on the design specifications brought by [Ant Design](http://ant.design/) and with the aim of building high-level components from the basics ones; we have developed templates, components, and corresponding design kit to improve the user and development experience for admin interfaces. 
With developers' feedback, we will increment, build and consolidate those templates and implementation, conclude best practices for components and business logic. Your help is much welcomed.
Bear those objectives in mind, we have built the following templates, and have built a scaffold based on React.js, which should help you prototyping production-ready admin interface.

```
- Dashboard
  - Analytic
  - Monitor
  - Workspace
- Form
  - Basic Form
  - Step Form
  - Advanced From
- List
  - Standard Table
  - Standard List
  - Card List
  - Search List (Project/Applications/Article)
- Profile
  - Simple Profile
  - Advanced Profile
- Result
  - Success
  - Failed
- Exception
  - 403
  - 404
  - 500
- User
  - Login
  - Register
  - Register Result
```

### For Designer

If you are product manager or designer, you can find the [design kit](/docs/resource) here.

### For Developer

We will walk you through the steps to get started.

## Preparation

You will needs [node](http://nodejs.org/) and [git](https://git-scm.com/). The project is based on [ES2015+](http://es6.ruanyifeng.com/), [React](http://facebook.github.io/react/), [dva](http://github.com/dvajs/dva), [g2](https://antv.alipay.com/g2/doc/index.html) and [antd](https://ant.design/docs/react/introduce). It would be helpful if you have pre-existing knowledge on those.

## Installation

There are three ways to install.

### Clone the Git Repository

```bash
$ git clone --depth=1 git@github.com:ant-design/ant-design-pro.git my-project
$ cd my-project
```

### Download the Package

Download [https://github.com/ant-design/ant-design-pro/archive/master.zip](https://github.com/ant-design/ant-design-pro/archive/master.zip), and un-archive.

### Use the Command Line

You can also use [ant-design-pro-cli](https://github.com/ant-design/ant-design-pro-cli).

```bash
$ npm install ant-design-pro-cli -g
$ mkdir my-project && cd my-project
$ pro init  # Initialize Scaffold
```

## Scaffolding

We have provided a scaffold for you, includes common routes for admins, the directory structure is presented below.

```bash
├── mock                     # Local Mock Data
├── public
│   ├── favicon.ico          # Favicon
│   └── index.html           # HTML Entry File
├── src
│   ├── common               # Common Configuration like Navigation
│   ├── components           # Components
│   ├── e2e                  # Integrated Test Case
│   ├── layouts              # Common Layouts
│   ├── models               # dva Model
│   ├── routes               # Sub-pages and templates
│   ├── services             # Back-end Services
│   ├── utils                # Utility
│   ├── g2.js                # Dataviz Configuration
│   ├── polyfill.js          # Polyfills
│   ├── theme.js             # Theme Configuration
│   ├── index.js             # App Entry
│   ├── index.less           # Global Stylesheet
│   └── router.js            # Route Entry File
├── tests                    # Tests Configuration
├── README.md
└── package.json
```

## Development

Install Dependencies

```bash
$ npm install
```

> If you encounter network issues, You may use [cnpm](https://cnpmjs.org/) as an alternative npm source commented out as it is most likely only relevant for users in China.

```bash
$ npm start
```

<img src="https://gw.alipayobjects.com/zos/rmsportal/DaIsSQRbNkwOXbMDhqEx.png" width="700" />

After it is done, it will automatically open [http://localhost:8000](http://localhost:8000). If you see the following page, you succeed.

<img src="https://gw.alipayobjects.com/zos/rmsportal/psqyFTiRoXQeaNZdjppA.png" width="700" alt="Screenshot" />

You're all set!
We have built-in models, standard components, mock data, hot module reloading, state management, i18n, global router, etc.
You can continue exploring other documents for more details on those topics.
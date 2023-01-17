# Notus NextJS <a href="https://twitter.com/intent/tweet?url=https%3A%2F%2Fdemos.creative-tim.com%2Fnotus-nextjs%2F&text=Start%20your%20development%20with%20a%20Free%20Tailwind%20CSS%20and%20NextJS%20UI%20Kit%20and%20Admin.%20Let%20Notus%20NextJS%20amaze%20you%20with%20its%20cool%20features%20and%20build%20tools%20and%20get%20your%20project%20to%20a%20whole%20new%20level." target="_blank">![Tweet](https://img.shields.io/twitter/url/http/shields.io.svg?style=social&logo=twitter)</a>

![version](https://img.shields.io/badge/version-1.1.0-blue.svg) ![license](https://img.shields.io/badge/license-MIT-blue.svg) <a href="https://github.com/creativetimofficial/notus-nextjs/issues?q=is%3Aopen+is%3Aissue" target="_blank">![GitHub issues open](https://img.shields.io/github/issues/creativetimofficial/notus-nextjs.svg)</a> <a href="https://github.com/creativetimofficial/notus-nextjs/issues?q=is%3Aissue+is%3Aclosed" target="_blank">![GitHub issues closed](https://img.shields.io/github/issues-closed-raw/creativetimofficial/notus-nextjs.svg)</a> <a href="https://gitter.im/creative-tim-general/Lobby" target="_blank">![Join the chat at https://gitter.im/NIT-dgp/General](https://badges.gitter.im/NIT-dgp/General.svg)</a> <a href="https://discord.gg/E4aHAQy" target="_blank">![Chat](https://img.shields.io/badge/chat-on%20discord-7289da.svg)</a>

### A beautiful UI Kit and Admin for Tailwind CSS and NextJS.

Start your development with a Free Tailwind CSS and NextJS UI Kit and Admin. Let Notus NextJS amaze you with its cool features and build tools and get your project to a whole new level.

Notus NextJS is Free and Open Source. It features multiple HTML and NextJS elements and it comes with dynamic components for NextJS.

It is based on [Tailwind Starter Kit] by James Smith, and it is build with both presentation pages, and pages for an admin dashboard.

Speed up your web development with a beautiful product made by James Smith.
If you like bright and fresh colors, you will love this Free Tailwind CSS Template! It features a huge number of components that can help you create amazing websites.

### Get Started

- Install NodeJS **LTS** version from <a href="https://nodejs.org/en/?ref=creativetim">NodeJs Official Page</a>
- Download the product on this page
- Unzip the downloaded file to a folder in your computer
- Open Terminal
- Go to your file project (where you’ve unzipped the product)
- (If you are on a linux based terminal) Simply run `npm run install:clean`
- (If not) Run in terminal `npm install`
- (If not) Run in terminal `npm run build:tailwind` (each time you add a new class, a class that does not exist in `src/assets/styles/tailwind.css`, you will need to run this command)
- (If not) Run in terminal `npm run dev`
- Navigate to https://localhost:3000
- Check more about [Tailwind CSS](https://tailwindcss.com)

### Pages

If you want to get inspiration or just show something directly to your clients,
you can jump start your development with our pre-built example pages. You will be able
to quickly set up the basic structure for your web project.


### Fully Coded Components

Notus NextJS is built with over frontend 120 components, giving you the freedom of choosing and combining. All components can take variations in colors, that you can easily modify using Tailwind CSS classes (NOTE: each time you add a new class, a class that does not exist in `src/assets/styles/tailwind.css`, you will need to compile again tailwind).

You will save a lot of time going from prototyping to full-functional code, because all elements are implemented.
This Free Tailwind CSS Template is coming with prebuilt examples, so the development process is seamless, switching from our pages to the real website is very easy to be done.

Every element has multiple states for colors, styles, hover, focus, that you can easily access and use.


### CSS Components

Notus NextJS comes with 120 Fully Coded CSS elements, such as [Alerts](https://www.creative-tim.com/learning-lab/tailwind/nextjs/alerts/notus?ref=nnjs-github-readme), [Buttons](https://www.creative-tim.com/learning-lab/tailwind/nextjs/buttons/notus?ref=nnjs-github-readme), [Inputs](https://www.creative-tim.com/learning-lab/tailwind/nextjs/inputs/notus?ref=nnjs-github-readme) and many more.

Please [check all of them here](https://www.creative-tim.com/learning-lab/tailwind/nextjs/alerts/notus?ref=nnjs-github-readme).

## Table of Contents

* [Versions](#versions)
* [Documentation](#documentation)
* [Quick Start](#quick-start)
* [Files and folders](#files-and-folders)
* [Browser Support](#browser-support)
* [Reporting Issues](#reporting-issues)
* [Licensing](#licensing)
* [Useful Links](#useful-links)
* [Resources](#resources)


## Quick start

- <a href="https://www.creative-tim.com/product/notus-nextjs?ref=nnjs-github-readme" target="_blank">Download from Creative Tim</a>.
- <a href="https://github.com/creativetimofficial/notus-nextjs" target="_blank">Check it on Github</a>.

## Files and Folder

This is the project structure that you will get upon the download:
```
notus-nextjs
.
├── CHANGELOG.md
├── ISSUE_TEMPLATE.md
├── LICENSE.md
├── README.md
├── assets
│   ├── img
│   │   ├── brand
│   │   │   └── favicon.ico
│   │   ├── github.svg
│   │   └── google.svg
│   └── styles
│       ├── index.css
│       └── tailwind.css
├── components
│   ├── Cards
│   │   ├── CardBarChart.js
│   │   ├── CardLineChart.js
│   │   ├── CardPageVisits.js
│   │   ├── CardProfile.js
│   │   ├── CardSettings.js
│   │   ├── CardSocialTraffic.js
│   │   ├── CardStats.js
│   │   └── CardTable.js
│   ├── Dropdowns
│   │   ├── IndexDropdown.js
│   │   ├── NotificationDropdown.js
│   │   ├── PagesDropdown.js
│   │   ├── TableDropdown.js
│   │   └── UserDropdown.js
│   ├── Footers
│   │   ├── Footer.js
│   │   ├── FooterAdmin.js
│   │   └── FooterSmall.js
│   ├── Headers
│   │   └── HeaderStats.js
│   ├── Maps
│   │   └── MapExample.js
│   ├── Navbars
│   │   ├── AdminNavbar.js
│   │   ├── AuthNavbar.js
│   │   └── IndexNavbar.js
│   ├── PageChange
│   │   └── PageChange.js
│   └── Sidebar
│       └── Sidebar.js
├── layouts
│   ├── Admin.js
│   └── Auth.js
├── next.config.js
├── package.json
├── pages
│   ├── 404.js
│   ├── _app.js
│   ├── _document.js
│   ├── _error.js
│   ├── admin
│   │   ├── dashboard.js
│   │   ├── maps.js
│   │   ├── settings.js
│   │   └── tables.js
│   ├── auth
│   │   ├── login.js
│   │   └── register.js
│   ├── index.js
│   ├── landing.js
│   └── profile.js
└── tailwind.config.js
```

## Reporting Issues

We use GitHub Issues as the official bug tracker for the Notus NextJS. Here are some advices for our users that want to report an issue:

1. Make sure that you are using the latest version of the Notus NextJS. Check the CHANGELOG from your dashboard on our <a href="https://www.creative-tim.com/?ref=nnjs-readme" target="_blank">website</a>.
2. Providing us reproducible steps for the issue will shorten the time it takes for it to be fixed.
3. Some issues may be browser specific, so specifying in what browser you encountered the issue might help.




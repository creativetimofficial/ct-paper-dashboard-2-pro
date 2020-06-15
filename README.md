# [Paper Dashboard 2 PRO](https://demos.creative-tim.com/paper-dashboard-2-pro/examples/dashboard.html)  


![version](https://img.shields.io/badge/version-2.3.1-blue.svg) [![GitHub issues open](https://img.shields.io/github/issues/creativetimofficial/material-kit.svg?maxAge=2592000)](https://github.com/creativetimofficial/ct-paper-dashboard-2-pro/issues?q=is%3Aopen+is%3Aissue) [![GitHub issues closed](https://img.shields.io/github/issues-closed-raw/creativetimofficial/ct-paper-dashboard-2-pro.svg?maxAge=2592000)](https://github.com/creativetimofficial/ct-paper-dashboard-2-pro/issues/issues?q=is%3Aissue+is%3Aclosed) [![Join the chat at https://gitter.im/NIT-dgp/General](https://badges.gitter.im/NIT-dgp/General.svg)](https://gitter.im/creative-tim-general/Lobby) [![Chat](https://img.shields.io/badge/chat-on%20discord-7289da.svg)](https://discord.gg/E4aHAQy)

![Paper Dashboard 2 PRO](https://s3.amazonaws.com/creativetim_bucket/products/84/original/opt_pd2p_thumbnail.jpg?1526481078)

We made it our priority to not add things that you don't need, so the  **[Paper Dashboard 2 PRO](https://demos.creative-tim.com/paper-dashboard-2-pro/examples/dashboard.html)** comes with just enough features for you to easily use. It combines multiple components and plugins and features numerous example of how it can be used. Inside the archive, you will also find multiple example pages to get you start or provide inspiration.

Paper Dashboard 2 PRO is the extended version of Paper Dashboard (https://www.creative-tim.com/product/paper-dashboard-2-pro). Based on feedback from people that downloaded and used it, we have added needed components and we have created multiple examples pages. We are curious to see how you want to use it and also improve it, so let us know any feedback you have.



## Table of Contents

* [Versions](#versions)
* [Demo](#demo)
* [Quick Start](#quick-start)
* [Documentation](#documentation)
* [File Structure](#file-structure)
* [Browser Support](#browser-support)
* [Resources](#resources)
* [Reporting Issues](#reporting-issues)
* [Licensing](#licensing)
* [Useful Links](#useful-links)


## Versions

[<img src="https://github.com/creativetimofficial/public-assets/blob/master/logos/html-logo.jpg?raw=true" width="60" height="60" />](https://www.creative-tim.com/product/paper-dashboard-2-pro)[<img src="https://github.com/creativetimofficial/public-assets/blob/master/logos/angular-logo.jpg?raw=true" width="60" height="60" />](https://www.creative-tim.com/product/paper-dashboard-pro-angular)[<img src="https://raw.githubusercontent.com/creativetimofficial/public-assets/master/logos/photoshop-logo.jpg" width="60" height="60" />](https://github.com/creativetimofficial/material-kit/tree/photoshop)

| HTML | Angular | React |
| --- | --- | --- |
| [![Paper Dashboard 2 Pro HTML](https://s3.amazonaws.com/creativetim_bucket/products/84/original/opt_pd2p_thumbnail.jpg?1526481078)](https://www.creative-tim.com/product/paper-dashboard-2-pro)  | [![Paper Dashboard Pro Angular](https://s3.amazonaws.com/creativetim_bucket/products/59/original/opt_pdp_angular_thumbnail.jpg?1551358278)](https://www.creative-tim.com/product/paper-dashboard-pro-angular) | [![Paper Dashboard Pro React](https://s3.amazonaws.com/creativetim_bucket/products/134/original/opt_pdp_react.jpg?1542215770)](https://www.creative-tim.com/product/paper-dashboard-pro-react)

## Demo

- [Start page](https://demos.creative-tim.com/paper-dashboard-2-pro/examples/dashboard.html)
- [User profile page](https://demos.creative-tim.com/paper-dashboard-2-pro/examples/pages/user.html)
- [Tables page ](https://demos.creative-tim.com/paper-dashboard-2-pro/examples/tables/extended.html)
- [Maps Page](https://demos.creative-tim.com/paper-dashboard-2-pro/examples/maps/google.html)
- [Notifications page](https://demos.creative-tim.com/paper-dashboard-2-pro/examples/components/notifications.html)

[View More](https://demos.creative-tim.com/paper-dashboard-2-pro/examples/dashboard.html).

## Quick start

We've also included an optional Gulp file to help you get started with theme customization. You'll need to install Node.js and Gulp before using our included gulpfile.js.

1.  Download the project's zip
2.  Make sure you have node.js (<https://nodejs.org/en/>) installed
3.  Type `npm install` in terminal/console in the source folder where `package.json` is located
4.  You will find all the branding colors inside `assets/scss/paper-dashboard/_variables.scss`. You can change them with a `HEX` value or with other predefined variables.
5.  Run in terminal `gulp compile-scss` for a single compilation or `gulp watch` for continous compilation of the changes that you make in `*.scss` files. This command should be run in the same folder where `gulpfile.js` and `package.json` are located
6.  Run in terminal `gulp open-app` for opening the Presentation Page (default) of the product.

## Documentation
The documentation for the Paper Dashboard 2 PRO is hosted at our [website](https://demos.creative-tim.com/paper-dashboard-2-pro/docs/1.0/getting-started/introduction.html).


## File Structure

Within the download you'll find the following directories and files:

```
paper-dashboard-2-pro
.
├── CHANGELOG.md
├── README.md
├── assets
│   ├── css/
│   │   ├── bootstrap.min.css
│   │   ├── bootstrap.min.css.map
│   │   ├── paper-dashboard.css
│   │   ├── paper-dashboard.css.map
│   │   └── paper-dashboard.min.css
│   ├── demo/
│   │   ├── demo.css
│   │   └── demo.js
│   ├── fonts/
│   ├── img/
│   ├── js/
│   │   ├── core/
│   │   │   ├── bootstrap.min.js
│   │   │   ├── jquery.min.js
│   │   │   └── popper.min.js
│   │   ├── paper-dashboard.js
│   │   ├── paper-dashboard.js.map
│   │   ├── paper-dashboard.min.js
│   │   └── plugins/
│   └── scss
│       ├── paper-dashboard/
│       │   ├── cards/
│       │   ├── mixins/
│       │   └── plugins/
│       └── paper-dashboard.scss
├── docs/
│   └── documentation.html
├── examples/
│   ├── dashboard.html
│   ├── calendar.html
│   ├── charts.html
│   ├── components/
│   │   ├── buttons.html
│   │   ├── grid.html
│   │   ├── icons.html
│   │   ├── notifications.html
│   │   ├── panels.html
│   │   ├── sweet-alert.html
│   │   └── typography.html
│   ├── forms/
│   │   ├── extended.html
│   │   ├── regular.html
│   │   ├── validation.html
│   │   └── wizard.html
│   ├── maps/
│   │   ├── fullscreen.html
│   │   ├── google.html
│   │   └── vector.html
│   ├── pages/
│   │   ├── lock.html
│   │   ├── login.html
│   │   ├── register.html
│   │   ├── timeline.html
│   │   └── user.html
│   ├── tables/
│   │   ├── datatables.net.html
│   │   ├── extended.html
│   │   └── regular.html
│   └── widgets.html
├── gulpfile.js
├── nucleo-icons.html
└── package.json
```

## Browser Support

At present, we officially aim to support the last two versions of the following browsers:

<img src="https://github.com/creativetimofficial/public-assets/blob/master/logos/chrome-logo.png?raw=true" width="64" height="64"> <img src="https://raw.githubusercontent.com/creativetimofficial/public-assets/master/logos/firefox-logo.png" width="64" height="64"> <img src="https://raw.githubusercontent.com/creativetimofficial/public-assets/master/logos/edge-logo.png" width="64" height="64"> <img src="https://raw.githubusercontent.com/creativetimofficial/public-assets/master/logos/safari-logo.png" width="64" height="64"> <img src="https://raw.githubusercontent.com/creativetimofficial/public-assets/master/logos/opera-logo.png" width="64" height="64">

## Resources
- [Live Preview](https://demos.creative-tim.com/paper-dashboard-2-pro/examples/dashboard.html)
- [Buy Page](https://www.creative-tim.com/product/paper-dashboard-2-pro)
- [Documentation](https://demos.creative-tim.com/paper-dashboard-2-pro/docs/1.0/getting-started/introduction.html)
- [Paper Dashboard PRO Bootstrap 3](https://demos.creative-tim.com/paper-dashboard-pro/examples/dashboard/overview.html)
- [License Agreement](https://www.creative-tim.com/license)
- [Support](https://www.creative-tim.com/contact-us)
- Issues [Github Issues Page](https://github.com/creativetimofficial/ct-paper-dashboard-2-pro/issues)

## Reporting Issues

We use GitHub Issues as the official bug tracker for the Paper Dashboard 2 PRO. Here are some advices for our users that want to report an issue:

1. Make sure that you are using the latest version of the Paper Dashboard 2 PRO. Check the CHANGELOG from your dashboard on our [website](https://www.creative-tim.com/?ref=pd2p-github-readme).
2. Providing us reproducible steps for the issue will shorten the time it takes for it to be fixed.
3. Some issues may be browser specific, so specifying in what browser you encountered the issue might help.

## Licensing

- Copyright 2020 Creative Tim (https://www.creative-tim.com/?ref=pd2p-github-readme)

[CHANGELOG]: ./CHANGELOG.md
[LICENSE]: ./LICENSE.md

## Useful Links

- [Tutorials](https://www.youtube.com/channel/UCVyTG4sCw-rOvB9oHkzZD1w)
- [Affiliate Program](https://www.creative-tim.com/affiliates/new?ref=pd2p-github-readme) (earn money)
- [Blog Creative Tim](https://creative-tim.com/blog)
- [Free Products](https://www.creative-tim.com/bootstrap-themes/free?ref=pd2p-github-readme) from Creative Tim
- [Premium Products](https://www.creative-tim.com/bootstrap-themes/premium?ref=pd2p-github-readme) from Creative Tim
- [React Products](https://www.creative-tim.com/bootstrap-themes/react-themes?ref=pd2p-github-readme) from Creative Tim
- [Angular Products](https://www.creative-tim.com/bootstrap-themes/angular-themes?ref=pd2p-github-readme) from Creative Tim
- [VueJS Products](https://www.creative-tim.com/bootstrap-themes/vuejs-themes?ref=pd2p-github-readme) from Creative Tim
- [More products](https://www.creative-tim.com/bootstrap-themes?ref=pd2p-github-readme) from Creative Tim
- Check our Bundles [here](https://www.creative-tim.com/bundles?ref=pd2p-github-readme)

### Social Media

Twitter: <https://twitter.com/CreativeTim>

Facebook: <https://www.facebook.com/CreativeTim>

Dribbble: <https://dribbble.com/creativetim>

Instagram: <https://www.instagram.com/CreativeTimOfficial>

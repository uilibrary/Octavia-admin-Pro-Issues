# Octavia - Vuetify Admin dashboard Template

# [Octavia Admin Pro](https://octavia-admin.vercel.app)

![version](https://img.shields.io/badge/version-1.0.0-blue.svg)

<a href="https://octavia-admin.vercel.app"><img src="https://i.ibb.co/mBbW0sx/01-preview.png" alt="01-preview" border="0"></a>

**Octavia Admin Pro** is a Modern & beautiful Admin Dashboard built over [Vuetify](https://vuetifyjs.com/en/), [Vuex](https://vuex.vuejs.org/installation.html) and [Vuejs](https://vuejs.org/). It will help you get started and quickly developing dashboards in no time. Using This Dashboard is pretty simple Component Based Admin but requires basic knowledge of Javascript, [Vuejs](https://vuejs.org/v2/guide/) and [Vue-Router](https://router.vuejs.org/en/).

## Getting Started

-   Install Nodejs from the official [Nodejs page](https://nodejs.org/en/)

## Project setup Using NPM

```
npm install
```

-   if this is not work try :

```
npm cache clean --force

```

-   or

```
npm intall  --legacy-peer-deps

```

### Compiles and hot-reloads for development

```
npm run serve
```

### Compiles and minifies for production

```
npm run build
```

### Lints and fixes files

```
npm run lint
```

## Vuetify

Vuetify is an Open Source UI Library that is developed exactly according to Material Design spec. Every component is handcrafted to bring you the best possible UI tools to your next great app. The development doesn't stop at the core components outlined in Google's spec. Through the support of community members and sponsors, additional components will be designed and made available for everyone to enjoy.

The documentation for **Vuetify** is hosted [here](https://vuetifyjs.com/).

**_Not all components that are available in this project are part of the Template and may be a default Vuetify component_**

## Vuex

Vuex is a state management pattern + library for Vue.js applications. It serves as a centralized store for all the components in an application, with rules ensuring that the state can only be mutated in a predictable fashion. It also integrates with Vue's official [devtools](https://github.com/vuejs/vue-devtools) extension to provide advanced features such as zero-config time-travel debugging and state snapshot export / import.

## Vue-cli

We used the latest 3.x [Vue CLI](https://github.com/vuejs/vue-cli) which aims to reduce project configuration
to as little as possible. Almost everything is inside `package.json` + some other related files such as
`.babel.config.js`, `.eslintrc.js` and `.postcssrc.js`.

Let us know what you think and what we can improve below. And good luck with development!

## Table of Contents

-   [Demo](#demo)
-   [Quick Start](#quick-start)

-   [File Structure](#file-structure)
-   [Documentation](#documentation)
-   [Browser Support](#browser-support)
-   [Resources](#resources)
-   [Reporting Issues](#reporting-issues)
-   [Technical Support or Questions](#technical-support-or-questions)
-   [Licensing](#licensing)
-   [Useful Links](#useful-links)

## Demo

-   [Demo page](https://octavia-admin.vercel.app)

## Quick Start

-   Install Nodejs from the official [Nodejs page](https://nodejs.org/en/)
-   Install Yarn from the official [Yarn installation page](https://classic.yarnpkg.com/en/docs/install/#windows-stable).
-   Unzip the `octavia-admin.zip` file downloaded from Vuetify
-   Create a folder named `octavia-admin` and unzip the `theme.zip` file provided by the previous step
-   Open your terminal and navigate to the `octavia-admin` directory
-   Run `yarn install` to install the project's dependencies
-   Run `yarn serve` to start a local development server

You can also run additional tasks such as

-   `yarn run build` to build your app for production
-   `yarn run lint` to run linting.

### Project setup Using NPM

```
npm install
```

### Compiles and hot-reloads for development

```
npm run serve
```

### Compiles and minifies for production

```
npm run build
```

### Lints and fixes files

```
npm run lint
```

## File Structure

Within the download you'll find the following directories and files:

<details>

```txt
Octavia Admin/
|-- .gitignore
|-- .htaccess
|-- babel.config.js
|-- debug.log
|-- description.html
|-- package-lock.json
|-- package.json
|-- README.md
|-- server.js
|-- vue.config.js
|-- public
|   |-- .htaccess
|   |-- android-chrome-192x192.png
|   |-- android-chrome-512x512.png
|   |-- apple-touch-icon.png
|   |-- browserconfig.xml
|   |-- favicon-16x16.png
|   |-- favicon-32x32.png
|   |-- favicon.ico
|   |-- index.html
|   |-- mstile-144x144.png
|   |-- mstile-150x150.png
|   |-- mstile-310x150.png
|   |-- mstile-310x310.png
|   |-- mstile-70x70.png
|   |-- robots.txt
|   |-- safari-pinned-tab.svg
|   |-- site.webmanifest
|   |-- _redirects
|-- src
|-- App.vue
|-- main.js
|-- themeConfig.js
|-- assets
|   |-- logo.png
|   |-- logo.svg
|   |-- css
|   |   |-- tailwind.css
|   |-- fonts
|   |   |-- gijgo
|   |   |   |-- gijgo-material.eot
|   |   |   |-- gijgo-material.svg
|   |   |   |-- gijgo-material.ttf
|   |   |   |-- gijgo-material.woff
|   |   |-- iconsmind
|   |       |-- iconsmind.css
|   |       |-- iconsmind.eot
|   |       |-- iconsmind.svg
|   |       |-- iconsmind.ttf
|   |       |-- iconsmind.woff
|   |-- images
|   |   |-- Angular_Icon.png
|   |   |-- arctic-circle-logo.svg
|   |   |-- arctic-logo.svg
|   |   |-- arctic-white-circle.svg
|   |   |-- bg-1.png
|   |   |-- bootstrap-logo.png
|   |   |-- checkmark.svg
|   |   |-- circles.png
|   |   |-- close.svg
|   |   |-- danger.svg
|   |   |-- dots.png
|   |   |-- egret.png
|   |   |-- Html_Icon.png
|   |   |-- info.svg
|   |   |-- laravel-logo.png
|   |   |-- logo.svg
|   |   |-- mac_book.jpg
|   |   |-- master-card.png
|   |   |-- page-bg-bottom.png
|   |   |-- photo-long-1.jpg
|   |   |-- photo-long-2.jpg
|   |   |-- photo-long-3.jpg
|   |   |-- photo-long-4.jpg
|   |   |-- photo-wide-1.jpg
|   |   |-- photo-wide-2.jpg
|   |   |-- photo-wide-3.jpg
|   |   |-- photo-wide-5.jpeg
|   |   |-- ps.png
|   |   |-- react.png
|   |   |-- Sass_icon.png
|   |   |-- signin-left.jpg
|   |   |-- trianglefy.png
|   |   |-- vue.png
|   |   |-- waterfall.jpg
|   |   |-- webpack.png
|   |   |-- avatars
|   |   |   |-- 001-man.svg
|   |   |   |-- 002-woman.svg
|   |   |   |-- 003-man-1.svg
|   |   |   |-- 004-bald.svg
|   |   |   |-- 005-man-2.svg
|   |   |   |-- 006-woman-1.svg
|   |   |   |-- 007-woman-2.svg
|   |   |-- BrandSVG
|   |   |   |-- apple.svg
|   |   |   |-- asus.svg
|   |   |   |-- cisco.svg
|   |   |   |-- dell.svg
|   |   |   |-- intel.svg
|   |   |   |-- lg.svg
|   |   |   |-- motorola.svg
|   |   |   |-- vaio.svg
|   |   |-- cities
|   |   |   |-- city-1.jpg
|   |   |   |-- city-2.jpg
|   |   |   |-- city-3.jpg
|   |   |   |-- city-cars-road-houses.jpg
|   |   |   |-- pexels-photo-129830.jpeg
|   |   |   |-- pexels-photo-466685.jpeg
|   |   |-- country
|   |   |   |-- china.jpg
|   |   |   |-- dubai.jpg
|   |   |   |-- new_york.jpg
|   |   |   |-- paris.jpg
|   |   |-- faces
|   |   |   |-- 1.jpg
|   |   |   |-- 10.jpg
|   |   |   |-- 12.jpg
|   |   |   |-- 13.jpg
|   |   |   |-- 15.jpg
|   |   |   |-- 16.jpg
|   |   |   |-- 17.jpg
|   |   |   |-- 2.jpg
|   |   |   |-- 3.jpg
|   |   |   |-- 4.jpg
|   |   |   |-- 5.jpg
|   |   |   |-- 9.jpg
|   |   |-- file-types
|   |   |   |-- 001-pdf.svg
|   |   |   |-- 002-psd.svg
|   |   |   |-- 004-xlsx.svg
|   |   |-- gallery
|   |   |   |-- section-bg-1.jpg
|   |   |   |-- sq-10.jpg
|   |   |   |-- sq-11.jpg
|   |   |   |-- sq-12.jpg
|   |   |   |-- sq-13.jpg
|   |   |   |-- sq-15.jpg
|   |   |   |-- sq-16.jpg
|   |   |   |-- sq-17.jpg
|   |   |   |-- sq-4.jpg
|   |   |   |-- sq-5.jpg
|   |   |   |-- sq-6.jpg
|   |   |   |-- sq-7.jpg
|   |   |   |-- sq-8.jpg
|   |   |   |-- sq-9.jpg
|   |   |-- illustrations
|   |   |   |-- baby.svg
|   |   |   |-- badge-1.svg
|   |   |   |-- badge-2.svg
|   |   |   |-- badge-3.svg
|   |   |   |-- breaking_barriers.svg
|   |   |   |-- business_deal.svg
|   |   |   |-- designer.svg
|   |   |   |-- done.svg
|   |   |   |-- done_2.svg
|   |   |   |-- lighthouse.svg
|   |   |   |-- posting_photo.svg
|   |   |   |-- rocket.svg
|   |   |   |-- tick.svg
|   |   |   |-- undraw_monitor.svg
|   |   |   |-- upgrade.svg
|   |   |   |-- ecomerce
|   |   |   |   |-- chair-2.svg
|   |   |   |   |-- chair-3.svg
|   |   |   |   |-- chair.svg
|   |   |   |   |-- furniture.svg
|   |   |   |-- pricing
|   |   |       |-- for_business.svg
|   |   |       |-- plan.svg
|   |   |       |-- undraw_analyze.svg
|   |   |       |-- undraw_businessman.svg
|   |   |       |-- undraw_businesswoman.svg
|   |   |       |-- undraw_Graduation.svg
|   |   |       |-- undraw_investing.svg
|   |   |       |-- undraw_map.svg
|   |   |       |-- undraw_map_2.svg
|   |   |       |-- undraw_plans.svg
|   |   |       |-- undraw_setup.svg
|   |   |       |-- undraw_unicorn.svg
|   |   |       |-- undraw_world.svg
|   |   |-- logos
|   |   |   |-- 001-spotify.svg
|   |   |   |-- 003-apple.svg
|   |   |   |-- 004-windows.svg
|   |   |   |-- 005-google.svg
|   |   |   |-- angular.png
|   |   |   |-- bootstrap.png
|   |   |   |-- logo-1.png
|   |   |   |-- logo-2.png
|   |   |   |-- logo-3.png
|   |   |   |-- logo-4.png
|   |   |   |-- logo-5.png
|   |   |   |-- logo-6.png
|   |   |   |-- logo-7.png
|   |   |   |-- logo-8.png
|   |   |   |-- logo-9.png
|   |   |   |-- logo-circle.svg
|   |   |   |-- logo.svg
|   |   |   |-- react.png
|   |   |   |-- sass.png
|   |   |   |-- webpack.png
|   |   |-- payment-card
|   |   |   |-- 004-visa.svg
|   |   |   |-- maestro.png
|   |   |   |-- master-card.png
|   |   |   |-- paypal-2.png
|   |   |   |-- paypal.png
|   |   |   |-- visa-2.png
|   |   |   |-- visa.png
|   |   |-- products
|   |   |   |-- 1.png
|   |   |   |-- 10.png
|   |   |   |-- 11.png
|   |   |   |-- 12.png
|   |   |   |-- 13.png
|   |   |   |-- 14.png
|   |   |   |-- 15.png
|   |   |   |-- 16.png
|   |   |   |-- 17.png
|   |   |   |-- 18.png
|   |   |   |-- 19.png
|   |   |   |-- 2.png
|   |   |   |-- 20.png
|   |   |   |-- 21.png
|   |   |   |-- 22.png
|   |   |   |-- 23.png
|   |   |   |-- 24.png
|   |   |   |-- 25.png
|   |   |   |-- 26.png
|   |   |   |-- 27.png
|   |   |   |-- 28.png
|   |   |   |-- 29.png
|   |   |   |-- 3.png
|   |   |   |-- 30.png
|   |   |   |-- 31.png
|   |   |   |-- 32.png
|   |   |   |-- 33.png
|   |   |   |-- 34.png
|   |   |   |-- 35.png
|   |   |   |-- 36.png
|   |   |   |-- 37.png
|   |   |   |-- 38.png
|   |   |   |-- 39.png
|   |   |   |-- 4.png
|   |   |   |-- 40.png
|   |   |   |-- 41.png
|   |   |   |-- 42.png
|   |   |   |-- 43.png
|   |   |   |-- 44.png
|   |   |   |-- 45.png
|   |   |   |-- 46.png
|   |   |   |-- 47.png
|   |   |   |-- 48.png
|   |   |   |-- 49.png
|   |   |   |-- 5.png
|   |   |   |-- 50.png
|   |   |   |-- 51.png
|   |   |   |-- 52.png
|   |   |   |-- 6.png
|   |   |   |-- 7.png
|   |   |   |-- 8.png
|   |   |   |-- 9.png
|   |   |   |-- cloud-346710_1280.png
|   |   |   |-- headphone-1.jpg
|   |   |   |-- headphone-2.jpg
|   |   |   |-- headphone-3.jpg
|   |   |   |-- headphone-4.jpg
|   |   |   |-- iphone-1.jpg
|   |   |   |-- iphone-2.jpg
|   |   |   |-- photo-wide-2.jpg
|   |   |   |-- speaker-1.jpg
|   |   |   |-- speaker-2.jpg
|   |   |   |-- watch-1.jpg
|   |   |   |-- watch-2.jpg
|   |   |   |-- weather-2.jpg
|   |   |   |-- weather.jpg
|   |   |   |-- accessories
|   |   |   |   |-- wireless.png
|   |   |   |-- audio
|   |   |   |   |-- earbuds.png
|   |   |   |   |-- earphone.png
|   |   |   |   |-- microphone.png
|   |   |   |   |-- speaker.png
|   |   |   |-- fashion
|   |   |   |   |-- t-shirt-2.png
|   |   |   |   |-- t-shirt-3.png
|   |   |   |   |-- t-shirt-4.png
|   |   |   |   |-- t-shirt-5.png
|   |   |   |   |-- t-shirt.png
|   |   |   |-- mobile
|   |   |       |-- samsung.png
|   |   |-- screenshots
|   |   |   |-- dashboard.v1.png
|   |   |   |-- dashboard.v2.png
|   |   |   |-- layout1.png
|   |   |   |-- layout2.png
|   |   |   |-- layout23.png
|   |   |   |-- layout3.png
|   |   |   |-- layout4.png
|   |   |-- svg
|   |       |-- activity.svg
|   |       |-- add-contact.svg
|   |       |-- architecture-and-city.svg
|   |       |-- art-and-design.svg
|   |       |-- artist.svg
|   |       |-- block.svg
|   |       |-- booking-online.svg
|   |       |-- brands-and-logotypes.svg
|   |       |-- business-and-finance.svg
|   |       |-- calendar.svg
|   |       |-- company.svg
|   |       |-- contact.svg
|   |       |-- customer.svg
|   |       |-- data-security-2.svg
|   |       |-- data-security.svg
|   |       |-- database.svg
|   |       |-- donald-trump.svg
|   |       |-- download.svg
|   |       |-- error.svg
|   |       |-- experience.svg
|   |       |-- folder.svg
|   |       |-- gift.svg
|   |       |-- goal.svg
|   |       |-- google-logo.svg
|   |       |-- google-photos.svg
|   |       |-- growth.svg
|   |       |-- link.svg
|   |       |-- log-in.svg
|   |       |-- login.svg
|   |       |-- mail.svg
|   |       |-- man.svg
|   |       |-- maps-and-location-2.svg
|   |       |-- maps-and-location.svg
|   |       |-- mobile-banking.svg
|   |       |-- money.svg
|   |       |-- online-payment.svg
|   |       |-- password-manager.svg
|   |       |-- placeholder.svg
|   |       |-- remove-user.svg
|   |       |-- search.svg
|   |       |-- secret.svg
|   |       |-- seo-and-web.svg
|   |       |-- share.svg
|   |       |-- skycraper.svg
|   |       |-- startup.svg
|   |       |-- subscription.svg
|   |       |-- team.svg
|   |       |-- timeline.svg
|   |       |-- ui.svg
|   |       |-- warning.svg
|   |       |-- wrench.svg
|   |       |-- youtube.svg
|   |-- js
|   |   |-- app
|   |   |   |-- app.js
|   |   |   |-- egretCusomizer.js
|   |   |   |-- headerMenu.js
|   |   |   |-- layout1.js
|   |   |   |-- layout2.js
|   |   |   |-- layout3.js
|   |   |   |-- layout4.js
|   |   |   |-- mobileHeader.js
|   |   |   |-- search.js
|   |   |   |-- secondarySidebar.js
|   |   |   |-- sidebarPanel.js
|   |   |   |-- stickyHeader.js
|   |   |   |-- utils.js
|   |   |   |-- wizard.js
|   |   |-- data
|   |       |-- countries.json
|   |       |-- datatable.json
|   |       |-- series.js
|   |       |-- template-list.json
|   |-- scss
|       |-- octavia-design-system
|           |-- octavia-design-system.scss
|           |-- _reboot.scss
|           |-- functions
|           |   |-- _color.function.scss
|           |   |-- _functions.scss
|           |-- mixins
|           |   |-- _animation.scss
|           |   |-- _badge.scss
|           |   |-- _border.scss
|           |   |-- _buttons.scss
|           |   |-- _card.scss
|           |   |-- _hover.scss
|           |   |-- _icons.scss
|           |   |-- _mixins.scss
|           |   |-- _responsive.scss
|           |   |-- _shadow.scss
|           |   |-- _typography.scss
|           |-- utilities
|           |   |-- _animations.scss
|           |   |-- _avatar.scss
|           |   |-- _border.scss
|           |   |-- _colors.scss
|           |   |-- _height-width.scss
|           |   |-- _shadow.scss
|           |   |-- _spacing.scss
|           |   |-- _typography.scss
|           |   |-- _utilities.scss
|           |   |-- _z-index.scss
|           |-- variables
|           |   |-- _animation.scss
|           |   |-- _base.scss
|           |   |-- _border.scss
|           |   |-- _buttons.scss
|           |   |-- _colors.scss
|           |   |-- _shadows.scss
|           |   |-- _spacing.scss
|           |   |-- _typography.scss
|           |   |-- _variables.scss
|           |   |-- _z-index.scss
|           |-- views
|               |-- _dark.scss
|-- auth
|   |-- authenticate.js
|-- components
|   |-- README.md
|   |-- base
|   |   |-- Card.vue
|   |   |-- HoverButton.vue
|   |   |-- item.vue
|   |   |-- itemGroup.vue
|   |   |-- itemSubGroup.vue
|   |   |-- OutlineButton.vue
|   |-- card
|       |-- AnalyticCardVersionOne.vue
|       |-- AnalyticCardVersionTwo.vue
|       |-- AvatarGroupCard.vue
|       |-- BasicInfoCard.vue
|       |-- ChartCard.vue
|       |-- CryptoCurrencyCard.vue
|       |-- DonationCard.vue
|       |-- LmsCard.vue
|       |-- PriceCard.vue
|       |-- TestCard.vue
|       |-- listCard
|           |-- ListCard.vue
|           |-- ListCardRow.vue
|           |-- ListCardThree.vue
|           |-- ListCardTwo.vue
|-- data
|   |-- analytic.js
|   |-- analytic2.js
|   |-- apexChart.js
|   |-- apexDataSeries.js
|   |-- chat.js
|   |-- config.js
|   |-- cryptoCurrency.js
|   |-- dashboard1.js
|   |-- dashboard2.js
|   |-- dashboard3.js
|   |-- demographics.js
|   |-- echarts.js
|   |-- echartSeries.js
|   |-- jobManagement.js
|   |-- learningManagement.js
|   |-- navigation.js
|   |-- products.js
|   |-- sales2.js
|   |-- voiceInteraction.js
|   |-- widgetChart.js
|   |-- widgetStatistics.js
|-- fake-db
|   |-- index.js
|   |-- mock.js
|   |-- data
|       |-- chat.js
|       |-- ecommerce.js
|       |-- note.js
|       |-- todo.js
|-- lang
|   |-- lang.js
|   |-- i18n
|       |-- bn.json
|       |-- de.json
|       |-- en.json
|-- layouts
|   |-- base
|   |   |-- AppBar.vue
|   |   |-- Index.vue
|   |   |-- View.vue
|   |-- common-drawer
|   |   |-- Customizer.vue
|   |   |-- NotificationDrawer.vue
|   |   |-- SearchDrawer.vue
|   |   |-- UserDrawer.vue
|   |-- horizontal
|   |   |-- AppBar.vue
|   |   |-- Footer.vue
|   |   |-- Index.vue
|   |   |-- Sidebar.vue
|   |   |-- TopNavbar.vue
|   |   |-- TopNavMenu.vue
|   |   |-- UserDrawer.vue
|   |   |-- View.vue
|   |-- vertical
|   |   |-- AppBar.vue
|   |   |-- Footer.vue
|   |   |-- Index.vue
|   |   |-- Sidebar.vue
|   |   |-- SubHeader.vue
|   |   |-- View.vue
|   |-- vertical-compact-layout
|   |   |-- AppBar.vue
|   |   |-- Footer.vue
|   |   |-- Index.vue
|   |   |-- Sidebar.vue
|   |   |-- View.vue
|   |-- vertical-saas-layout
|       |-- AppBar.vue
|       |-- Footer.vue
|       |-- Index.vue
|       |-- Sidebar.vue
|       |-- View.vue
|-- plugins
|   |-- apexChart.js
|   |-- base.js
|   |-- index.js
|   |-- octavia.kit.js
|   |-- vuetify.js
|   |-- webfontloader.js
|-- router
|   |-- index.js
|-- scss
|   |-- variable.scss
|-- store
|   |-- index.js
|   |-- modules
|       |-- authData.js
|       |-- cart.js
|       |-- chat.js
|       |-- compactSidebar.js
|       |-- hridoy.jsx
|       |-- invoice.js
|       |-- largeSidebar.js
|       |-- note.js
|       |-- scrumboard.js
|       |-- themeConfig.js
|       |-- verticalSidebar.js
|-- views
    |-- app
    |   |-- Index.vue
    |   |-- apps
    |   |   |-- Chat.vue
    |   |   |-- FileManager.vue
    |   |   |-- Index.vue
    |   |   |-- Note.vue
    |   |   |-- Scrumboard.vue
    |   |   |-- Todo.vue
    |   |-- charts
    |   |   |-- Charts.vue
    |   |   |-- apexChart
    |   |       |-- ApexAreaChart.vue
    |   |       |-- ApexBarChart.vue
    |   |       |-- ApexChart.vue
    |   |       |-- ApexColumnChart.vue
    |   |       |-- ApexLineChart.vue
    |   |       |-- ApexMixChart.vue
    |   |       |-- ApexPieChart.vue
    |   |       |-- ApexRadarChart.vue
    |   |       |-- ApexRadialBarChart.vue
    |   |       |-- ApexScatterChart.vue
    |   |       |-- ApexSparklineChart.vue
    |   |       |-- CustomApexChart.vue
    |   |-- customTable
    |   |   |-- CustomTable.vue
    |   |   |-- TableOne.vue
    |   |   |-- TableThree.vue
    |   |   |-- TableTwo.vue
    |   |-- dashboard
    |   |   |-- Analytic.vue
    |   |   |-- AnalyticExtra.vue
    |   |   |-- CryptoCurrency.vue
    |   |   |-- Donation.vue
    |   |   |-- Index.vue
    |   |   |-- JobManagement.vue
    |   |   |-- LearningManagement.vue
    |   |   |-- Sales.vue
    |   |-- ecommerce
    |   |   |-- CartDrawer.vue
    |   |   |-- Ecommerce.vue
    |   |   |-- EcommerceProductCheckout.vue
    |   |   |-- EcommerceProductDetails.vue
    |   |   |-- EcommerceProductList.vue
    |   |-- extraUiKits
    |   |   |-- BottomNavigation.vue
    |   |   |-- BottomSheets.vue
    |   |   |-- Calendars.vue
    |   |   |-- Cards.vue
    |   |   |-- Circular.vue
    |   |   |-- Index.vue
    |   |   |-- Linear.vue
    |   |   |-- List.vue
    |   |   |-- Paginations.vue
    |   |   |-- Ratings.vue
    |   |   |-- Tabs.vue
    |   |-- forms
    |   |   |-- ComboBox.vue
    |   |   |-- DatePicker.vue
    |   |   |-- Index.vue
    |   |   |-- Inputs.vue
    |   |   |-- OverflowButtons.vue
    |   |   |-- SelectionControls.vue
    |   |   |-- Selects.vue
    |   |   |-- Sliders.vue
    |   |   |-- Textarea.vue
    |   |   |-- TextFields.vue
    |   |   |-- TimePicker.vue
    |   |   |-- Validation.vue
    |   |-- pages
    |   |   |-- Blank.vue
    |   |   |-- Pages.vue
    |   |   |-- account
    |   |   |   |-- Account.vue
    |   |   |   |-- AccountData.vue
    |   |   |   |-- AccountHome.vue
    |   |   |   |-- AccountPayment.vue
    |   |   |   |-- AccountPeople.vue
    |   |   |   |-- AccountPersonalInfo.vue
    |   |   |   |-- AccountSecurity.vue
    |   |   |-- faq
    |   |   |   |-- Faq.vue
    |   |   |   |-- FaqOne.vue
    |   |   |   |-- FaqThree.vue
    |   |   |   |-- FaqTwo.vue
    |   |   |-- invoice
    |   |   |   |-- EditInvoice.vue
    |   |   |   |-- Invoice.vue
    |   |   |   |-- InvoiceVerOne.vue
    |   |   |   |-- InvoiceVerTwo.vue
    |   |   |-- list
    |   |   |   |-- List.vue
    |   |   |   |-- ListColumnOne.vue
    |   |   |   |-- ListColumnRow.vue
    |   |   |   |-- ListColumnThree.vue
    |   |   |   |-- ListColumnTwo.vue
    |   |   |-- pricing
    |   |   |   |-- Pricing.vue
    |   |   |   |-- PricingVerOne.vue
    |   |   |   |-- PricingVerThree.vue
    |   |   |   |-- PricingVerTwo.vue
    |   |   |-- profile
    |   |   |   |-- Profile.vue
    |   |   |   |-- ProfileOne.vue
    |   |   |   |-- ProfileTwo.vue
    |   |   |-- projects
    |   |   |   |-- Overview.vue
    |   |   |   |-- Projects.vue
    |   |   |   |-- Todo.vue
    |   |   |-- widgets
    |   |       |-- General.vue
    |   |       |-- WidgetCharts.vue
    |   |       |-- Widgets.vue
    |   |       |-- WidgetsTable.vue
    |   |-- sessions
    |   |   |-- Error.vue
    |   |   |-- Forgot.vue
    |   |   |-- Lockscreen.vue
    |   |   |-- Sessions.vue
    |   |   |-- SignIn.vue
    |   |   |-- SignInFive.vue
    |   |   |-- SignInFour.vue
    |   |   |-- SignInThree.vue
    |   |   |-- SignInTwo.vue
    |   |   |-- SignUp.vue
    |   |   |-- SignUpFive.vue
    |   |   |-- SignUpTwo.vue
    |   |-- tables
    |   |   |-- DataIterators.vue
    |   |   |-- DataTables.vue
    |   |   |-- Index.vue
    |   |   |-- SimpleTables.vue
    |   |-- test
    |   |   |-- Test.vue
    |   |   |-- Testing-2.vue
    |   |   |-- Testing.vue
    |   |-- uiKits
    |       |-- Accordion.vue
    |       |-- Alerts.vue
    |       |-- Avatar.vue
    |       |-- Badge.vue
    |       |-- Button.vue
    |       |-- Chips.vue
    |       |-- FileInputs.vue
    |       |-- Index.vue
    |       |-- Snackbar.vue
    |       |-- Sparklines.vue
    |       |-- Stepper.vue
    |       |-- ToolTip.vue
    |       |-- TreeView.vue
    |-- home
    |   |-- Index.vue
    |-- uiKits
        |-- button.vue

```

</details>

## Documentation

[![octavia-Presentation-min](https://i.ibb.co/8MMThXV/octavia-Presentation-min.jpg)](https://octavia-admin.vercel.app)

Octavia Admin – VueJs and Vuetify Admin Dashboard Template is clean, feature rich, extraordinarily customizable & developer friendly admin dashboard template.

We’ve followed highest industry standard for Octavia & wrote detailed documentation for the ease of use & customization. Moreover, our dedicated support team is always ready to help you. You can also report bug and submit feature request [HERE](https://github.com/uilibrary/Octavia-admin-Pro-Issues)

Octavia is Ultra Fast , Check Speed [Here](https://gtmetrix.com/reports/www.octavia.ui-lib.com/SWd6ZIcb/)

[![speed-Octavia](https://i.ibb.co/6mytHqp/speed-Octavia.png)](https://gtmetrix.com/reports/www.octavia.ui-lib.com/SWd6ZIcb/)

Octavia Admin Dashboard comes with stunningly designed equipped to apply dashboard interfaces, web page templates, components, plugins with Dark & Light color scheme & RTL

## List of some pages & Features From Octavia Admin

Octavia Provide Built in Firebase Authentication , Prebuilt Applications with Mock Data to help you quick start your project.

## Features

-   Authentication
    -   FireBase
-   Vuex as State Manager
-   Horizontal Navigation
-   Vertical Navigation
-   Compact Navigation
-   SaaS Navigation
-   Fully Responsive
-   **Dashboards**
    -   [Analytic Dashboard](https://octavia-admin.vercel.app/app/dashboard/analytic)
    -   [Sales Dashboard](https://octavia-admin.vercel.app/app/dashboard/sales)
    -   [LMS Dashboard](https://octavia-admin.vercel.app/app/dashboard/learning-management)
    -   [Crypto Dashboard](https://octavia-admin.vercel.app/app/dashboard/crypto-currency)
    -   [Donation Dashboard](https://octavia-admin.vercel.app/app/dashboard/crypto-currency)
    -   [Job Management Dashboard](https://octavia-admin.vercel.app/app/dashboard/job-management)
-   **Apps**
    -   [eCommerce/Shopping cart](https://octavia-admin.vercel.app/app/ecommerce/ecommerce-product-list)
    -   [Scrum board](https://octavia-admin.vercel.app/app/apps/scrumboard)
    -   [Event calendar](https://octavia-admin.vercel.app/app/extraUiKits/calendars)
    -   [Chat](https://octavia-admin.vercel.app/app/apps/chat)
    -   [Note](https://octavia-admin.vercel.app/app/apps/note)
    -   [To-do list](https://octavia-admin.vercel.app/app/apps/todo)
    -   [File Manager](https://octavia-admin.vercel.app/app/apps/file-manager)
-   **Forms**
    -   [Combobox](https://octavia-admin.vercel.app/app/forms/combobox)
    -   [Validation](https://octavia-admin.vercel.app/app/forms/validation)
    -   [Overflow Buttons](https://octavia-admin.vercel.app/app/forms/overflow-buttons)
    -   [Selects](https://octavia-admin.vercel.app/app/forms/selects)
    -   [Selection Control](https://octavia-admin.vercel.app/app/forms/selection-controls)
    -   [Slider](https://octavia-admin.vercel.app/app/forms/sliders)
    -   [Text Area](https://octavia-admin.vercel.app/app/forms/textarea)
    -   [Text Fields](https://octavia-admin.vercel.app/app/forms/textfields)
    -   [Date Pikcet](https://octavia-admin.vercel.app/app/forms/datepicker)
    -   [Time Picker](https://octavia-admin.vercel.app/app/forms/timepicker)

*   **Charts**
    -   [Apex Charts](https://octavia-admin.vercel.app/app/charts/apexchart/ApexAreaChart)
*   **Pages**
    -   **Projects**
        -   [Project Overview](https://octavia-admin.vercel.app/app/pages/projects/overview)
    -   **Widgets**
        -   [General](https://octavia-admin.vercel.app/app/pages/widgets/general)
        -   [Charts](https://octavia-admin.vercel.app/app/pages/widgets/widgetsCharts)
        -   [Table](https://octavia-admin.vercel.app/app/pages/widgets/widgetsTable)
    -   **Faqs**
        -   [Faq Version One](https://octavia-admin.vercel.app/app/pages/faq/faq-one)
        -   [Faq Version Two](https://octavia-admin.vercel.app/app/pages/faq/faq-two)
        -   [Faq Version Three](https://octavia-admin.vercel.app/app/pages/faq/faq-three)
    -   **Lists**
        -   [List Column One](https://octavia-admin.vercel.app/app/pages/list/list-column)
        -   [List Column Two](https://octavia-admin.vercel.app/app/pages/list/list-column-two)
        -   [List Column Three](https://octavia-admin.vercel.app/app/pages/list/list-column-three)
        -   [List Row](https://octavia-admin.vercel.app/app/pages/list/list-column-row)
    -   **Profile**
        -   [Profile Version One](https://octavia-admin.vercel.app/app/pages/profile/profile-one)
        -   [Profile Version Two](https://octavia-admin.vercel.app/app/pages/profile/profile-two)
    -   **Accounts**
        -   [Home](https://octavia-admin.vercel.app/app/pages/account/account-home)
        -   [Data](https://octavia-admin.vercel.app/app/pages/account/account-data)
        -   [Payment](https://octavia-admin.vercel.app/app/pages/account/account-payment)
        -   [People](https://octavia-admin.vercel.app/app/pages/account/account-people)
        -   [Security](https://octavia-admin.vercel.app/app/pages/account/account-security)
        -   [Personal Info](https://octavia-admin.vercel.app/app/pages/account/account-personal-info)
    -   **Pricing**
        -   [Pricing Version One](https://octavia-admin.vercel.app/app/pages/pricing/pricing-ver-one)
        -   [Pricing Version Two](https://octavia-admin.vercel.app/app/pages/pricing/pricing-ver-two)
        -   [Pricing Version Three](https://octavia-admin.vercel.app/app/pages/pricing/pricing-ver-three)
    -   **Invoice**
        -   [Invoice Version One](https://octavia-admin.vercel.app/app/pages/invoice/invoice-ver-one)
        -   [Invoice Version Two](https://octavia-admin.vercel.app/app/pages/invoice/invoice-ver-two)
        -   [Edit Invoice](https://octavia-admin.vercel.app/app/pages/invoice/edit-invoice)
    -   **Custom Data Tables**
        -   [Table Version One](https://octavia-admin.vercel.app/app/customTable/tableOne)
        -   [Table Version Two](https://octavia-admin.vercel.app/app/customTable/tableTwo)
        -   [Table Version Three](https://octavia-admin.vercel.app/app/customTable/tableThree)
    -   [SignIn Version 1](https://octavia-admin.vercel.app/app/sessions/sign-in)
    -   [SignIn Version 2](https://octavia-admin.vercel.app/app/sessions/sign-in-two)
    -   [SignIn Version 3](https://octavia-admin.vercel.app/app/sessions/sign-in-three)
    -   [SignIn Version 4](https://octavia-admin.vercel.app/app/sessions/sign-in-four)
    -   [SignIn Version 5](https://octavia-admin.vercel.app/app/sessions/sign-in-five)
    -   [Signup Version 1](https://octavia-admin.vercel.app/app/sessions/sign-up)
    -   [Signup Version 2](https://octavia-admin.vercel.app/app/sessions/sign-up-2)
    -   [Signup Version 3](https://octavia-admin.vercel.app/app/sessions/sign-up-5)
    -   [Lock Screen](https://octavia-admin.vercel.app/app/sessions/lockscreen)
    -   [Error](https://octavia-admin.vercel.app/app/sessions/error)
    -   [Forgot Password](https://octavia-admin.vercel.app/app/sessions/forgot)
*   And Many More .....

## Browser Support

Octavia aims to support all evergreen browsers (Chrome, Firefox, etc) and Internet Explorer 11 (IE11)

## Resources

-   [Live Preview](https://octavia-admin.vercel.app)
-   Product Page: [Product](https://octavia-admin.vercel.app)
-   Vuetify Documentation is [Here](https://vuetifyjs.com/)
-   License Agreement: [License](https://store.vuetifyjs.com/licenses)
-   Contact: [Contact](https://store.vuetifyjs.com/contact-us)
-   Issues: [Github Issues Page](https://github.com/uilibrary/Octavia-admin-Pro-Issues)

## Reporting Issues

We use GitHub Issues as the official bug tracker for the **Octavia Admin Pro** theme. Here is some advice for our users that want to report an issue:

1. Providing us reproducible steps for the issue will shorten the time it takes for it to be fixed.
2. Some issues may be browser specific, so specifying what browser you encountered the issue will be helpful.

## Technical Support or Questions

If you have questions or need help integrating the product please file an issue [here](https://github.com/uilibrary/Octavia-admin-Pro-Issues).

## Licensing

-   Copyright 2021 Ui-Lib <https://ui-lib.com>
-   Vuetify [License Information](https://github.com/vuetifyjs/vuetify/blob/master/LICENSE.md)

<br>
<br>

<p align="center">
  <img src="https://ui-lib.com/wp-content/uploads/2018/11/Final_Web-01.png" height="128">
</p>

<br>

All applications are built using **Vue** and **Vuetify** and use best standards and practices for optimal **performance** and **accessibility**. Each template is built mobile first and scales down to 320px width (iPhone 5). Each theme supports all evergreen browsers (Chrome, Firefox, etc) and Internet Explorer 11 (IE11).

Each theme comes with full support for all of Vuetify's features including components, directives and more. For more information on available features, visit the API Explorer in the Vuetify documentation.

## Useful Links

-   [Vuetify Documentation](https://vuetifyjs.com/)
-   [Vuetify Store](https://store.vuetifyjs.com/)
-   [Free Vuetify Themes](https://store.vuetifyjs.com/collections/free-products)
-   [Discord](https://discord.com/invite/s93b7Fv)
-   [Twitter](https://twitter.com/vuetifyjs)

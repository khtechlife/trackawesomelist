# Awesome Web Monetization Overview

🕶️ Stuffs about Web Monetization. Packages, articles, documentation links and others tools.

[🏠 Home](/README.md) · [🔥 Feed](https://www.trackawesomelist.com/thomasbnt/awesome-web-monetization/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung) · [😺 thomasbnt/awesome-web-monetization](https://github.com/thomasbnt/awesome-web-monetization) · ⭐ 264 · 🏷️ Miscellaneous

[ [Daily](/content/thomasbnt/awesome-web-monetization/README.md) / [Weekly](/content/thomasbnt/awesome-web-monetization/week/README.md) / Overview ]

---

<img src="https://github.com/thomasbnt/awesome-web-monetization/raw/main/assets/wm_icon_animated.svg" alt="Logo Web Monetization" align="right" width="120px" />

# Awesome Web Monetization [![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)

> Awesome stuffs about Web Monetization. Learn more, check modules and others tools.

**Web Monetization** is a web service that allows you to send money directly in your browser.
This is a JavaScript browser API that allows the creation of a payment stream from the user agent to the website

## Contents

*   [About Web Monetization](#about-web-monetization)
*   [How to start monetize my website](#how-to-start-monetize-my-website)
*   [Resources](#resources)
    *   [Packages](#packages)
    *   [Tutorials](#tutorials)
    *   [Articles](#articles)
    *   [Newsletters](#newsletters)
    *   [Tools](#tools)
    *   [Community](#community)
*   [Donate](#donate)

## About Web Monetization

*   [Webmonetization.org](https://webmonetization.org/)
*   [Documentation](https://webmonetization.org/docs/)
*   [How Web Monetization work for paying payments](https://webmonetization.org/docs/intro/sending-payments/)
*   [How Web Monetization work for receiving payments](https://webmonetization.org/docs/intro/receiving-payments/)
*   [Specifications](https://webmonetization.org/specification/)
*   [ILP Forum (read only)](https://forum.interledger.org/)
*   [Grant For The Web](https://www.grantfortheweb.org/)

***

*   [Interledger : Open protocol suite for sending payments across different ledgers](https://interledger.org/)

## How to start monetize my website

If you would like to monetize your content, you must have a Wallet and Provider account. See below the platforms that allow you to use them.

<details><summary>More details about Wallet and Provider account</summary>
<p>

***

| **Wallets** |                                                                                             |                                                                                                                                                                                                                   |     |
| :---------: | :-----------------------------------------------------------------------------------------: | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :-: |
|     Name    | [![GateHub](https://webmonetization.org/img/logo-wallet-gatehub.svg)](https://gatehub.net/) | [New Wallet ?<br>Create a issue ! (⭐264)](https://github.com/thomasbnt/awesome-web-monetization/issues/new?assignees=thomasbnt\&labels=Wallet%2C+%E2%86%94+WM+repository\&template=new-wallet.md\&title=%5BWa%5D) |     |
|     Fees    |                   SEPA: 1.00 EUR < 50,000 EUR<br>Wire: $15 min ($150 max)                   |                                                                                                                                                                                                                   |     |

| **Payments** |        |
| ------------ | ------ |
| Name         | Empty. |

***

</p>
</details>

On your webpage, integrate your `monetization` tag on meta

```html
<meta name="monetization" content="$ilp.example.com/123456789" />
```

and detect if `monetization` is possible, then work

```js
if (document.monetization) {
  document.monetization.addEventListener("monetizationstart", () => {
    console.log(
      "🎉 Awesome ! You use Web Monetization.\nMore information https://webmonetization.org",
    );
  });
}
```

## Resources

### Packages

*Any packages/modules and plugins*

*   [monetize.js (⭐14)](https://github.com/sunchayn/monetize.js) - An event-driven library to manage and simulate Web Monetization. ![](https://github.com/thomasbnt/awesome-web-monetization/raw/main/assets/small_icons/javascript.png)
*   [types-wm (⭐3)](https://github.com/dacioromero/types-wm) - TypeScript definitions for Web Monetization ![](https://github.com/thomasbnt/awesome-web-monetization/raw/main/assets/small_icons/typescript.png)
*   [ngx-monetization (archived) (⭐8)](https://github.com/CDDelta/ngx-monetization) - Web Monetization API for Angular. ![](https://github.com/thomasbnt/awesome-web-monetization/raw/main/assets/small_icons/angular.png)
*   [react-hook-wm (⭐7)](https://github.com/dacioromero/react-hook-wm) - React hooks for integrating with Web Monetization. ![](https://github.com/thomasbnt/awesome-web-monetization/raw/main/assets/small_icons/react.png)
*   [react-monetize (⭐29)](https://github.com/guidovizoso/react-monetize) - Helpers and hooks to speed up your integration with Web Monetization API. ![](https://github.com/thomasbnt/awesome-web-monetization/raw/main/assets/small_icons/react.png)
*   [ep\_monetization (⭐0)](https://github.com/ISNIT0/ep_monetization) - Plugin for applying payment pointer meta tag to Etherpad site. ![](https://github.com/thomasbnt/awesome-web-monetization/raw/main/assets/small_icons/javascript.png)
*   [wp-connect-coil](https://wordpress.org/plugins/wp-connect-coil/) - Plugin for applying Coil payment pointer meta tag to WordPress site. ![](https://github.com/thomasbnt/awesome-web-monetization/raw/main/assets/small_icons/wordpress.png)
*   [xrptipbot-wordpress-widget](https://wordpress.org/plugins/widget-xrptipbot/) - WordPress Widget based on XRPTIPBOT embed code to donate content creators. ![](https://github.com/thomasbnt/awesome-web-monetization/raw/main/assets/small_icons/wordpress.png)
*   [eleventy-plugin-monetization (⭐17)](https://github.com/DanCanetti/eleventy-plugin-monetization) - An Eleventy plugin to monetize posts and site content. ![](https://github.com/thomasbnt/awesome-web-monetization/raw/main/assets/small_icons/11ty.png)
*   [web-monetization-components (⭐9)](https://github.com/philnash/web-monetization-components) - A collection of web components you can use on your web monetized websites. ![](https://github.com/thomasbnt/awesome-web-monetization/raw/main/assets/small_icons/javascript.png)
*   [revshare (⭐7)](https://github.com/kewbish/revshare) - A JS library for revenue sharing. ![](https://github.com/thomasbnt/awesome-web-monetization/raw/main/assets/small_icons/javascript.png)
*   [web-monetization-proxy (⭐3)](https://github.com/tcdowney/web-monetization-proxy) - Simple Go proxy for injecting Web Monetization meta tags. ![](https://github.com/thomasbnt/awesome-web-monetization/raw/main/assets/small_icons/go.png)
*   [gridsome-plugin-monetization (⭐14)](https://github.com/Sergix/gridsome-plugin-monetization) - Web monetization for Gridsome. ![](https://github.com/thomasbnt/awesome-web-monetization/raw/main/assets/small_icons/gridsome.png)
*   [vuepress-plugin-web-monetization (⭐13)](https://github.com/spekulatius/vuepress-plugin-web-monetization) - Adds the web-monetization metatag to your VuePress website. ![](https://github.com/thomasbnt/awesome-web-monetization/raw/main/assets/small_icons/vuejs.png)
*   [jekyll-web\_monetization (⭐10)](https://github.com/philnash/jekyll-web_monetization) - A Jekyll plugin to add Web MonetizationAPI payment pointers to your site. ![](https://github.com/thomasbnt/awesome-web-monetization/raw/main/assets/small_icons/jekyll.png)
*   [Monetization (⭐4)](https://github.com/KNawm/monetization) - A wrapper around the Web Monetization API to monetize apps. ![](https://github.com/thomasbnt/awesome-web-monetization/raw/main/assets/small_icons/dart.png)
*   [react-webmonetization-meta (⭐3)](https://github.com/uchibeke/react-webmonetization-meta) - A Web Monetization meta tag manager for React. ![](https://github.com/thomasbnt/awesome-web-monetization/raw/main/assets/small_icons/react.png)
*   [web-monetization-electron-app (⭐4)](https://github.com/Jasmin2895/web-monetization-electron-app) - Project demonstrate basic setup to enable web monetization in Electron App. ![](https://github.com/thomasbnt/awesome-web-monetization/raw/main/assets/small_icons/electron.png)
*   [web-monetized-video (⭐15)](https://github.com/Jasmin2895/web-monetized-video) - A web component with has play and pay policy and charges you for the amount of video watched. ![](https://github.com/thomasbnt/awesome-web-monetization/raw/main/assets/small_icons/javascript.png)
*   [web-monetization-polyfill (⭐2)](https://github.com/immers-space/web-monetization-polyfill/) - Ensure the JavaScript Web Monetization API is available, even in environments with Content Security Policies enabled. ![](https://github.com/thomasbnt/awesome-web-monetization/raw/main/assets/small_icons/javascript.png)
*   [web-monetization-video-ads](https://www.npmjs.com/package/web-monetization-video-ads) - Linking Web Monetization with video advertising to allow a freemium business model to be implemented for Web Monetization. ![](https://github.com/thomasbnt/awesome-web-monetization/raw/main/assets/small_icons/javascript.png)
*   [web-monetization-revenue-share](https://www.npmjs.com/package/web-monetization-revenue-share) - Automated redistribution of funds to a community via smart contracts. ![](https://github.com/thomasbnt/awesome-web-monetization/raw/main/assets/small_icons/javascript.png)
*   [awesome-jsgames (⭐399)](https://github.com/proyecto26/awesome-jsgames) - A curated list of awesome JavaScript Games ![](https://github.com/thomasbnt/awesome-web-monetization/raw/main/assets/small_icons/javascript.png)
*   [mediadisclosures (⭐0)](https://github.com/oofdere/mediadisclosures) - An open-source, always evolving, universal content rating system. ![](https://github.com/thomasbnt/awesome-web-monetization/raw/main/assets/small_icons/javascript.png)
*   [web-monetization-demo (⭐1)](https://github.com/peter279k/web-monetization-demo) - This is a Web Monetization Demo ![](https://github.com/thomasbnt/awesome-web-monetization/raw/main/assets/small_icons/javascript.png)
*   [money-chat (⭐3)](https://github.com/dfoderick/money-chat) - Web Monetization chat app ![](https://github.com/thomasbnt/awesome-web-monetization/raw/main/assets/small_icons/javascript.png)

### Tutorials

*   [Getting started](https://webmonetization.org/docs/guides/monetize-page/) - Official documents from webmonetization.org.
*   [Exclusive content](https://webmonetization.org/docs/guides/provide-exclusive-content/) - Put exclusive content on your website.
*   ['A Web Monetization Story'](https://esse-dev.github.io/a-web-monetization-story/) - An interactive, story-based Web Monetization tutorial for online creators.
*   [Web Monetization like I'm 5](https://dev.to/hacksultan/web-monetization-like-i-m-5-1418) - Monetizing the web!

### Articles

*   [Monetizing Content in View](https://dev.to/godwinagedah/monetizing-content-in-view-paying-for-what-you-see-462a) - Paying for what you see.
*   [Web Components](https://dev.to/philnash/web-components-for-the-web-monetization-api-4ed9) - For the Web Monetization API (serie).

### Newsletters

*   [Newsletter of grantfortheweb.org](https://www.grantfortheweb.org/signup) - Sign up for email updates.

### Tools

*   [Probabilistic Revshare Generator - Web Monetization](https://webmonetization.org/prob-revshare/) - Probabilistic revenue sharing (revshare) is one way to share a portion of a web monetized pages earnings between multiple payment pointers.

    > Use this tool to define a list of payment pointers and their weights.
    > Then, add the generated monetization link element to your site.
    > The link will contain a unique URL hosted on <https://webmonetization.org/api/revshare/pay/>.
    > If you'd prefer to not use a hosted URL, you can set up revshare by adding a script to your site.

*   [Is web monetized (⭐4)](https://github.com/jkga/is-web-monetized) - A very simple tool for checking if Web Monetization is enabled.

    > ```bash
    > npm install is-web-monetized -g
    > monetized example.com
    > ```
    >
    > You can also test your website [with the dependency (⭐4)](https://github.com/jkga/is-web-monetized#usage).

*   [Paytrackr (⭐0)](https://github.com/thomasbnt/paytrackr) - (Forked from [wobsoriano/paytrackr](https://github.com/wobsoriano)) - Track and manage your micropayments into one place.

    > PayTrackr is the easiest and safest way to track and manage your micropayments to web monetized websites, having a web monetization provider membership.

*   [Akita (⭐22)](https://github.com/esse-dev/akita) - A browser extension that gives you insight into your involvement with Web Monetization.

    > Akita presents your top visited monetized sites, how much time you're spending on them, and how much you're contributing (or could contribute) to them.

*   [Open Monetization Wallet (⭐11)](https://github.com/kristianfreeman/openmonetizationwallet) - Tools for managing your vanity Web Monetization wallet.

    > Open Monetization Wallet (OMW) makes it easier to accept payments with the Web Monetization API at scale. Some features:
    >
    > *   Custom wallet URLs: own your own "Payment Pointer", e.g. $wallet.signalnerve.com, instead of $pay.stronghold.co/abcdef123
    > *   Change between wallets/providers with no downtime
    > *   Logs of incoming payment requests
    > *   Revenue sharing between multiple wallets, e.g. for multiple team members
    > *   Infinitely scalable with serverless technology
    > *   Free and open-source

### Community

*   [Web Monetization Community](https://community.interledger.org/)
*   [@GrantForTheWeb on Twitter](https://twitter.com/GrantForTheWeb)
*   [Web Monetization tag on DEV](https://dev.to/t/webmonetization)

***

## Contribute

Contributions welcome ! Read the [contribution guidelines](https://github.com/thomasbnt/awesome-web-monetization/blob/main/readme.md/contributing.md) first.
You can also contribute to share this repository and Web Monetization with your friends. 😄

If you want to add a new small icon, the height must be **16px**. Put in `assets/small_icons/NAME.png`. Format PNG only accepted.

> **Powered by Netlify** ✨

Netlify powering [the website](https://awesomewebmonetization.netlify.app/). Thanks to them! 💚

[![Deploys by Netlify](https://img.shields.io/badge/Netlify-00C7B7?style=for-the-badge\&logo=netlify\&logoColor=white)](https://netlify.com)

## Donate

Feel free to help [me](https://github.com/thomasbnt) for the maintenance of this project !
Thanks to all **Sponsors on GitHub** !

[![GitHub Sponsors](https://cdn.jsdelivr.net/gh/thomasbnt/sponsors/sponsors.svg)](https://github.com/sponsors/thomasbnt)

[![GitHub Sponsors](https://img.shields.io/badge/Sponsor%20me-%23EA54AE.svg?\&style=for-the-badge\&logo=github-sponsors\&logoColor=white)](https://github.com/sponsors/thomasbnt) [![Support me on Buy Me a Coffee](https://img.shields.io/badge/Support%20me-on%20Buy%20Me%20a%20Coffee-white?style=for-the-badge\&logo=buy-me-a-coffee\&logoColor=black\&labelColor=%23FFDD00)](https://www.buymeacoffee.com/thomasbnt?via=thomasbnt)


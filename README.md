# Orb's Minimal React Template

Last README update: Saturday, March 20, 2021.

A React app template for bootstrapping deployments on Orb's HyperEdge.

**`yarn start`** spins up a development server on `PORT 3000`.

**`yarn build`** builds the application for production into the `/build` directory.

**`yarn serve`** serves a built application locally.

All source code is contained in the `/src` directory.

Deploy the app on [Orb's HyperEdge](https://console.orbclouds.com?id=606019a808e440587e87d7c5).

---
## See This Repo In Action!

This repo serves as the starting point for all of the apps featured on [Orb's YouTube channel](https://yt.orbclouds.com?id=606019a808e440587e87d7c5).

A number of live apps have been created using this repository, so you know it'll work 😉.

- [Colors](https://github.orbclouds.com?id=606019a808e440587e87d7c5&to=60601f8108e440587e87d7c8), a color generator app deployed [here](https://apps.orbclouds.com?id=606019a808e440587e87d7c5&to=60661c8c92b45e0abe0e055f)
- [Taxes](https://github.orbclouds.com?id=606019a808e440587e87d7c5&to=6060205308e440587e87d7c9), a progressive tax calculator app deployed [here](https://apps.orbclouds.com?id=606019a808e440587e87d7c5&to=60661c9a92b45e0abe0e0560)
- [Math](https://github.orbclouds.com?id=606019a808e440587e87d7c5&to=606be6b8ab35fd6d45a1a587), a math quiz app deployed [here](https://apps.orbclouds.com?id=606019a808e440587e87d7c5&to=606be6a9ab35fd6d45a1a586)
- [Flashcards](https://github.orbclouds.com?id=606019a808e440587e87d7c5&to=606be5e1ab35fd6d45a1a585), a flashcards app deployed [here](https://apps.orbclouds.com?id=606019a808e440587e87d7c5&to=606be5c0ab35fd6d45a1a584)
- [Clock](https://github.orbclouds.com?id=606019a808e440587e87d7c5&to=606b4f28d416365a7d038767), an analog clock app deployed [here](https://apps.orbclouds.com?id=606019a808e440587e87d7c5&to=606b4f36d416365a7d038768)

---
## Overview of Technologies Used

This repository includes a few cool technologies to help you fly through development:

1. [Snowpack](https://www.snowpack.dev), a lightning-fast frontend build tool, designed for the modern web.
2. [React](https://reactjs.org/), a JavaScript library for building user interfaces.
3. [Typescript](https://www.typescriptlang.org/), an open-source language which builds on JavaScript by adding static type definitions.
4. [PostCSS](https://postcss.org/), a tool for transforming CSS with JavaScript. Specifically, we make use of [Autoprefixer](https://autoprefixer.github.io/), a PostCSS plugin which parses your CSS and adds vendor prefixes.
5. [Google Analytics](https://analytics.google.com/), a web analytics service offered by Google that tracks and reports website traffic, currently as a platform inside the Google Marketing Platform brand. **NOTE:** Google Analytics is only enabled in production by default. We normally inject Property IDs as `ENVIRONMENT_VARIABLE`s and you can do the same using `dotenv`, which is already configured by default and works out-of-the-box in this repo. For example, create a `.env` file in the root directory of this repo like this:

```
SNOWPACK_PUBLIC_GOOGLE_ANALYTICS_ID=XXXXXXXXXX
```

The code in this repository was auto-formatted by [Prettier](https://prettier.io/), an opinionated code formatter. [ESLint](https://eslint.org/) was also very helpful!

---

## The Goals of This Repo

This repo was created as a resource for the team at Orb to rapidly develop front-ends of all kinds. We thought it would be a useful resource for everyone to use as well.

*The goal is to share a cool repository that we have found useful internally.*

If you believe that there is a tool which could add something to this repository, please let us know! We're always happy to hear from you and learn about new technologies.

---

## Get In Touch

Have a thought? Think we missed something? [Let us know!](https://www.orbclouds.com/get-in-touch?id=606019a808e440587e87d7c5) There are also many other ways to get in touch with us:

[🌐 Our Website](https://www.orbclouds.com?id=606019a808e440587e87d7c5)

[▶️  Our YouTube](https://yt.orbclouds.com?id=606019a808e440587e87d7c5)

[📸 Our Instagram](https://ig.orbclouds.com?id=606019a808e440587e87d7c5)

[🐦 Our Twitter](https://twitter.orbclouds.com?id=606019a808e440587e87d7c5)

[🇫 Our Facebook](https://fb.orbclouds.com?id=606019a808e440587e87d7c5)

[🎶 Our TikTok](https://tiktok.orbclouds.com?id=606019a808e440587e87d7c5)

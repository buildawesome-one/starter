---
permalink: /
eleventyNavigation: { key: Home, order: 1 }
---

# [One¹](//buildawesome.one/) Starter

![](https://trendshift.io/api/badge/trendshift/repositories/78215/daily?language=Nunjucks)

<big>One of the smallest and easiest to maintain starters for 11ty / Build Awesome
— perfect for blogs, docs, landing pages, or anything content-driven.</big>

Powered by [Build Awesome One¹](//buildawesome.one/) kit and [Blades CSS](//blades.dev/) micro-framework.

---

## Feel the difference

By [literally] hiding inside `.build` subfolder, it declutters the project root for your content:

<table class="borderless">
<tr><th>

https://github.com/buildawesome-one/starter

</th><th><p>vs.</p></th><th>

https://github.com/11ty/eleventy-base-blog

</th></tr>
<tr><td><!-- $ tree -L 1 -a -F --dirsfirst -I '.git' --noreport | pbcopy -->

```treeview
├── .build/
├── blog/
├── media/
├── LICENSE.md
└── README.md
```

</td><td></td><td>

```treeview
├── .github/
├── _config/
├── _data/
├── _includes/
├── content/
├── css/
├── public/
├── .editorconfig
├── .gitattributes
├── .gitignore
├── .nojekyll
├── .nvmrc
├── LICENSE
├── README.md
├── eleventy.config.js
├── netlify.toml
├── package-lock.json
├── package.json
└── vercel.json
```

</td></tr></table>
<style>
  .borderless {
    th { padding-bottom: 0; vertical-align: middle }
    pre { padding: 0; margin: 0 }
  }
</style>

---

## [Blog](/blog/) included!

---

## Local development

As simple as:

```sh
cd .build/
npm install    # dependencies
npm start      # development
npm run stage  # serve production version locally
               # ready to deploy! 🚀
```

---
permalink: /
eleventyNavigation: { key: Home, order: 1 }
---

<h1><sup style class="faded"><sub>11ty / Build Awesome<br></sub></sup><!-- <br> for GitHub only -->

[_One_](//buildawesome.one/) Starter

</h1>

<p>
  <img src="https://img.shields.io/github/v/release/buildawesome-one/starter?label=&color=darkslategray&style=for-the-badge">
  <a href="https://starter.buildawesome.one/" hidden><img src="https://img.shields.io/badge/Demo_➜-blue?style=for-the-badge"></a><!-- GitHub only -->
  <object data="https://img.shields.io/github/stars/buildawesome-one/starter?label=GitHub&labelColor=silver&color=gainsboro&style=for-the-badge"></object><!-- won't render on GitHub -->
</p>

<big>Best content-first micro-starter
powered by [Build&nbsp;Awesome&nbsp;_One_](//buildawesome.one/)&nbsp;kit
and [*Bl*ades&nbsp;CSS](//blades.dev/)
—&nbsp;perfect for blogs, docs, landing&nbsp;pages, or&nbsp;anything content-driven.</big>

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

## Local development

As simple as:

```sh
cd .build/
npm install    # dependencies
npm start      # development
npm run stage  # serve production version locally
               # ready to deploy! 🚀
```

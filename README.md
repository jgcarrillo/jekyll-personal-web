<div align="center">
    <b>⚠️⚠️ I decided to migrate the old web from Jekyll to 11ty. [Here is the code](https://github.com/jgcarrillo/jgcarrillo.github.io) ⚠️⚠️</b>
</div>
# Welcome to my personal website

## Table of contents

1. [How to install Jekyll](#1-how-to-install-jekyll)
2. [How to install plugins](#2-how-to-install-plugins)
3. [How to change the default theme](#3-how-to-change-the-default-theme)
4. [Basic directory structure](#4-basic-directory-structure)
5. [Update the Gemfile for use on GitHub Pages](#5-update-the-gemfile-for-use-on-github-pages)
6. [Plugin SEO tags](#6-plugin-seo-tags)

## 1. How to install Jekyll

1. Download Ruby+DevKit from [here](https://jekyllrb.com/docs/installation/windows/).
2. Install it.
3. Do the steps 1, 2 and 3 in order of appearance.
4. Check that everything its ok with `ruby -v`, `gem -v`
5. Do an `gem install jekyll bundler` install **bundler** and, after that, check that **Jekyl** it is installed with `jekyll -v`
6. Create a new project ` jekyll new nombre-proyecto`
7. A default directory folder was created with the _minimal_ theme.
8. Go to **Gemfile** and insert the line `gem "webrick"`
9. Do a `bundle install`
10. Do a `bundle exec jekyll serve` to create the site folder and the server.

## 2. How to install plugins

1. Go to [this website](https://jekyllrb.com/docs/plugins/your-first-plugin/).
2. Check the documentation of the plugin an add in `_config.yml` and `Gemfile` the necessary line.

## 3. How to change the default theme

We can disable the default theme by comment the appropriate line in `_config.yml` and `Gemfile`. Whe can choose our personal directory structure.

If we want to know where the default theme is, do an `bundle info --path minima`. The, with the _cd_ command go to the path to see the folders.

## 4. Basic directory structure

```
.
├── _config.yml
├── _data
│   └── members.yml
├── _drafts
│   ├── begin-with-the-crazy-ideas.md
│   └── on-simplicity-in-technology.md
├── _includes
│   ├── footer.html
│   └── header.html
├── _layouts
│   ├── default.html
│   └── post.html
├── _posts
│   ├── 2007-10-29-why-every-programmer-should-play-nethack.md
│   └── 2009-04-26-barcamp-boston-4-roundup.md
├── _sass
│   ├── _base.scss
│   └── _layout.scss
├── _site
├── .jekyll-metadata
└── index.html # can also be an 'index.md' with valid front matter
```

## 5. Update the Gemfile for use on GitHub Pages

1. First of all you need to set your appropriate GitHub Pages repository.
2. Go to your _Gemfile_ and comment the line `gem "jekyll"` and uncomment the line `gem "github-pages", group: :jekyll_plugins`
3. In the terminal execute: `bundle update github-pages`. If an error ocurred, try `bundle install` to install the necesary dependencies. After this, execute `bundle update` and finally `bundle install` again to ensure github-pages has already installed.

In some cases you only need to run `bundle update` in order to get the lastests updates of your Gemfile dependencies.

## 6. Plugin SEO tags

In order to set the appropriate SEO tags you need to install [jekyll-seo-tags](https://github.com/jekyll/jekyll-seo-tag). Be carefull with YAML sintaxys.

---

Code of my personal website [jgcarrillo.com](https://jgcarrillo.com)

-   [Jekyll](https://jekyllrb.com/)
-   Hosted in [GitHub Pages](https://github.com/)
-   [Documentation about Liquid template language](https://shopify.github.io/liquid/)

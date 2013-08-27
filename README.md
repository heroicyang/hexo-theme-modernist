# Modernist

> **Attention: Modernist has been updated to Hexo version 2.0.x. If you're still using version 1.x, please use the [1.x](https://github.com/heroicyang/hexo-theme-modernist/tree/1.x) branch.**

> Theme for [Hexo]. Based on Hexo default light theme, and [modernist theme] for Github Pages.  

[Demo the Theme]

## Install

Execute the following command and modify `theme` in `_config.yml` to `modernist`.

```
git clone git://github.com/heroicyang/hexo-theme-modernist.git themes/modernist
```
For Hexo 1.x:

```
git clone -b 1.x git://github.com/heroicyang/hexo-theme-modernist.git themes/modernist
```

## Update

Execute the following command to update Modernist.

```
cd themes/modernist
git pull
```
For Hexo 1.x:

```
cd themes/modernist
git pull origin 1.x
```

## Config

Default config:

``` yaml
menu:
  Home: /
  Archives: /archives

excerpt_link: Read More
archive_yearly: false

widgets:
  - category
  - tag
  - tagcloud
  - recent_posts
  - blogroll

blogrolls:
  - Heroic Yang's Blog: http://heroicyang.com/

fancybox: true

duoshuo_shortname:

google_analytics:
rss:
```

- **menu** - Main navigation menu
- **excerpt_link** - "Read More" link text at the bottom of excerpted articles
- **archive_yearly** - Enable archives grouped by year, only for nonpaged (set the pagination config: `archive: 1`)
- **widgets** - Widgets displaying in sidebar
- **blogrolls** - Blogrolls displaying in `blogroll` widget
- **fancybox** - Enable [Fancybox]
- **duoshuo_shortname** - [Duoshuo] ID
- **google_analytics** - Google Analytics ID
- **rss** - RSS subscription link (change if using Feedburner)

[Hexo]: http://zespia.tw/hexo/
[modernist theme]: https://github.com/orderedlist/modernist
[Demo the Theme]: http://heroicyang.com/
[Duoshuo]: http://duoshuo.com
[Fancybox]: http://fancyapps.com/fancybox/

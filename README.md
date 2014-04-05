# Modernist

> Theme for [Hexo]. Based on [modernist theme] for GitHub Pages.

[Demo the Theme]

## Install

```
git clone git://github.com/heroicyang/hexo-theme-modernist.git themes/modernist
```

**Modernist requires Hexo 2.4 and above.**

## Enable
Modify `theme` setting in `_config.yml` to `modernist`.

## Update

```
cd themes/modernist
git pull
```

## Configuration

``` yaml
# Header
menu:
  Home: /
  Archives: /archives
rss: /atom.xml

# Content
archive_date_format: MMM DD
fancybox: true

# Comment Plugin
duoshuo_shortname:

# Miscellaneous
google_analytics:
favicon: /favicon.ico
```

- **menu** - Navigation menu
- **rss** - RSS link
- **archive_date_format** - Date format in archives page.
- **fancybox** - Enable [Fancybox]
- **duoshuo_shortname** - [Duoshuo] ID
- **google_analytics** - Google Analytics ID
- **favicon** - Favicon path

[Hexo]: http://zespia.tw/hexo/
[modernist theme]: https://github.com/orderedlist/modernist
[Demo the Theme]: http://heroicyang.com/
[Duoshuo]: http://duoshuo.com
[Fancybox]: http://fancyapps.com/fancybox/

title: Bells and whistles
date: 2015-06-28 15:04:27
tags: hexo
---
## Atom feed
As simple as:
``` bash
$ npm install hexo-generator-feed --save
```

``` yaml _config.yml
feed:
  type: atom
  path: atom.xml
  limit: 20
```

## Comments
All through my hexo initiation, [this guy's tutorial](http://jr0cket.co.uk/hexo/configure-your-hexo-website.html) was very helpful.
Thanks to him, I discovered [disqus](https://disqus.com/).
``` yaml _config.yml
disqus_shortname: your_disqus_name
```

## Banner
Do a `hexo clean` and change banner-url in themes/landscape/source/css/_variables.styl.

## Code highlighting
Well, it doesn't work out of the box

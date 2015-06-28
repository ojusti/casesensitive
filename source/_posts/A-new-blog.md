title: A new blog
date: 2015-06-27 22:38:25
tags: hexo
---
## Choose a platform
* Google `programmer friendly blogging`
* Read [10 Open Source Blogging Platforms for Developers](http://sixrevisions.com/tools/open-source-blogging-platforms-for-developers)
* Google `hexo vs octopress`
* Read [Octopress vs Hexo](http://www.techelex.org/octopress-vs-hexo)
* All the others results on the 1st page were `from octopress to hexo`-like too
* I want to learn javascript

I choose hexojs.

## Installation
* [Hexo's official tutorial](https://hexo.io/docs)
* I have git, I need nodejs
* Google `nodejs ubuntu install`
* Read [How To Install Node.js on an Ubuntu 14.04 server](https://www.digitalocean.com/community/tutorials/how-to-install-node-js-on-an-ubuntu-14-04-server)
* Follow `How To Install Using a PPA` as I would like to have a newer version
``` bash
$ curl -sL https://deb.nodesource.com/setup | sudo bash -
$ sudo apt-get install nodejs
```
* Install hexo using npm
``` bash
$ sudo npm install -g hexo-cli
```

## First post
* Init site folder
``` bash
$ hexo init site
INFO  Copying data to ~/work/site
INFO  You are almost done! Don't forget to run 'npm install' before you start blogging with Hexo!
$ sudo npm install
```
* Change _config.yml, modify title, author and url
* Start writing this "tutorial"
```bash
$ hexo new "A new blog"
```
* Preview
``` bash
$ hexo server
```

## Deploy
* Follow [hexo's doc](https://hexo.io/docs/deployment.html) and [this tutorial](http://rabbi.xyz/Getting-Started-With-Hexo-Deploying-On-Github-Pages/) to deploy to github.
* Deploy type should be `git` not `github`
``` bash
$ hexo generate --deploy
```

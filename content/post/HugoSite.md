---
title: "HugoSite"
date: 2018-10-02T08:39:27-04:00
draft: false
---

Will document build of site here

Some background info on default directory layout:


* archetypes: here we define what our content is, we can set default tags or categories and define types such as a post, tutorial or product here
* config.toml: main configuration is in here, we can define all of the websites title, language, urls etc here
* content: the content pages of the site are stored here, sub directories are used for sections to help organize the content, create a content/products for your products content for example
* data: Site data such a localization configurations go here
* layouts: layouts for the Go html/template library which Hugo utilizes go here
* static: Any static files here will be compiled into the final website, total freedom is allowed so you can serve any css,js or image file for example.
* themes: Create new themes or clone themes from github into this directory to use them with your site.

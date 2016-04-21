# hexo-footnotes

![travis build status](https://travis-ci.org/LouisBarranqueiro/hexo-footnotes.svg?branch=master)

A plugin to support markdown footnotes in Hexo posts

## Syntax

#### Mardown
```
basic footnote[^1]
here is an inline footnote[^2](inline footnote)
and another one[^3]
and another one[^4]

[^1]: basic footnote content
[^3]: paragraph
footnote
content
[^4]: footnote content with some [markdown](https://en.wikipedia.org/wiki/Markdown)
```
#### Output
![footnotes](https://raw.githubusercontent.com/LouisBarranqueiro/hexo-footnotes/master/screenshot.png?token=AEfNWh_U1kEIyTb8euyeYHgEvmcXxXtrks5XIflWwA%3D%3D)

## Installation

```
npm install hexo-footnotes --save
```

If Hexo detect automatically all plugins, that's all.  

If that is not the case, register the plugin in your `_config.yml` file :
```
plugins:
  - hexo-footnotes
```

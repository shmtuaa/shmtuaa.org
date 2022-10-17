---
permalink: /blog_template
title: 这里写TITLE
author: chair
layout: post
excerpt: 这里写摘要，不写的话就是文章的前150字。
---

如果不写摘要，最前面的这几段最好不要出现标题。

<!-- more -->

这个标记代表摘要的终止，标记本身不会被渲染。

你会拥有自己的主页，主页的地址是https://shmtuaa.org/你的作者id。

请参考[这个链接](https://help.github.com/articles/basic-writing-and-formatting-syntax)写作。

引用的素材请放在`/assets/作者id/`的目录下，引用素材很简单，比如[这样](/assets/css/primer.css)就会转到网站所使用的primer css内容。引用请在单独开一个作者的文件夹，比如assets/caa/...。

引用其他文章可以[这样]({% post_url 2022-10-01-MAIN-description %})。

这篇文章的源代码可以见[本网站的代码](https://github.com/shmtuaa/shmtuaa.org)中`_posts/2022-10-01-MBER-template.md`，文件前缀需要是`年年年年-月月-日日-MBER-`。

不要忘记写上自己的邮箱，比如[chair@shmtuaa.org](mailto:chair@shmtuaa.org)，你的邮箱名字一般是博客id。

一般的博客请不要在Markdown最前面写`permalink`一栏。

引用代码

```python
print("123")
```

欢迎开设自己的博客，请联系你所在学生组织的社长/主任/主席/~~头号人物~~。

## 未来可能会更新的

还有一些东西，详见[这个链接](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/creating-diagrams)。

```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```

```geojson
{
  "type": "FeatureCollection",
  "features": [
    {
      "type": "Feature",
      "id": 1,
      "properties": {
        "ID": 0
      },
      "geometry": {
        "type": "Polygon",
        "coordinates": [
          [
              [-90,35],
              [-90,30],
              [-85,30],
              [-85,35],
              [-90,35]
          ]
        ]
      }
    }
  ]
}
```

```stl
solid cube_corner
  facet normal 0.0 -1.0 0.0
    outer loop
      vertex 0.0 0.0 0.0
      vertex 1.0 0.0 0.0
      vertex 0.0 0.0 1.0
    endloop
  endfacet
  facet normal 0.0 0.0 -1.0
    outer loop
      vertex 0.0 0.0 0.0
      vertex 0.0 1.0 0.0
      vertex 1.0 0.0 0.0
    endloop
  endfacet
  facet normal -1.0 0.0 0.0
    outer loop
      vertex 0.0 0.0 0.0
      vertex 0.0 0.0 1.0
      vertex 0.0 1.0 0.0
    endloop
  endfacet
  facet normal 0.577 0.577 0.577
    outer loop
      vertex 1.0 0.0 0.0
      vertex 0.0 1.0 0.0
      vertex 0.0 0.0 1.0
    endloop
  endfacet
endsolid
```
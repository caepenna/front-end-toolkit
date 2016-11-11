---
layout: content
title:  "Libraries"
permalink: /contents/libraries
description: The libraries that we use
---

## JQuery

JQuery is an open source JavaScript librabry designed to simplify HTML document traversing,
event handling, animating, and Ajax interactions. Its slogan is **"Write less, do more"**.

Here are some advantages of using JQuery:

- Is lightweight and easy to use;
- Handles cross-browser issues;
- Is extensible and has a wide range of official and third-party plug-ins;
- Is constantly evolved and has an active community.

You can find more information and download the library in this [link](http://learn.jquery.com/).

## Select2

## C3
C3JS is a library to make charts, they are a excelent option to front end designers with little or no experience in JS. Is realy easy to install and use.
It's possible just make simple graphics like bar charts, line charts, donut charts.
The possibility of configuration is just for data values, colors and animations time.

**Example:**

```js
var chart = c3.generate({
    bindto: '#chart',
    data: {
      columns: [
        ['data1', 30, 200, 100, 400, 150, 250],
        ['data2', 50, 20, 10, 40, 15, 25]
      ]
    }
});
```

If you need a big customisation C3 isn't recommended. In this case, will be better use D3JS, but this tool is more complex and require a good level of knowledge in javascript.

## Bourbon

Bourbon is a mixin library usefull for saving time when setting most used mixins on your project.

It can be installed as a gem if you are working on a rails project, and can easily be installed via `$ gem install bourbon` if you are on a non-rails app.

Basically, Bourbon creates a file with mixins you can use on your project. You can check out all the mixins available on Bourbon on their [documentation page](http://bourbon.io/docs/).

Bourbon is simple, lightweight and definitely worth using. However you could replace Bourbon with a `mixins.scss` file if you don't want to rely on dependencies or just don't want to have it on your project.

Here are some example of Bourbon's mixins in use:

```scss
.element {
  @include directional-property(border, width, 10px null 4px 3px);
}
```

Which outputs the following CSS:

```css
.element {
  border-top-width: 10px;
  border-bottom-width: 4px;
  border-left-width: 3px;
}
```

It also has handy prefixer mixins such as:

```scss
@mixin box-sizing($box) {
  @include prefixer(box-sizing, $box, webkit moz spec);
}

.element {
  @include box-sizing(border-box);
}
```

Which outputs the following CSS:

```css
.element {
  -webkit-box-sizing: border-box;
     -moz-box-sizing: border-box;
          box-sizing: border-box;
}
```

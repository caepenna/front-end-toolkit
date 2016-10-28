---
layout: content
title:  "Libraries"
permalink: /contents/libraries
description: The libraries that we use
---

## JQuery

## Select2

## C3

## Bourbon

Bourbon is a mixin library usefull for saving time when setting most used mixins on your project.

It can be installed as a gem if you are working on a rails project, and can easily be installed via `$ gem install bourbon` if you are on a non-rails app.

Basically, Bourbon creates a file with mixins you can use on your project. You can check out all the mixins available on Bourbon on their [documentation page](http://bourbon.io/docs/).

Bourbon is simple, lightweigh and definetly worth using. However you could replace Bourbon with a `mixins.scss` file if you don't want to rely on dependencies or just don't want to have it on your project.

Here are some example of Bourbon's mixins in use:

```scss
  @include directional-property(border, width, 10px null 4px 3px);
```

Which outputs the following CSS:

```css
  border-top-width: 10px;
  border-bottom-width: 4px;
  border-left-width: 3px;
```

It also has handy prefixer mixins such as:

```scss
@mixin box-sizing($box) {
  @include prefixer(box-sizing, $box, webkit moz spec);
}
```

Which outputs the following CSS:

```css
-webkit-box-sizing: $box;
   -moz-box-sizing: $box;
        box-sizing: $box;
```

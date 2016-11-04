---
layout: content
title:  "Libraries"
permalink: /contents/libraries
description: The libraries that we use
---

## JQuery

## Select2

## C3
C3JS is a library to make charts, they are a excelent option to front end designers with little or no experience in JS. Is realy easy to install and use.
It's possible just make a simple graphics like bar charts, line charts, donut charts.
The possibility of configuration is just for data values, colors and time of animations.

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

Is a good option to prototype with simple charts. If you need a big customization C3 isn't recomended, it's better use D3JS in this case, but D3 is realy complex and need a good level of knowledge in javascript.

## Bourbon

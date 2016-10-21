---
layout: content
title:  "Grid Framework"
permalink: /contents/grid-framework
description: The grid systems that we use
---

Grid Systems help us to keep the project content organized and make our job quicker.

We will explain about two different solutions that we use.
The first is the grid framework that our team create.
The second is Neat, the grid framework of Bourbon.

## Flama Grid Framework

We decided to build our own column grid system because we want more flexibility.
We created an easy way to customize all variables that envolves a grid,
such as gutter size, numbers of columns and column width.
You can also include custom settings for different screen devices.

**Example:**

```sass
$nOfColumns: 12
$gutter: 1rem
$columnWidth: ( 100%/#{$nOfColumns} - #{$gutter} )

$nOfColumnsMobile: 4
$gutterMobile: .5rem
$columnWidthMobile: ( 100%/#{$nOfColumnsMobile} - #{$gutterMobile} )
```

The Flama Grid Framework is easy to install and config. Is semantic and clean.
If you want informations about how use it you can go to the [repository](https://github.com/flama).

## Neat

The other tool that we like to use is Neat.
Is a lightweight semantic grid framework for Sass and Bourbon.
Is simple, responsive and easy to install.

One of the biggest reason why we use Neat is because it promotes clean and semantic markup, without classes and extra wrapping divs.

**Example:**

```sass
sidebar { @include span-columns(3); }
article { @include span-columns(9); }
```

When you add the mixins above, your sidebar will automatically have three columns and your article nine columns.

The only issue that we don't like is the amount of CSS attributes generated when you use those mixins.
As an example, if you add a span-columns in all childrens of a div they will have a float attribute.
The div will not have height and you will have to you use a clearfix.


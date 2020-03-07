---
title: A post with example embeds and images
date: '2020-03-07'
tags:
  - images
  - content
  - embeds
  - code
---

## Embedded elements


This post contains `iframe` embedded elements, wrapped inside of a CSS class. That allows you to add custom styles to match the visual look of embeds better for your needs. You can customize the CSS class name by adjusting `iframesClass` from the main `config.json` file. Here is an example of a CodePen embed.

<iframe height="265" style="width: 100%;" scrolling="no" title="CSS Shapes experiment (webkit only)" src="https://codepen.io/rachsmith/embed/dBrFv?height=265&theme-id=light&default-tab=js,result" frameborder="no" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href='https://codepen.io/rachsmith/pen/dBrFv'>CSS Shapes experiment (webkit only)</a> by Rachel Smith
  (<a href='https://codepen.io/rachsmith'>@rachsmith</a>) on <a href='https://codepen.io'>CodePen</a>.
</iframe>

## Images and pictures

This starter uses a custom transformer to parse `markdown` content and improve it. An example of this are the images. If you add an image with title to your markdown, it will be replaced with a `<picture>` element, and the title is placed as `<figcaption>` in order to keep a basic semantic structure.

**The following image code is:**

`![Alt](https://cdn.pixabay.com/photo/2013/08/09/05/52/umbrella-170962_960_720.jpg 
'Image of person looking out to the sea. Grey monochromatic with purple umbrella')`

![Alt](https://cdn.pixabay.com/photo/2013/08/09/05/52/umbrella-170962_960_720.jpg 'Image of person looking out to the sea. Grey monochromatic with purple umbrella')

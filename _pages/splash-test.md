---
title: "Bienvenido"
layout: splash
permalink: /splash
# author_profile: true
header:
  # image: assets/images/header1.jpg
  overlay_image: /assets/images/header1.jpg
  # overlay_filter: 0.5 # same as adding an opacity of 0.5 to a black background
  overlay_filter: linear-gradient(rgba(255, 0, 0, 0.5), rgba(0, 255, 255, 0.5))
  caption: "Photo by <a href='https://unsplash.com/@marekpiwnicki?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText'>Marek Piwnicki</a> on <a href='https://unsplash.com/t/nature?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText'>Unsplash</a>"
  actions:
    - label: "Más info:"
      url: "https://unsplash.com"
  intro:
    - excerpt: 'Esto es una prueba'
# feature_row:
 #   - image_path: /assets/images/marek-piwnicki-6JX47S9SMRs-unsplash.jpg
  #  alt: "placeholder image 1"
   # title: "Placeholder 1"
   # excerpt: "This is some sample content that goes here with **Markdown** formatting."
   # - image_path: /assets/images/nikhil-l_g6a902OH8-unsplash.jpg
   # image_caption: "Image courtesy of [Unsplash](https://unsplash.com/)"
   # alt: "placeholder image 2"
   # title: "Placeholder 2"
   # excerpt: "This is some sample content that goes here with **Markdown** formatting."
   # url: "#test-link"
   # btn_label: "Leer más"
   # btn_class: "btn--primary"
prueba_var: "Prueba variable" 
---

<h1> {{ "Hello World" | downcase }} </h1>

## Hola...

Lorem ipsum
![yaktocat](https://octodex.github.com/images/yaktocat.png)

{{ page.prueba_var }}

{% include feature_row id="intro" type="center" %}

{% include video id="212731897" provider="vimeo" %}

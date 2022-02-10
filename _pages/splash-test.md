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
feature_row:
  - image_path: /assets/images/marek-piwnicki-6JX47S9SMRs-unsplash.jpg
    alt: "placeholder image 1"
    title: "Placeholder 1"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
  - image_path: /assets/images/nikhil-l_g6a902OH8-unsplash.jpg
    image_caption: "Image courtesy of [Unsplash](https://unsplash.com/)"
    alt: "placeholder image 2"
    title: "Placeholder 2"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
    url: "#test-link"
    btn_label: "Leer más"
    btn_class: "btn--primary"
  - image_path: /assets/images/foo-bar-identity-th.jpg
    alt: "placeholder image 3"
    title: "Unreal VR"
    excerpt: "Algunos proyectos recientes"
feature_row2:
  - image_path: /assets/images/unsplash-gallery-image-1-th.jpg
    alt: "unsplash"
    title: "Hello there"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Left aligned with `type="left"`'
feature_row3:
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "prueba row"
    title: "Idea"
    excerpt: "Más enlaces a ninguna parte"
    url: "/about"
    btn_label: "Acerca de"
    btn_class: "btn--primary"   
prueba_var: "Prueba variable" 
---

<h1> {{ "Hello World" | downcase }} </h1>

## Hola...

Lorem ipsum
![yaktocat](https://octodex.github.com/images/yaktocat.png)

{{ page.prueba_var }} {{ site.time | date_to_string }}

{% include feature_row id="intro" type="center" %}

{% include feature_row %}

{% include video id="212731897" provider="vimeo" %}

{% include feature_row id="feature_row2" type="left" %}

{% include feature_row id="feature_row3" type="right" %}

{{ site.time | date_to_long_string}}

{% highlight ruby %}
def foo
  put 'foo'
end
{% endhighlight %}

{% assign image_files = site.static_files | where: "image", true %}

{% for myimage in image_files %}

  {{myimage.path}}

{% endfor %}

<h3 class="archive__subtitle">{{ site.data.ui-text[site.locale].recent_post | default: "Recent" }}</h3>
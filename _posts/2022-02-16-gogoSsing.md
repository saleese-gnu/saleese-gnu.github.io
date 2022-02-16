---
author: 블로그 관리자
type: gallery
featimg:
title: 고고씽 [2021]
tags: [android, scooter]
category: [app, demo vedio]
gallery:
    - images:
      - filename: gallery-1.jpg
        alttext: Bloom Flat
      - filename: gallery-2.jpg
        alttext: Bloom
      - filename: gallery-3.jpg
        alttext: Blossom in a Star
      - filename: gallery-4.jpg
        alttext: Blossom
      - filename: gallery-5.jpg
        alttext: Bubbly Bloom
      - filename: gallery-6.jpg
        alttext: Rays of Gold
      - filename: gallery-7.jpg
        alttext: Exotic
      - filename: gallery-8.jpg
        alttext: Filled out
---
Here you'll find a simple gallery, that just adds all of the images at full-width directly in the post content.

<br>

###### Demo Video
<video controls preload="auto">
  <source src="\videos\2022_gogo_ssing.mp4" type="video/mp4">
  현재 브라우저가 동영상을 지원하지 않습니다.
</video>

<br>

###### front matter

```yml
---
type: gallery
gallery:
    - images:
      - filename: gallery-1.jpg
        alttext: Bloom Flat
      - filename: gallery-2.jpg
        alttext: Bloom
      - filename: gallery-3.jpg
        alttext: Blossom in a Star
      - filename: gallery-4.jpg
        alttext: Blossom
      - filename: gallery-5.jpg
        alttext: Bubbly Bloom
      - filename: gallery-6.jpg
        alttext: Rays of Gold
      - filename: gallery-7.jpg
        alttext: Exotic
      - filename: gallery-8.jpg
        alttext: Filled out
---
```
<br>

###### post content

``` liquid
{% raw  %}
{% include gallery.html %}
{% endraw %}
```

{% include gallery.html %}
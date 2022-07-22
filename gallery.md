---
layout: page
title: Gallery
image: /assets/images/splash.png
description: Shame them into mass-adoption!
---

Make sure to use [#FuckingShitcoins][hashtag] on twitter to spread the word!

<small>Bonus points if you sign every card with the current [Moscow Time!][mt]</small>

{% for image in site.static_files %}
{% if image.path contains 'images/gallery' %}
{% include image.html path=image.path width='100%' %}
{% endif %}
{% endfor %}

---

[<< Back](/)

[mt]: https://twitter.com/moscowTimeBot/
[hashtag]: https://twitter.com/hashtag/FuckingShitcoins

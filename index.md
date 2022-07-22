---
layout: splash
title: Fucking Shitcoins
image: /assets/images/splash.png
description: Shame them into mass-adoption!
---

{% include image.html path='/assets/images/splash.png' width='100%' %}

# Received a card?

Well, that sucks. It means that a customer of yours wanted to pay you using the best money humanity ever had, and you refused it. Ooof.

Here is what you can do:

- Learn about the benefits of accepting sats<br/>
  <small>TLDR: Near 0% transaction fees, near-instant settlement, no chargebacks.</small>
- [Understand why][wtf] the money you received is a shitcoin
- [Set yourself up][local] to receive sats
- [Follow the white rabbit! 🐇][br]

[wtf]: https://wtfhappenedin1971.com/
[local]: https://bitcoinforlocalbusiness.com/
[br]: https://bitcoin-resources.com

# Want to shame someone else?

Go ahead! Download one of the PDFs below and print it yourself. The cards are business-card-sized, so it should be easy enough. Also: feel free to translate them, remix them, and make them your own!

{% for image in site.static_files %}
{% if image.path contains 'files/pdfs' %}
- [{{ image.name }}]({{ image.path }})
{% endif %}
{% endfor %}

[View the gallery](/gallery) to see how the cards look like in meatspace.

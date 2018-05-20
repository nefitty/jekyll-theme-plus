---
layout: help
title: How Can We Help You?
subtitle: Self Help Support
hero:
    background: "#ffffff"   # background color, note setting a background image below will overlay the background color
    image: ocean.jpg        # local image e.g ocean.jpg from /assets/posts/ folder or remote e.g https://source.unsplash.com/ZeXP6p7agjE
    align: top              # header image alignment e.g. top, center or bottom
    text: dark              # text color e.g. dark or light
    search: true            # enable search
category:
    columns: 3              # number of category columns; 1, 2, 3, 4
featured:
    title: Featured Articles
    tag: featured           # tag used to populate featured section on home page
---

{% include cards.html id="home-why" style="default" media="top" section="muted" align="center" title="Why switch to Jekyll" %}

{% include features.html id="feature" section="default" align="center" title="Awesome Features" %}

{% include cta title="Support continuous development of this theme with your contribution" button_text="Support Us" button_url="https://www.paypal.me/ivanchromjak" blank="true" section="primary" %}




<!--

{% include cards.html id="home-right" style="" media="right" section="muted" %}

{% include cards.html id="home-next" style="primary" align="center" section="muted" %}

{% include instagram.html count="8" section="default" %}

background-image: linear-gradient(to right, #0acffe 0%, #495aff 100%);
background-image: linear-gradient(-225deg, #AC32E4 0%, #7918F2 48%, #4801FF 100%);
background-image: linear-gradient(-225deg, #A445B2 0%, #D41872 52%, #FF0066 100%); -->

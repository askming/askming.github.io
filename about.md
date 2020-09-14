---
layout: default
title: "about"
permalink: /about/
---
{%- assign social = site.minima.social_links -%}
{%- include latex.html -%}

## about me

- **Doing for living**: [biostatistics](https://en.wikipedia.org/wiki/Biostatistics)
- **Hobby**: reading, sports, photography, learning
- **Social networks**: <a rel="me" href="https://www.linkedin.com/in/{{ social.linkedin | cgi_escape | escape }}" title="{{ social.linkedin | escape }}"><svg class="svg-icon grey"><use xlink:href="{{ '/assets/linkedin.svg#linkedin'  | relative_url }}"></use></svg></a> <a rel="me" href="https://twitter.com/{{ social.twitter | cgi_escape | escape }}" title="{{ social.twitter | escape }}"><svg class="svg-icon grey"><use xlink:href="{{ '/assets/twitter.svg#twitter' | relative_url }}"></use></svg></a> <a rel="me" href="https://t.me/{{ social.telegram | cgi_escape | escape }}" title="{{ social.telegram | escape }}"><svg class="svg-icon grey"><use xlink:href="{{ '/assets/telegram.svg#telegram' | relative_url }}"></use></svg></a>
- **Get in touch** $\Rightarrow$ {{site.email}}

<br />

$$
l\text{ife} = \int_{\text{born}}^{\text{death}} \text{study} dt
$$






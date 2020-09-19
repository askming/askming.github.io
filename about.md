---
layout: default
title: "about"
permalink: /about/
---
{%- assign social = site.minima.social_links -%}
{%- include latex.html -%}
{%- include customfonts.html -%}

## about me
混迹于北美大陆的浙江人。

大学时代博客正流行，我也随大流开启自己的第一个博客。期间写写停停，在不同平台间兜兜转转，到如今曾经的轨迹丢失得支离破碎，几乎没剩下什么。在此站之前的最后一站--Blogspot上还保存着一些08年到11年间的让自己看着都尴尬的“幼稚篇章”，勉强可以算是硕果仅存。其实心底一直还是想拥有一个属于自己的独立博客，用来记录属于自己的生活经历，思考和记忆。虽然已经断了的时间线已经不能回头再去连上, 但是能够回头看看曾几何时幼稚的自己留下的点点痕迹又何尝不是一种让人快乐的财富呢?
                                            
<div style="text-align: right; color:grey" > 2020年9月 </div>

- **Do for living**: [biostatistics](https://en.wikipedia.org/wiki/Biostatistics)
- **Hobbies**: 读书(慢)，(看)篮球，拍照，学新东西
- **Social networks**: <a rel="me" href="https://www.linkedin.com/in/{{ social.linkedin | cgi_escape | escape }}" title="{{ social.linkedin | escape }}"><svg class="svg-icon grey"><use xlink:href="{{ '/assets/linkedin.svg#linkedin'  | relative_url }}"></use></svg></a> <a rel="me" href="https://twitter.com/{{ social.twitter | cgi_escape | escape }}" title="{{ social.twitter | escape }}"><svg class="svg-icon grey"><use xlink:href="{{ '/assets/twitter.svg#twitter' | relative_url }}"></use></svg></a> <a rel="me" href="https://t.me/{{ social.telegram | cgi_escape | escape }}" title="{{ social.telegram | escape }}"><svg class="svg-icon grey"><use xlink:href="{{ '/assets/telegram.svg#telegram' | relative_url }}"></use></svg></a>
- **Get in touch** $\Rightarrow$ {{site.email}}

<br />

$$
\sim \text{life} = \int_{\text{birth}}^{\text{death}} \text{study} dt \sim
$$

{%- include disque.html -%}
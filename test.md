---
layout: page
title: Test
permalink: /test/
---
testing stuffs here:

{%- assign social = site.minima.social_links -%}

{{ social }}

{%- if social.instagram -%}<li><a href="https://www.instagram.com/{{ social.instagram | cgi_escape | escape }}" title="{{ social.instagram | escape }}"><svg class="svg-icon grey"><use xlink:href="{{ '/assets/minima-social-icons.svg#instagram' | relative_url }}"></use></svg></a></li>{%- endif -%}

## inc
{%- include social.html -%}

---
layout: page
permalink: /about/
---

This is the base Jekyll theme. You can find out more info about customizing your Jekyll theme, as well as basic Jekyll usage documentation at [jekyllrb.com](https://jekyllrb.com/)

You can find the source code for Minima at GitHub:
[jekyll][jekyll-organization] /
[minima](https://github.com/jekyll/minima)

You can find the source code for Jekyll at GitHub:
[jekyll][jekyll-organization] /
[jekyll](https://github.com/jekyll/jekyll)

[jekyll-organization]: https://github.com/jekyll

<ul class="contact-list">
    {%- if site.email -%}
    <li><a class="u-email" href="mailto:{{ site.email }}">{{ site.email }}</a></li>
    {%- endif -%}
    {%- if site.street -%}
    <li class="footer-street">{{ site.street }}</li>
    {%- endif -%}
</ul>

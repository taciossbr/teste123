# capitulo 1

<ul>
{% for page in site.collections.legal.docs %}
  <li><a href="{{ page.url }}">{{ page.title }}</a></li>
{% endfor %}
</ul>

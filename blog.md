### Dowiedz się więcej
{% assign posts = site.posts | slice: 0, 3 %}
<ul>
{% for post in posts %}
  <li><a href="{{ post.url | relative_url }}">{{ post.title }}</a> <small>— {{ post.date | date: "%Y-%m-%d" }}</small></li>
{% endfor %}
</ul>

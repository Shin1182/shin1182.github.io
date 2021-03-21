

* Hi, welcome!

{% for post in site.posts %}
  <ul>
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  </ul>
  {{ post.excerpt | truncate: 50 }}
{% endfor %}

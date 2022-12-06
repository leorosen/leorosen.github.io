# leorosen.github.io
Leonid Rosenboim Personal Blog
Updated: 2022-12-05

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

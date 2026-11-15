## About

This page serves as a simple second brain for me to store and retrieve notes. Feel free to stick around, but don't expect too regular updates.


<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
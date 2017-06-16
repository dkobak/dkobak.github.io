<ul>
  {% for post in site.posts %}
      <a href="{{ post.url }}">{{ post.title }}</a>
      {{ post.excerpt }}

      {% if post.excerpt != post.content %}
         <p><a href="{{ site.baseurl }}{{ post.url }}" style="font-weight:bold">Read more</a></p>
      {% endif %}
  {% endfor %}
</ul>

{% for post in site.posts %}
    {{ post.excerpt }}
    
    {% if post.excerpt != post.content %}
    <a href="{{ site.baseurl }}{{ post.url }}" style="font-weight:bold">Read more</a>
    {% endif %}
    
    <hr>
{% endfor %}

<hr>

<ul>
  {% for post in site.posts %}
    <li>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>

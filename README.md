{% for post in site.posts %}
    {{ post.excerpt }}
    
    {% if post.excerpt != post.content %}
    <a href="{{ site.baseurl }}{{ post.url }}" style="font-weight:bold">Read more</a>
    {% endif %}
    
    <hr>
{% endfor %}

<hr>

  {% for post in site.posts %}
      <p>Boo</p>
      {{ post.excerpt }}
  {% endfor %}

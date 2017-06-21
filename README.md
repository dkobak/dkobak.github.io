{% for post in site.posts %}
{% unless post.draft %}
{{ post.excerpt }}

{% if post.excerpt != post.content %}
<p><a href="{{ site.baseurl }}{{ post.url }}" style="font-weight:bold">CONTINUE READING</a></p>
{% endif %}
  
<hr>
{% endunless}
{% endfor %}

{% for post in site.posts %}
{% unless post.draft %}

<h2>{{ post.title }}</h2>
<p style="color:grey; margin-top:-1em; font-weight:bold">{{ post.date | date_to_long_string }}</p>

{{ post.excerpt }}

{% if post.excerpt != post.content %}
<p><a href="{{ site.baseurl }}{{ post.url }}" style="font-weight:bold">CONTINUE READING</a></p>
{% endif %}
  
<hr>
{% endunless %}
{% endfor %}

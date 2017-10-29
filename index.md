<div>
  {% for post in site.posts %}
    <div>
      <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
      {{ post.excerpt }}
    </div>
  {% endfor %}
</div>

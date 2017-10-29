<div>
  {% for post in site.posts %}
    <div>
      <h4><a href="{{ post.url }}">{{ post.title }}</a></h4>
      ![alt text]({{ post.img }}) {{ post.excerpt }}
    </div>
  {% endfor %}
</div>

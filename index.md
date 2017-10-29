<div class="posts">
  {% for post in site.posts %}
    <div class="post">
      <h4><a href="{{ post.link }}">{{ post.title }}</a></h4>  
      ![My helpful screenshot]({{ post.img }})
      <p>{{ post.text }}</p>
    </div>
  {% endfor %}
</div>

<div class="posts">
  {% for post in site.posts %}
    <div class="post">
      <h4><a href="{{ post.link }}">{{ post.title }}</a></h4>  
      <img src="{{ post.img }}"></img>
      <p>{{ post.text }}</p>
    </div>
  {% endfor %}
</div>

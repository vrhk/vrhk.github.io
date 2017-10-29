<div>
  {% for post in site.posts %}
    <div>
      <h4><a href="{{ post.link }}">{{ post.title }}</a></h4>  
      <img src={{ post.img }} style="height: 2em;"></img>
      <p>{{ post.text }}</p>
    </div>
  {% endfor %}
</div>

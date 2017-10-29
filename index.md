<article class="posts">
  {% for post in site.posts %}
    <div class="post">
      <div class="thumb">
        <img src="{{ post.img }}">
      </div>
      <div class="post">
        <h4><a href="{{ post.link }}">{{ post.title }}</a></h4>  
        <p><span class="source">{{ post.source }}</span> {{ post.text }}</p>
      </div>
    </div>
  {% endfor %}
</article>

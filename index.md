<article class="posts">
  {% for post in site.posts %}
    <div class="post">
      <div class="thumb">
        <img src="{{ post.img }}">
      </div>
      <header class="post">
        <h4><a href="{{ post.link }}">{{ post.title }}</a></h4>  
        <p><span class="source">{{ post.source }}</span> {{ post.text }}</p>
      </header>
      <footer>
      </footer>
    </div>
  {% endfor %}
</article>

<div class="posts">
  {% for post in site.posts %}
    <div>
      <article class="post">
        <a href="{{ post.link }}">
          <div class="thumb">
            <img src="{{ post.image }}">
          </div>
          <header class="content">
            <p class="title"><span class="source">{{ post.name }}</span>  {{ post.title }}</p>
            <p class="text">{{ post.text }}</p>
          </header>
          <footer>
            <p></p>
          </footer>
        </a>
      </article>
    </div>
  {% endfor %}
</div>

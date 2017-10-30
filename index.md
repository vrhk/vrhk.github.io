<div class="posts">
  {% for post in site.posts %}
    <div>
      <article class="post">
        <a href="{{ post.link }}">
          <div class="thumb">
            <img src="{{ post.image }}">
          </div>
          <header class="content">
            <p class="title">{{ post.title }}</p>
            <p><span class="source">{{ post.source }}</span> {{ post.text }}</p>
          </header>
          <footer>
            <p>{{ post.name }}</p>
          </footer>
        </a>
      </article>
    </div>
  {% endfor %}
</div>

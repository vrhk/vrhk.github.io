<div>
  {% for post in site.posts %}
    <div>
      <h4><a href="{{ post.link }}">{{ post.title }}</a></h4>  
      ![alt text]({{ post.img }} {{ post.title }})  
      {{ post.text }}  
    </div>
  {% endfor %}
</div>

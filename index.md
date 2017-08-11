Welcome to a written journal of the trials and tribulations in the ownership of a Suzuki Jimny.

I hope to use this blog to serve as a record of its life in my care. From its purchase, until its eventual death upon the scrap heap.

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>
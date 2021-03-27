<ul>
  {% for post in site.posts %}
    <li>
        <h3>
          <a class="post-link" href="{{ post.url | relative_url }}">
            {{ post.title | escape }}
          </a>
        </h3>
        <span class="post-meta">{{ post.date | date: date_format }}</span>
    </li>
  {% endfor %}
</ul>

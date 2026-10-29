Welcome To The **Ashton Caseman** Website! I'm the owner of *AC Island*, an active creator producing animations, music, theatre, and gaming content. 

---

## Latest Articles & Guides

Explore my recent project logs, gaming setups, and tech guides below:

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> - <span>{{ post.date | date: "%B %d, %Y" }}</span>
    </li>
  {% endfor %}
</ul>

# Recent Post's
<ul>
    {% for post in site.posts %}
        <li>
            <a href="/Blog{{ post.url }}">{{posts.title}}</a>
        </li>
    {% endfor %}
</ul>
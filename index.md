## 📰 Bulletin

<div class="posts">
	{% for post in site.posts %}
	    <span>{{ post.date | date_to_string }}</span>. — <a href="{{ post.url }}" title="{{ post.title }}">{{ post.title }}</a>
        <p>{{ post.content }}</p>
	<hr>
	{% endfor %}
</div>

---
title: Latest News
layout: default
---

<div class="container mt-5 mb-5">
	<div class="row">
			<h3>Latest News</h3>
			<ul class="timeline">
{% for post in site.posts %}
				<li>
					<a href="#" class="float-right">{{post.date | date: "%d %B, %Y"}}</a>
					<a href="{{post.url}}">{{post.title}}</a>
					<p>{{post.excerpt}}</p>
				</li>
{% endfor %}        
			</ul>
	</div>
</div>

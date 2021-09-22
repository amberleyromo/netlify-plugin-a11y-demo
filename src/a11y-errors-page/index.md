---
layout: layouts/post.njk
title: A page with some errors
templateClass: tmpl-post
ignoreDate: true
eleventyNavigation:
  key: A page with some errors
  order: 3
---

<figure>
	<img src="{{'/img/cats-570x720.png' | url}}" width="570" height="720">
	<figcaption>
		This image doesn't have an <code>alt</code> attribute.
	</figcaption>
</figure>

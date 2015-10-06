---
layout: default
title: The Data Hide Meetings
---

    {% for post in site.posts %}
    - [{{ post.title }}]({{ post.url | prepend: site.baseurl }}) 17:00 on {{ post.date | date: "%b %-d, %Y" }} at [The Hide](https://www.facebook.com/TheHideS3)
    {% endfor %}

	<p class="rss-subscribe">subscribe <a href="{{ "/feed.xml" | prepend: site.baseurl }}">via RSS</a></p>

</div>

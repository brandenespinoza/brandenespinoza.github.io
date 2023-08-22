---
layout:    page
title:     Library
permalink: /library/
---
Here's my reading list: a journey through tales, lessons, and lingering thoughts. While some have left their mark, others simply passed the time. Either way, they're milestones on my path. Dive in to see what caught my eye or just what kept me company on a quiet night. It's a taste, a snapshot, of a broader journey through words.

# Current Reads


{% for post in site.posts %}
{% if post.categories contains "bookreview" %}
{% if post.tags contains page.tag %}   
            <a itemprop="url" href="{{ post.url }}" target="_blank" title="{{ post.title }}">
                <span itemprop="name" itemprop=name>{{ post.title }}</span>
            </a>
        <p class="link_tags">{{ page.tags }}</p>
        </div>
    </div>
{% endif %}
{% endif %}
{% endfor %}


{% for post in site.posts %}
{% if post.categories contains "bookreview" %}
<li><a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a></li>
{% endif %}
{% endfor %}

# On Deck
{% for post in site.posts %}
{% if post.categories contains "bookreview" %}
{% if post.tags contains "ondeck" %}
<li><a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a></li>
{% endif %}
{% endif %}
{% endfor %}

# Currently Reading
{% for post in site.posts %}
{% if post.categories contains "bookreview" %}
{% if post.tags contains "inprogress" %}
<li><a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a></li>
{% endif %}
{% endif %}
{% endfor %}


# Completed
<ul>
{% for post in site.posts %}
{% if post.categories contains "bookreview" %}
{% if post.tags contains "inprogress" %}
<li><a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a></li>
{% endif %}
{% endif %}
{% endfor %}
<li><a href="#">Atlas Shrugged by Ayn Rand</a></li>
</ul>


# On Deck
- {% for post in site.posts %} {% if post.categories contains "bookreview" %}
{{ post.date | date: site.date_format }}{{ post.title }}
{% endif %} {% endfor %}

# Past Reads
- {% for post in site.posts %} {% if post.categories contains "books" %}
{{ post.date | date: site.date_format }}{{ post.title }}
{% endif %} {% endfor %}

---
layout:    page
title:     Book Notes
permalink: /book-notes/
---

<br/>

<div style="text-align:center"><span class="navy">"Seek ye diligently and teach one another words of wisdom; yea, seek ye out of the <strong>best books</strong> words of wisdom; seek learning, even by study and also by faith." - Joseph Smith Jr.</span></div>

<br/>

---

I wanted to start documenting my journey through tales, lessons, and thoughts found in the books I read. While some have left their mark, others simply passed the time. Either way, they're milestones on my path. Dive in to see what caught my eye or just what kept me company on a quiet night. It's a taste, a snapshot, of a broader journey through words.

---

<div class="home">
   <h2>On Deck</h2>
      <ul class="posts">
         {% for post in site.posts %}
            {% if post.categories contains "book-notes" %}
               {% if post.tags contains "on-deck" %}
                     <li><span>Eventually</span><a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a></li>
               {% endif %}
               {% endif %}
         {% endfor %}
      </ul>
   <h2>In Progress</h2>
      <ul class="posts">
         {% for post in site.posts %}
            {% if post.categories contains "book-notes" %}
               {% if post.tags contains "in-progress" %}
                     <li><span>About Now</span><a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a></li>
               {% endif %}
               {% endif %}
         {% endfor %}
      </ul>
   <h2>Completed</h2>
      <ul class="posts">
         {% for post in site.posts %}
            {% if post.categories contains "book-notes" %}
               {% if post.tags contains "completed" %}
                     <li><span>{{ post.date | date: site.date_format }}</span><a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a></li>
               {% endif %}
               {% endif %}
         {% endfor %}
      </ul>
</div>

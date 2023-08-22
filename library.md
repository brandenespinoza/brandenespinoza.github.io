---
layout:    page
title:     Library
permalink: /library/
---
<div class="home">
While it's not an exhaustive list of books I've read, it does the job.  Really I wanted to start documenting my journey through tales, lessons, and thoughts found in the books I read. While some have left their mark, others simply passed the time. Either way, they're milestones on my path. Dive in to see what caught my eye or just what kept me company on a quiet night. It's a taste, a snapshot, of a broader journey through words.
<div class="home">
   <h2>On Deck</h2>
      <ul class="posts">
         <li><span>Eventually</span><a href="#">"Man's Search for Meaning" by Viktor E. Frankl</a></li>
      </ul>
   <h2>In Progress</h2>
      <ul class="posts">
         {% for post in site.posts %}
            {% if post.categories contains "book-review" %}
               {% if post.tags contains "in-progress" %}
                     <li><span>{{ post.date | date: site.date_format }}</span><a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a></li>
               {% endif %}
               {% endif %}
         {% endfor %}
      </ul>
   <h2>Completed</h2>
      <ul class="posts">
         {% for post in site.posts %}
            {% if post.categories contains "book-review" %}
               {% if post.tags contains "completed" %}
                     <li><span>{{ post.date | date: site.date_format }}</span><a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a></li>
               {% endif %}
               {% endif %}
         {% endfor %}
         <li><span>Long Ago</span><a href="#">"Oedipus at Colonus" by Sophocles</a></li>
         <li><span>Long Ago</span><a href="#">"Oedipus Rex" by Sophocles</a></li>
         <li><span>Long Ago</span><a href="#">"Antigone" by Sophocles</a></li>
         <li><span>Long Ago</span><a href="#">"Oresteia" by Aeschylus</a></li>
         <li><span>Long Ago</span><a href="#">"Fables" by Aesop</a></li>
         <li><span>Long Ago</span><a href="#">Sappho</a></li>
         <li><span>Long Ago</span><a href="#">"Works and Days" by Hesiod</a></li>
         <li><span>Long Ago</span><a href="#">"Theogeny" by Hesiod</a></li>
         <li><span>Long Ago</span><a href="#">"The Odyssey" by Homer</a></li>
         <li><span>Long Ago</span><a href="#">"The Iliad" by Homer</a></li>
         <li><span>Long Ago</span><a href="#">The Epic of Gilgamesh</a></li>
         <li><span>Long Ago</span><a href="#">"The Torrents of Spring" by Ernest Hemingway</a></li>
         <li><span>Long Ago</span><a href="#">"For Whom the Bell Tolls" by Ernest Hemingway</a></li>
         <li><span>Long Ago</span><a href="#">"The Sun Also Rises" by Ernest Hemingway</a></li>
         <li><span>Long Ago</span><a href="#">"A Moveable Feast" by Ernest Hemingway</a></li>
         <li><span>Long Ago</span><a href="#">"A Farewell to Arms" by Ernest Hemingway</a></li>
         <li><span>Long Ago</span><a href="#">"Atlas Shrugged" by Ayn Rand</a></li>
         <li><span>Long Ago</span><a href="#">"Anthem" by Ayn Rand</a></li>
         <li><span>Long Ago</span><a href="#">"Human Action" by Ludwig von Mises</a></li>
         <li><span>Long Ago</span><a href="#">The Book of Mormon</a></li>
         
      </ul>
</div>

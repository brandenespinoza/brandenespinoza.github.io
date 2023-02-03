---
layout:    page
title:     Traditionalism
permalink: /tradition/
---

<br/>

<div style="text-align:center"><span class="navy">"<strong>Tradition</strong> is not the worship of ashes, but the preservation of <strong>fire</strong>." - Gustav Mahler</span></div>

<br/>

---

Below is a currated set of references and resources I have found enlightening in my path to understanding the importance of traditional western paradigms, customs, and institutions in preserving and promoting the cause of human flourishing. As heirs of all that our ancestors were, it is our responsibility to ensure we do not discard, neither by casual circumstance nor calculated intent, the endowment of civilization. 

---

## Resources
### Fatherhood & Masculinity
- [12 Rules for Life: An Antidote to Chaos](https://www.amazon.com/12-Rules-Life-Antidote-Chaos/dp/0345816021) by Jordan B. Peterson

### Motherhood & Femininity
- [The Philosophy of Motherhood](https://philosophyofmotherhood.wordpress.com/)

<br/><br/>
## My Posts

<div>
  <ul class="posts">    
    {% for post in site.posts %}
    {% if post.categories contains "tradition" %}
    <li><span>{{ post.date | date: site.date_format }}</span><a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a></li>
    {% endif %}
    {% endfor %}
  </ul>
</div>


---
layout:    page
title:     Bitcoin Resources
permalink: /tradition/
---
It has been said that **tradition** is not the worship of ashes, but the preservation of fire. Below is a currated set of references and resources I have found enlightening in my path to understanding the importance of traditional western paradigms, customs, and institutions in preserving and promoting the cause of human flourishing. As heirs of all that our ancestors were, it is our responsibility to ensure we do not discard, neither by casual circumstance nor calculated intent, the endowment of civilization. 

# Resources
## Fatherhood & Masculinity
- **Book**: [12 Rules for Life: An Antidote to Chaos](https://www.amazon.com/12-Rules-Life-Antidote-Chaos/dp/0345816021) by Jordan B. Peterson

## Motherhood & Femininity
- **Blog**: [The Philosophy of Motherhood](https://philosophyofmotherhood.wordpress.com/)

# My Writing

<div>
  <ul class="posts">    
    {% for post in site.posts %}
    <li><span>{{ post.date | date: site.date_format }}</span><a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
</div<>

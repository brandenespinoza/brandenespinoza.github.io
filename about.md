---
layout: inner
title: About
permalink: /about/
---
<div class="hero-container" style="margin-bottom:0px;">
  <div class="hero-content wow fadein" style="margin-top:-60px;">
    {% if site.avatar_2 != '' %}
    <img style="margin: 0px auto 0px; display: block;border-radius:5%;width:400px; height:400px;object-fit: contain;" src="{{site.avatar_2}}" alt="Branden Espinoza">
    {% endif %}
    <h1 class="text-center" style="margin-top:50px; margin-bottom:50px">About Me</h1>
  </div>
</div>
Family comes first, always, but I’ve got a knack for Bitcoin and a taste for leading product teams through the chaos of fintech. Got one boot in the old world of traditional finance and the other planted firmly in the wild frontier of digital assets. I don’t just talk shop – I make things happen.

<h3 class="section-title text-center" style="margin-top:30px;">My Journey</h3>
<p class="section-subtitle text-center" style="margin-top:-10px; margin-bottom:20px">Tradfi Roots... Defi Shoots</p>

I cut my teeth in places like **American Express FX** and **Truist**, where I learned to dance with regulators without stepping on any toes. Compliance, risk management, all that – did it, nailed it. But the itch for something with a little more meaning got me moving. Found myself deep in the decentralized finance world, driving product at **Block.one** and **Bullish.com**. My projects and products included **L1 protocols**, **fund raising**, building **zero-to-one apps**, even launching golobally regulated **digital asset exchanges** – you name it, I’ve had my hand in it. I don’t just build products; I build companies.

What gets me up in the morning? Working with razor sharp minds who don’t just talk change but make it. **No fluff** – just smarts, grit, and results.

<h3 class="section-title text-center" style="margin-top:30px;">My Happy Place</h3>
<p class="section-subtitle text-center" style="margin-top:-10px; margin-bottom:20px">Books, Beef, and Buffett</p>
Life’s not just numbers and protocols. I keep things simple when the laptop’s closed – spending time with the **family**, knocking out **ribs low and slow** in the smoker, thumbing through **heavy books** that make you think twice about the world, and getting on a sailboat every chance I get. Oh, and if you catch me cranking up some **goofy trop rock tunes**? Don’t judge – we all got our vices.

<h3 class="section-title text-center" style="margin-top:30px;">My Calling</h3>
<p class="section-subtitle text-center" style="margin-top:-10px; margin-bottom:20px">Build Something Great</p>
Builders make the world better – fast, purposeful, and real. I thrive in environments that value **action** over endless meetings. Austrian economics and **praxeology** shape my thinking – helps me keep a clear head when the pressure’s on. I want ideas off the drawing board and into the hands of the people who need them, simple as that.

Faith keeps me grounded. It’s a compass in all things – personal, professional, and everything in between. **Right principles guide the right outcomes**, and I carry that into every project I take on.

<h3 class="section-title text-center" style="margin-top:30px;">Let's Have A Word</h3>
<p class="section-subtitle text-center" style="margin-top:-10px; margin-bottom:20px">I'm All Ears</p>
If you’ve got a project that needs someone who understands both the **traditional finance grind** and the **wild ride of digital assets** – particularly **Bitcoin** – we should break bread. Whether it’s a startup idea or just a good conversation, let’s connect.
---
<div class="hero-buttons">
  {% if site.enable_contact == true %}
    {% include contact.html %}
    {% include contact-modal.html %}
  {% endif %}
  {% if site.twitter_username != '' %}
    <a href="https://twitter.com/{{ site.twitter_username }}"><button class="btn btn-default btn-lg" title="Twitter/X" ><i class="fa fa-twitter fa-lg" style="padding-left:15px"></i></button></a>
  {% endif %}
  {% if site.github_username != '' %}
    <a href="https://github.com/{{ site.github_username }}"><button class="btn btn-default btn-lg" title="Github" ><i class="fa fa-github fa-lg" style="padding-left:15px"></i></button></a>
  {% endif %}
  {% if site.linkedin_username != '' %}
    <a href="https://www.linkedin.com/in/{{ site.linkedin_username }}"><button class="btn btn-default btn-lg"  title="LinkedIn" ><i class="fa fa-linkedin fa-lg" style="padding-left:15px"></i></button></a>
  {% endif %}
  {% if site.nostr_username != '' %}
    <a href="https://primal.net/p/{{ site.nostr_pubkey }}"><button class="btn btn-default btn-lg" title="Primal/Nostr" ><i class="fa fa-product-hunt fa-lg" style="padding-left:15px"></i></button></a>
  {% endif %}
</div>
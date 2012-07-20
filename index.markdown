---
layout: post
title: Peter's Corner
---

Hi there, I am Peter Wang, an [Open Source][oss] enthusiast. This site is
dedicated to providing information about [me](resume.html) and [what I do](/work).

I am building another site <http://happycasts.net> to help people learn Linux
skills.

[oss]:http://en.wikipedia.org/wiki/Open_source

<p><br /><b>My Blog:</b></p>
  <ul class="posts">
    {% for post in site.posts %}
      <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>

<p><br /><b>Find me on:</b></p>

<ul>

<li><a href="http://c2.com/cgi/wiki?PeterWang">Wikiwikiweb</a></li>

<li><a href="http://github.com/happypeter/">Github</a></li>

</ul>
<p><br /><b>Contact Information:</b></p>

<blockquote>
happypeter1983@gmail.com
</blockquote>



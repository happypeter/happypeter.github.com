---
layout: post
title: Peter's Corner
---

Welcome, I am Peter Wang, an [Open Source][oss] enthusiast. This site is
dedicated to providing information about [me](resume.html) and [what I do](/work).

I am building another site <http://happypeter.org> to help people learn Linux basics.

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
<p>
happypeter1983@gmail.com
</p>
</blockquote>


<script type="text/javascript" src="http://cdn.sublimevideo.net/js/ubisak9n.js"></script>
<video class="sublime" width="640" height="360" poster="video-poster.jpg" preload="none">
  <source src="http://media.happypeter.org/happycasts/201108060324_qhd.mov " />
</video>

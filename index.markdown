---
layout: default
---
<br /><br /><center><h1>Peter's Corner</h1></center>


<table width="540" align="center"><tr><td>

<br />

<p>
Welcome, I am Peter Wang, a open source enthusiast. This site is dedicated to providing information about <a href="bio.html">me</a> and  <a href="what_i_do.html">what I do</a>.
</p>


<p><br /><b>My Favorites:</b></p>
<ul>


<li>Check &nbsp;<a href="http://c2.com/cgi/wiki?PeterWang">Me on Wikiwikiweb</a></li>

<li>Linux info for beginners &nbsp;<a href="http://www.linfo.org/">LINFO</a></li>


</ul>

<p><br /><b>My Blog:</b></p>
  <ul class="posts">
    {% for post in site.posts %}
      <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
<p><br /><b>Site Contents:</b></p>

<blockquote><p>

<a href="recent_changes.html">Recent Changes</a> &nbsp; 
<a href="site_map.html">Site Map</a>
</blockquote></p>

<p><br /><b>Contact Information:</b></p>

<blockquote>
<p>
happypeter1983 at gmail.com
</p>
</blockquote>

</td></tr></table>


</body></html>

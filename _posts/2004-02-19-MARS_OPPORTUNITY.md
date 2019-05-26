---
layout: post
title:  MARS OPPORTUNITY
author: "NASA: Music to Wake Up By"
type: MusicPlaylist
date_modified: 2004-01-04:Sol 45
songs: ["Eclipse by Pink Floyd", "Meet Me Halfway by Kenny Loggins"]
---

----
### DATE: February 19, 2004
----
✦ Eclipse by Pink Floyd  &nbsp;<br />
✺ Meet Me Halfway by Kenny Loggins

#### Comment:
* in recognition of the transit of the martian moon, Phobos.
the second song, was played because Opportunity is halfway through its primary 90-sol surface mission.



<br/>
<center>
	<a target="_blank"
	   href="https://twitter.com/intent/tweet?hashtags=Space,NASA,Playlist,NASAWakeupCalls,SpaceProgram&text={{ page.author}}, '{{ page.songs.first }}' {{ page.title }}, {{ page.date | date: '%B %d, %Y' }}. {{ site.url }}{{ page.url }}&via=nasawakeupcalls"><i class="fab fa-twitter" alt="Tweet this page" style="font-size: 1.3em;"></i></a>
	&nbsp; 	<i class="fas fa-user-astronaut" style="font-size: 1.5em;"></i> &nbsp;
    <a id="custom_amazon_link"
       type="amzn" search="#"
       category="popular music">
    <i class="fab fa-amazon" style="font-size: 1.3em;"></i></a>
</center>

<!-- Randomly resolve an individual entry from a song array -->
<script src="/assets/javascript/seedrandom.min.js"></script>
<script>
  var wake_me_up = ["Eclipse by Pink Floyd", "Meet Me Halfway by Kenny Loggins"];
  var prng = new Math.seedrandom();
  function randomSong() {
    song = wake_me_up[Math.floor(Math.random() * wake_me_up.length)];
    var amazon_link = document.getElementById("custom_amazon_link");
    amazon_link.setAttribute("search", song);
  }
  window.onload = randomSong();
</script>

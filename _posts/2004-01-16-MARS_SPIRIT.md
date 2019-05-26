---
layout: post
title:  MARS SPIRIT
author: "NASA: Music to Wake Up By"
type: MusicPlaylist
date_modified: 2004-01-04:Sol 12
songs: ["Born to be Wild by Steppenwolf", "Rawhide by Riders in the Sky", "Who Let The Dogs Out? by The Baha Men"]
---

----
### DATE: January 16, 2004
----
✧ Born to be Wild by Steppenwolf  &nbsp;<br />
✦ Rawhide by Riders in the Sky  &nbsp;<br />
✧ Who Let The Dogs Out? by The Baha Men

#### Comment:
* Egress.




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
  var wake_me_up = ["Born to be Wild by Steppenwolf", "Rawhide by Riders in the Sky", "Who Let The Dogs Out? by The Baha Men"];
  var prng = new Math.seedrandom();
  function randomSong() {
    song = wake_me_up[Math.floor(Math.random() * wake_me_up.length)];
    var amazon_link = document.getElementById("custom_amazon_link");
    amazon_link.setAttribute("search", song);
  }
  window.onload = randomSong();
</script>

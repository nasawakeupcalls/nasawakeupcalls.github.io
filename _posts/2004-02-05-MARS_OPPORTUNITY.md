---
layout: post
title:  "NASA Wakeup Calls: MARS OPPORTUNITY ✧ Let It Be by The Beatles ✫ February 05, 2004"
blog_title: "MARS OPPORTUNITY"
author: "NASA: Music to Wake Up By"
type: MusicPlaylist
date_modified: 2004-01-04:Sol 32
songs: ["Let It Be by The Beatles"]
genres: ["Rock"]
---

----
### DATE: February 05, 2004
----
✧ Let It Be *by* The Beatles ([Rock](https://www.discogs.com/genre/Rock): [Pop Rock](https://www.discogs.com/style/Pop%20Rock)) <a target="blank_" href="https://www.discogs.com/The-Beatles-Let-It-Be/master/54533">
    <i class="fas fa-compact-disc"
       title="Discogs entry for this song"
       alt="Discogs entry for this song"
       style="font-size: 1.1em;"></i></a>
    

#### Comment:
* Long MB integration -- no IDD or mobility.



<br/>
<center>
	<a target="_blank"
	   href="https://twitter.com/intent/tweet?hashtags=Space,NASA,Playlist,NASAWakeupCalls,SpaceProgram&text=🚀 {{ page.author}}, '{{ page.songs.first }}' {{ page.title }}, {{ page.date | date: '%B %d, %Y' }}, {{ site.url }}{{ page.url }}&via=nasawakeupcalls"><i class="fab fa-twitter" title="Tweet this page" alt="Tweet this page" style="font-size: 1.3em;"></i></a>
	&nbsp; 	<i class="fas fa-user-astronaut" style="font-size: 1.5em;"></i> &nbsp;
    <a id="custom_amazon_link"
       type="amzn" search="#"
       category="popular music">
    <i class="fab fa-amazon" style="font-size: 1.3em;"></i></a>
</center>

<!-- Randomly resolve an individual entry from a song array -->
<script src="/assets/javascript/seedrandom.min.js"></script>
<script>
  var wake_me_up = ["Let It Be by The Beatles"];
  var prng = new Math.seedrandom();
  function randomSong() {
    song = wake_me_up[Math.floor(Math.random() * wake_me_up.length)];
    var amazon_link = document.getElementById("custom_amazon_link");
    amazon_link.setAttribute("search", song);
  }
  window.onload = randomSong();
</script>

---
layout: post
title:  "NASA Wakeup Calls: Crew Dragon Resilience ✫ In the Air Tonight by Phil Collins ✷ November 16, 2020"
blog_title: "Crew Dragon Resilience"
author: "NASA: Music to Wake Up By"
type: MusicPlaylist
date_modified: 2020-11-16
songs: ["In the Air Tonight by Phil Collins"]
genres: ["Pop"]
---

----
### DATE: November 16, 2020
----
✫ In the Air Tonight *by* Phil Collins ([Pop](https://www.discogs.com/genre/Pop)) 

#### Comment:
* No mission comment



<br/>
<center>
	<a target="_blank"
	   href="https://twitter.com/intent/tweet?hashtags=Space,NASA,Playlist,NASAWakeupCalls,SpaceProgram&text=🚀 {{ page.author}}, {{ page.title }}. {{ site.url }}{{ page.url }}&via=nasawakeupcalls"><i class="fab fa-twitter" title="Tweet this page" alt="Tweet this page" style="font-size: 1.3em;"></i></a>
	&nbsp; 	<i class="fas fa-user-astronaut" style="font-size: 1.5em;"></i> &nbsp;
    <a id="custom_amazon_link"
       type="amzn" search="#"
       category="popular music">
    <i class="fab fa-amazon" style="font-size: 1.3em;"></i></a>
</center>

<!-- Randomly resolve an individual entry from a song array -->
<script src="/assets/javascript/seedrandom.min.js"></script>
<script>
  var wake_me_up = ["In the Air Tonight by Phil Collins"];
  var prng = new Math.seedrandom();
  function randomSong() {
    song = wake_me_up[Math.floor(Math.random() * wake_me_up.length)];
    var amazon_link = document.getElementById("custom_amazon_link");
    amazon_link.setAttribute("search", song);
  }
  window.onload = randomSong();
</script>

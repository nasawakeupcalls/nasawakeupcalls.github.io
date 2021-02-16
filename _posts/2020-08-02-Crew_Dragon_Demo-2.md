---
layout: post
title:  "NASA Wakeup Calls: Crew Dragon Demo-2 ✫ None by None ✺ August 02, 2020"
blog_title: "Crew Dragon Demo-2"
author: "NASA: Music to Wake Up By"
type: MusicPlaylist
date_modified: 2020-08-02
songs: ["None by None"]
genres: []
---

----
### DATE: August 02, 2020
----
✫ None *by* None  

#### Comment:
* There wasn't a song played today. Rather a recording from Bob and Doug's son's Theo and Jack. They let their dads know how excited they were for their arrival back on earth today. Theo noting they wanted to go get their dog!



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
  var wake_me_up = ["None by None"];
  var prng = new Math.seedrandom();
  function randomSong() {
    song = wake_me_up[Math.floor(Math.random() * wake_me_up.length)];
    var amazon_link = document.getElementById("custom_amazon_link");
    amazon_link.setAttribute("search", song);
  }
  window.onload = randomSong();
</script>

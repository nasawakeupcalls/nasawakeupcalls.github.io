---
layout: post
title:  APOLLO-SOYUZ TEST PROJECT (ASTP)
author: "NASA: Music to Wake Up By"
type: MusicPlaylist
date_modified: 1975-07-18
songs: ["Midnight In Moscow by Unidentified"]
genres: ["Jazz"]
---

----
### DATE: July 18, 1975
----
⊹ Midnight In Moscow *by* Unidentified ([Jazz](https://www.discogs.com/genre/Jazz)) <a target="blank_" href="https://www.discogs.com/Al-Caiola-And-His-Magnificent-Seven-Midnight-In-Moscow/release/12334074">
    <i class="fas fa-compact-disc"
       title="Discogs entry for this song"
       alt="Discogs entry for this song"
       style="font-size: 1.1em;"></i></a>
    

#### Comment:
* No mission comment



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
  var wake_me_up = ["Midnight In Moscow by Unidentified"];
  var prng = new Math.seedrandom();
  function randomSong() {
    song = wake_me_up[Math.floor(Math.random() * wake_me_up.length)];
    var amazon_link = document.getElementById("custom_amazon_link");
    amazon_link.setAttribute("search", song);
  }
  window.onload = randomSong();
</script>

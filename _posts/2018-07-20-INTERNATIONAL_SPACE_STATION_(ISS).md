---
layout: post
title:  INTERNATIONAL SPACE STATION (ISS)
author: "NASA: Music to Wake Up By"
type: MusicPlaylist
date_modified: 2018-07-20
songs: ["Spacelab by Kraftwerk"]
---

----
### DATE: July 20, 2018
----
✫ Spacelab by Kraftwerk

#### Comment:
* On 20 July 2018 around 21:50 local time, ESA astronaut Alexander Gerst welcomed the legendary electronic band Kraftwerk and 7500 visitors to the Jazz Open Festival on Stuttgart's Schlossplatz – live from the International Space Station, where he will live and work until mid-December 2018. During the call with space, Kraftwerk founding member Ralf Hütter and Alexander played a special duet version of the track Spacelab, for which Alexander had a tablet computer configured with virtual synthesizers on board.



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
  var wake_me_up = ["Spacelab by Kraftwerk"];
  var prng = new Math.seedrandom();
  function randomSong() {
    song = wake_me_up[Math.floor(Math.random() * wake_me_up.length)];
    var amazon_link = document.getElementById("custom_amazon_link");
    amazon_link.setAttribute("search", song);
  }
  window.onload = randomSong();
</script>

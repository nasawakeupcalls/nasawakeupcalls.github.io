---
layout: post
title:  "NASA Wakeup Calls: MARS OPPORTUNITY ✧ I'M Still Standing by Elton John ✦ January 09, 2004"
blog_title: "MARS OPPORTUNITY"
author: "NASA: Music to Wake Up By"
type: MusicPlaylist
date_modified: 2004-01-04:Sol 5
songs: ["Stand by R.E.M.", "I'M Still Standing by Elton John"]
genres: ["Rock","Rock"]
---

----
### DATE: January 09, 2004
----
✷ Stand *by* R.E.M. ([Rock](https://www.discogs.com/genre/Rock): [Pop Rock](https://www.discogs.com/style/Pop%20Rock)) <a target="blank_" href="https://www.discogs.com/REM-Stand/master/57915">
    <i class="fas fa-compact-disc"
       title="Discogs entry for this song"
       alt="Discogs entry for this song"
       style="font-size: 1.1em;"></i></a>
      &nbsp;<br />
✧ I'M Still Standing *by* Elton John ([Rock](https://www.discogs.com/genre/Rock): [Pop Rock](https://www.discogs.com/style/Pop%20Rock)) <a target="blank_" href="https://www.discogs.com/Elton-John-Im-Still-Standing/master/444771">
    <i class="fas fa-compact-disc"
       title="Discogs entry for this song"
       alt="Discogs entry for this song"
       style="font-size: 1.1em;"></i></a>
    

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
  var wake_me_up = ["Stand by R.E.M.", "I'M Still Standing by Elton John"];
  var prng = new Math.seedrandom();
  function randomSong() {
    song = wake_me_up[Math.floor(Math.random() * wake_me_up.length)];
    var amazon_link = document.getElementById("custom_amazon_link");
    amazon_link.setAttribute("search", song);
  }
  window.onload = randomSong();
</script>

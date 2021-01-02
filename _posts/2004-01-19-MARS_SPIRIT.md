---
layout: post
title:  "NASA Wakeup Calls: MARS SPIRIT ✷ Good Times Roll by The Cars ✺ January 19, 2004"
blog_title: "MARS SPIRIT"
author: "NASA: Music to Wake Up By"
type: MusicPlaylist
date_modified: 2004-01-04:Sol 15
songs: ["If You Love Somebody Set Them Free by Sting", "Roam by The B-52's", "Good Times Roll by The Cars"]
genres: ["Rock","Rock"]
---

----
### DATE: January 19, 2004
----
✧ If You Love Somebody Set Them Free *by* Sting ([Rock](https://www.discogs.com/genre/Rock): [Pop Rock](https://www.discogs.com/style/Pop%20Rock)) <a target="blank_" href="https://www.discogs.com/Sting-If-You-Love-Somebody-Set-Them-Free/master/1090307">
    <i class="fas fa-compact-disc"
       title="Discogs entry for this song"
       alt="Discogs entry for this song"
       style="font-size: 1.1em;"></i></a>
      &nbsp;<br />
✺ Roam *by* The B-52's    &nbsp;<br />
✷ Good Times Roll *by* The Cars ([Rock](https://www.discogs.com/genre/Rock): [New Wave](https://www.discogs.com/style/New%20Wave)) <a target="blank_" href="https://www.discogs.com/The-Cars-Good-Times-Roll/master/313557">
    <i class="fas fa-compact-disc"
       title="Discogs entry for this song"
       alt="Discogs entry for this song"
       style="font-size: 1.1em;"></i></a>
    

#### Comment:
* Last engineering activities, first drive on the surface.




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
  var wake_me_up = ["If You Love Somebody Set Them Free by Sting", "Roam by The B-52's", "Good Times Roll by The Cars"];
  var prng = new Math.seedrandom();
  function randomSong() {
    song = wake_me_up[Math.floor(Math.random() * wake_me_up.length)];
    var amazon_link = document.getElementById("custom_amazon_link");
    amazon_link.setAttribute("search", song);
  }
  window.onload = randomSong();
</script>

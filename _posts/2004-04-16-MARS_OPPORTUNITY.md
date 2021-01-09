---
layout: post
title:  "NASA Wakeup Calls: MARS OPPORTUNITY ✵ Dazed And Confused by Led Zeppelin ✧ April 16, 2004"
blog_title: "MARS OPPORTUNITY"
author: "NASA: Music to Wake Up By"
type: MusicPlaylist
date_modified: 2004-01-04:Sol 101
songs: ["Morning Has Broken by Cat Stevens", "Hallelujah Chorus by Handel", "Dazed And Confused by Led Zeppelin"]
genres: ["Rock","Classical","Rock"]
---

----
### DATE: April 16, 2004
----
✺ Morning Has Broken *by* Cat Stevens ([Rock](https://www.discogs.com/genre/Rock): [Folk Rock](https://www.discogs.com/style/Folk%20Rock)) <a target="blank_" href="https://www.discogs.com/Cat-Stevens-Morning-Has-Broken/master/37394">
    <i class="fas fa-compact-disc"
       title="Discogs entry for this song"
       alt="Discogs entry for this song"
       style="font-size: 1.1em;"></i></a>
      &nbsp;<br />
✦ Hallelujah Chorus *by* Handel ([Classical](https://www.discogs.com/genre/Classical): [Baroque](https://www.discogs.com/style/Baroque)) <a target="blank_" href="https://www.discogs.com/Georg-Friedrich-H%C3%A4ndel-Hallelujah-Chorus/release/14559543">
    <i class="fas fa-compact-disc"
       title="Discogs entry for this song"
       alt="Discogs entry for this song"
       style="font-size: 1.1em;"></i></a>
      &nbsp;<br />
✵ Dazed And Confused *by* Led Zeppelin ([Rock](https://www.discogs.com/genre/Rock): [Blues Rock](https://www.discogs.com/style/Blues%20Rock)) <a target="blank_" href="https://www.discogs.com/Led-Zeppelin-Dazed-And-Confused/release/3147549">
    <i class="fas fa-compact-disc"
       title="Discogs entry for this song"
       alt="Discogs entry for this song"
       style="font-size: 1.1em;"></i></a>
    

#### Comment:
* No mission comment



<br/>
<center>
	<a target="_blank"
	   href="https://twitter.com/intent/tweet?hashtags=Space,NASA,Playlist,NASAWakeupCalls,SpaceProgram&text=🚀 {{ page.author}}, '{{ page.songs.first }}' {{ page.title }}, {{ site.url }}{{ page.url }}&via=nasawakeupcalls"><i class="fab fa-twitter" title="Tweet this page" alt="Tweet this page" style="font-size: 1.3em;"></i></a>
	&nbsp; 	<i class="fas fa-user-astronaut" style="font-size: 1.5em;"></i> &nbsp;
    <a id="custom_amazon_link"
       type="amzn" search="#"
       category="popular music">
    <i class="fab fa-amazon" style="font-size: 1.3em;"></i></a>
</center>

<!-- Randomly resolve an individual entry from a song array -->
<script src="/assets/javascript/seedrandom.min.js"></script>
<script>
  var wake_me_up = ["Morning Has Broken by Cat Stevens", "Hallelujah Chorus by Handel", "Dazed And Confused by Led Zeppelin"];
  var prng = new Math.seedrandom();
  function randomSong() {
    song = wake_me_up[Math.floor(Math.random() * wake_me_up.length)];
    var amazon_link = document.getElementById("custom_amazon_link");
    amazon_link.setAttribute("search", song);
  }
  window.onload = randomSong();
</script>

---
layout: post
title:  "NASA Wakeup Calls: MARS SPIRIT ✧ With A Little Help From My Friends by The Beatles ✦ January 29, 2004"
blog_title: "MARS SPIRIT"
author: "NASA: Music to Wake Up By"
type: MusicPlaylist
date_modified: 2004-01-04:Sol 25
songs: ["(You'Re The) Devil In Disguise by Elvis Presley", "With A Little Help From My Friends by The Beatles"]
genres: ["Rock","Rock"]
---

----
### DATE: January 29, 2004
----
✺ (You'Re The) Devil In Disguise *by* Elvis Presley ([Rock](https://www.discogs.com/genre/Rock): [Rock & Roll](https://www.discogs.com/style/Rock%20%26%20Roll)) <a target="blank_" href="https://www.discogs.com/Elvis-Youre-The-Devil-In-Disguise/master/107476">
    <i class="fas fa-compact-disc"
       title="Discogs entry for this song"
       alt="Discogs entry for this song"
       style="font-size: 1.1em;"></i></a>
      &nbsp;<br />
✧ With A Little Help From My Friends *by* The Beatles ([Rock](https://www.discogs.com/genre/Rock)) <a target="blank_" href="https://www.discogs.com/The-Beatles-With-A-Little-help-From-My-Friends/release/8255349">
    <i class="fas fa-compact-disc"
       title="Discogs entry for this song"
       alt="Discogs entry for this song"
       style="font-size: 1.1em;"></i></a>
    

#### Comment:
* Continuing debug, got picture!




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
  var wake_me_up = ["(You'Re The) Devil In Disguise by Elvis Presley", "With A Little Help From My Friends by The Beatles"];
  var prng = new Math.seedrandom();
  function randomSong() {
    song = wake_me_up[Math.floor(Math.random() * wake_me_up.length)];
    var amazon_link = document.getElementById("custom_amazon_link");
    amazon_link.setAttribute("search", song);
  }
  window.onload = randomSong();
</script>

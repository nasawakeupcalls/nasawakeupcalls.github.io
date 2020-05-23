---
layout: post
title:  MARS OPPORTUNITY
author: "NASA: Music to Wake Up By"
type: MusicPlaylist
date_modified: 2004-01-04:Sol 6
songs: ["Lookin' Out My Back Door by Creedence Clearwater Revival", "Release Me by Elvis Presley", "Born To Run by Bruce Springsteen"]
genres: ["Rock","Pop","Rock"]
---

----
### DATE: January 10, 2004
----
✵ Lookin' Out My Back Door *by* Creedence Clearwater Revival ([Rock](https://www.discogs.com/genre/Rock)) <a target="blank_" href="https://www.discogs.com/Creedence-Clearwater-Revival-Lookin-Out-My-Back-Door/master/543098">
    <i class="fas fa-compact-disc"
       title="Discogs entry for this song"
       alt="Discogs entry for this song"
       style="font-size: 1.1em;"></i></a>
      &nbsp;<br />
✵ Release Me *by* Elvis Presley ([Pop](https://www.discogs.com/genre/Pop): [Rhythm & Blues](https://www.discogs.com/style/Rhythm%20%26%20Blues)) <a target="blank_" href="https://www.discogs.com/Elvis-Presley-Please-Release-Me/master/1316819">
    <i class="fas fa-compact-disc"
       title="Discogs entry for this song"
       alt="Discogs entry for this song"
       style="font-size: 1.1em;"></i></a>
      &nbsp;<br />
✧ Born To Run *by* Bruce Springsteen ([Rock](https://www.discogs.com/genre/Rock): [Pop Rock](https://www.discogs.com/style/Pop%20Rock)) <a target="blank_" href="https://www.discogs.com/Bruce-Springsteen-Born-To-Run/master/26769">
    <i class="fas fa-compact-disc"
       title="Discogs entry for this song"
       alt="Discogs entry for this song"
       style="font-size: 1.1em;"></i></a>
    

#### Comment:
* Revival.
Middle wheel release.
Wake up.



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
  var wake_me_up = ["Lookin' Out My Back Door by Creedence Clearwater Revival", "Release Me by Elvis Presley", "Born To Run by Bruce Springsteen"];
  var prng = new Math.seedrandom();
  function randomSong() {
    song = wake_me_up[Math.floor(Math.random() * wake_me_up.length)];
    var amazon_link = document.getElementById("custom_amazon_link");
    amazon_link.setAttribute("search", song);
  }
  window.onload = randomSong();
</script>

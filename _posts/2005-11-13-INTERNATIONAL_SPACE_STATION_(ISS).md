---
layout: post
title:  "NASA Wakeup Calls: INTERNATIONAL SPACE STATION (ISS) ✺ English Tea by Paul McCartney ⊹ November 13, 2005"
blog_title: "INTERNATIONAL SPACE STATION (ISS)"
author: "NASA: Music to Wake Up By"
type: MusicPlaylist
date_modified: 2005-11-13
songs: ["Good Day Sunshine by Paul McCartney", "English Tea by Paul McCartney"]
genres: ["Rock"]
---

----
### DATE: November 13, 2005
----
✵ Good Day Sunshine *by* Paul McCartney ([Rock](https://www.discogs.com/genre/Rock)) <a target="blank_" href="https://www.discogs.com/Paul-McCartney-Birthday-Good-Day-Sunshine/release/2344380">
    <i class="fas fa-compact-disc"
       title="Discogs entry for this song"
       alt="Discogs entry for this song"
       style="font-size: 1.1em;"></i></a>
      &nbsp;<br />
✺ English Tea *by* Paul McCartney  

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
  var wake_me_up = ["Good Day Sunshine by Paul McCartney", "English Tea by Paul McCartney"];
  var prng = new Math.seedrandom();
  function randomSong() {
    song = wake_me_up[Math.floor(Math.random() * wake_me_up.length)];
    var amazon_link = document.getElementById("custom_amazon_link");
    amazon_link.setAttribute("search", song);
  }
  window.onload = randomSong();
</script>

---
layout: post
title:  "NASA Wakeup Calls: MARS SPIRIT ⊹ On The Road Again by Willie Nelson ⊹ February 01, 2004"
blog_title: "MARS SPIRIT"
author: "NASA: Music to Wake Up By"
type: MusicPlaylist
date_modified: 2004-01-04:Sol 28
songs: ["On The Road Again by Willie Nelson"]
genres: ["Folk, World, & Country"]
---

----
### DATE: February 01, 2004
----
⊹ On The Road Again *by* Willie Nelson ([Folk, World, & Country](https://www.discogs.com/genre/Folk%2C%20World%2C%20%26%20Country): [Country](https://www.discogs.com/style/Country)) <a target="blank_" href="https://www.discogs.com/Willie-Nelson-On-The-Road-Again/release/3840989">
    <i class="fas fa-compact-disc"
       title="Discogs entry for this song"
       alt="Discogs entry for this song"
       style="font-size: 1.1em;"></i></a>
    

#### Comment:
* Can't wait to get back on ..., back to normal use of the flash file system, itching to get going.



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
  var wake_me_up = ["On The Road Again by Willie Nelson"];
  var prng = new Math.seedrandom();
  function randomSong() {
    song = wake_me_up[Math.floor(Math.random() * wake_me_up.length)];
    var amazon_link = document.getElementById("custom_amazon_link");
    amazon_link.setAttribute("search", song);
  }
  window.onload = randomSong();
</script>

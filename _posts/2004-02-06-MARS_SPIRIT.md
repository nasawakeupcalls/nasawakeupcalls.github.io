---
layout: post
title:  "NASA Wakeup Calls: MARS SPIRIT ⊹ The Star Spangled Banner by Beyonce ⊹ February 06, 2004"
blog_title: "MARS SPIRIT"
author: "NASA: Music to Wake Up By"
type: MusicPlaylist
date_modified: 2004-01-04:Sol 33
songs: ["Back In The Saddle Again by Gene Autry", "The Star Spangled Banner by Beyonce"]
genres: ["Folk, World, & Country","Brass & Military"]
---

----
### DATE: February 06, 2004
----
⊹ Back In The Saddle Again *by* Gene Autry ([Folk, World, & Country](https://www.discogs.com/genre/Folk%2C%20World%2C%20%26%20Country): [Country](https://www.discogs.com/style/Country)) <a target="blank_" href="https://www.discogs.com/Gene-Autry-Back-In-The-Saddle-Again/release/10055137">
    <i class="fas fa-compact-disc"
       title="Discogs entry for this song"
       alt="Discogs entry for this song"
       style="font-size: 1.1em;"></i></a>
      &nbsp;<br />
⊹ The Star Spangled Banner *by* Beyonce ([Brass & Military](https://www.discogs.com/genre/Brass%20%26%20Military): [Brass Band](https://www.discogs.com/style/Brass%20Band)) <a target="blank_" href="https://www.discogs.com/Beyonc%C3%A9-Star-Spangled-Banner-From-The-Super-Bowl-XXXVIII-Performance/master/792937">
    <i class="fas fa-compact-disc"
       title="Discogs entry for this song"
       alt="Discogs entry for this song"
       style="font-size: 1.1em;"></i></a>
    

#### Comment:
* Back to normal operations, color flag picture on RAT.




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
  var wake_me_up = ["Back In The Saddle Again by Gene Autry", "The Star Spangled Banner by Beyonce"];
  var prng = new Math.seedrandom();
  function randomSong() {
    song = wake_me_up[Math.floor(Math.random() * wake_me_up.length)];
    var amazon_link = document.getElementById("custom_amazon_link");
    amazon_link.setAttribute("search", song);
  }
  window.onload = randomSong();
</script>

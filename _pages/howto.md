---
title: "How To"
permalink: /pages/howto/
layout: splash
excerpt: "How To HippoC"
sitemap: false
header:
  image: logoheader.jpg
---

<style>
  body{
    margin: 0;
    padding: 0;
  }
  .wrapper{
    width: 100%;
    margin: 0 auto;
  }
  .header {
    height: 15px;
    background-color: white;
}
.contentwrap {
    background-color: white
}
.contentwrap:after {
    content: ".";
    display: block;
    clear: both;
    visibility: hidden;
    line-height: 0;
    height: 0;
}
.navArea {
    float: left;
    width: 25%;
    background-color: white;
    margin: 0 0 0 0;
    padding: 0;
}
.contentArea {
    float: left;
     width: 75%;
    background-color: silver;
    margin: 0;
    padding: 0;
}
.footer {
    background-color: white;
    height: 2px;
    clear: both;
}
 .video-container {
  clear:left;
  position:relative;
	padding-bottom:56.25%;
	padding-top:1px;
	height:0;
  overflow:hidden;
  }
  
  .video-container iframe, div.video-container object, div.video-container embed {
	position:absolute;
  float:right;
  top:0;
	right:0;
	width:96%;
	height:100%;
} 

hr {
  background-color:#000000;
  color:#000000;
  border:#000000;
  height:1px;
}

</style>

<h1>How To do</h1>

<div class="wrapper">
  <header class="header"><hr></header>
    <section class="contentwrap">
      <nav class="navArea">Menu</nav>
      <article class="contentArea">Inhalt</article>
    </section>
    <div class="footer"><hr></div>
</div>
<p line-height="10em"></p>
<div class="wrapper">
  <header class="header"><hr></header>
    <section class="contentwrap">
      <nav class="navArea">Menu<br>Test</nav>
      <article class="contentArea">
      <div class="video-container">
      <iframe width="560" height="315" src="https://www.youtube.com/embed/PrH_exw1WXw" frameborder="0" allowfullscreen></iframe>
    </div>
      </article>
    </section>
    <div class="footer"><hr></div>
</div>


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
    width: 90%;
    margin: 0 auto;
  }
  .header {
    height: 120px;
    background-color: red;
}
.contentwrap {
    background-color: blue
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
    width: 30%;
    background-color: white;
    margin: 0 15px 0 0;
    padding: 0;
}
.contentArea {
    float: left;
     width: 68%;
    background-color: silver;
    margin: 0;
    padding: 0;
}
.footer {
    background-color: yellow;
    height: 50px;
    clear: both;
}
</style>

<h1>How To do</h1>

<div class="wrapper">
  <header class="header">Titel</header>
    <section class="contentwrap">
      <nav class="navArea">Menu</nav>
      <article class="contentArea">Inhalt</article>
    </section>
    <div class="footer">Fusszeile</div>
</div>
<p line-height="10em"></p>
<div class="wrapper">
  <header class="header">Titel</header>
    <section class="contentwrap">
      <nav class="navArea">Menu</nav>
      <article class="contentArea">Inhalt</article>
    </section>
    <div class="footer">Fusszeile</div>
</div>

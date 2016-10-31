---
title: "People"
permalink: /pages/people/
layout: splash
excerpt: "People"
sitemap: false
feature_row:
  - image_path: placeholder-male.jpg
    title: "Eugen Solowjow"
  - image_path: placeholder-male.jpg
    title: "Daniel Düker"
  - image_path: placeholder-male.jpg
    title: "Viktor Rausch"
  - image_path: placeholder-male.jpg
    title: "René Geist"
  - image_path: placeholder-male.jpg
    title: "Tobias Johannink"
---

<style>
 body {
        min-width:1000px;
    }
    .left {
        float:left;
        width: 33.33%;
        height:500px;
        background-color:yellow;
    }
    .right {
        float:right;
        width:33.33%;
        height:500px;
        background-color:yellow;
    }
    .middle {
        background-color:blue;
        min-width:33.33%;
        height:500px;
    }
    
    .profil { 
      width: 80%; 
      height: auto; 
      display: block;
      margin-left: auto;
      margin-right: auto
      }
</style>
<div style="margin-left:10%; margin-right:10%; text-align: justify">
  <div class="left">
       <p><img class="profil" src="https://johtobi.github.io/images/placeholder-male.jpg"><br>Max Mustermann</p>
  </div>
  <div class="right">
       <p> rechts</p>
  </div>
  <div class="middle">
       <p>mitte</p>
  </div>
</div>

<h2>Team</h2>
{: .text-center}

<div style="width:80%;margin:auto;">{% include feature_row %}</div>
<div style="width:80%;margin:auto;">{% include feature_row id="row2" %}</div>

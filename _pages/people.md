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
    #left {
        float:left;
        width:200px;
        height:500px;
        background-color:yellow;
    }
    #right {
        float:right;
        width:200px;
        height:500px;
        background-color:yellow;
    }
    #middle {
        background-color:blue;
        min-width:600px;
        height:500px;
    }
</style>
  <div id=left>
       <p> links</p>
    </div>
    <div id=right>
       <p> rechts</p>
    </div>
    <div id=middle>
       <p>mitte</p>
    </div>


<h2>Team</h2>
{: .text-center}

<div style="width:80%;margin:auto;">{% include feature_row %}</div>
<div style="width:80%;margin:auto;">{% include feature_row id="row2" %}</div>

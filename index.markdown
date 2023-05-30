---
layout: page
title: ResistantBees
permalink: /

---


<style>
body {
  
  background-color: black;
  text-align: center;
  color: white;
  
  }
div .a {
  text-align: center;
  color: white;

}


div a:link   {
  color:rgb(48, 99, 196);

}

div a:visited   {
  color:rgb(40, 85, 168);

}

  div a:hover {
  color: rgb(238, 84, 13);

  }


{
  box-sizing: border-box;
}

.row {
  display: flex;
  
}

/* Create three equal columns that sits next to each other */
.column {
  flex: 33.3%;
  padding 5px;
  
}

beediv {
  flex-grow: 3;
}




</style>

    
<body> 
<html> 

<div class="row">
  <div class="column">
    <img src="./img/logo.png" style="width:40%">
  </div>
  <div class="beediv">
    <img src="./img/bees.png" style="width:70%">
  </div>
  <div class="column">
    <img src="./img/apicultor.png" style="width:40%">
  </div>
</div>

<h1 style="color:#FB600D;">Varroa resistant bees</h1>

<div class="a">

<p>our experience with Varroa resistant bees over 15 years </p>

{% for post in site.posts %}
<li><a href="{{ post.url }}">{{post.title}}</a></li>
{% endfor %}

{% for post in site.pages %}
<li><a href="{{ post.url }}">{{post.title}}</a></li>
{% endfor %}


 </div>
</html>
</body>



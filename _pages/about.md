---
permalink: /
title: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<!-- TODO : page width? -->

*(under construction)*

<span style="font-size: 15px"> 
Hi, I'm Isidora - a first-year PhD student at [Saarland University](https://www.uni-saarland.de/en/home.html). I am part of the [Computational Linguistics](https://www.coli.uni-saarland.de/groups/AK/) research group, and my advisor is [Prof. Dr. Alexander Koller](https://www.coli.uni-saarland.de/~koller/#).

<span style="font-size: 15px">  My research focuses on adaptation in dialogue, and (TBD). </span>

<span style="font-size: 15px">  My research interests include: (TBD) </span><br>
  <span style="font-size: 15px">  - adaptation in dialogue </span><br>
<span style="font-size: 15px">   - dialogue agents </span><br>
  <span style="font-size: 15px">  - large language models </span><br>
<span style="font-size: 15px">  - (ethics in artificial intelligence) </span>

<span style="font-size: 15px"> 
⚠︎ I have a dog named Baloo! (click [here](#) for a random picture of him :D)
</span>

<div id="random-photo-container"></div>

<script>
    document.querySelector('a[href="#"]').addEventListener('click', function(event) {
        event.preventDefault();
        var photos = [
            'images/balu1.jpg',
            'images/balu2.jpg',
            'images/balu3.jpg',
            'images/balu4.jpg',
            'images/balu5.png',
            'images/balu6.jpg',
            'images/balu7.jpg',
            'images/balu8.jpg',
            'images/balu9.png',
            'images/balu10.png',
            'images/balu11.png',
            'images/balu13.jpg',
            'images/balu14.png',
            'images/balu15.png',
            'images/balu16.png',
            'images/balu17.png',
            'images/balu18.jpg'
        ];
        var randomIndex = Math.floor(Math.random() * photos.length);
        var selectedPhoto = photos[randomIndex];
        var container = document.getElementById('random-photo-container');
        container.innerHTML = '<img src="' + selectedPhoto + '" alt="Oops, something went wrong - please try again!">';
    });
    
</script>
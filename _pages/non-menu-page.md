---
permalink: /non-menu-page/
title: "Random Baloo Image"
author_profile: true
redirect_from: 
  - "/nmp/"
  - "/nmp.html"
---

<!-- This is a page not in the menu. You can use markdown in this page. -->


<div id="random-photo-container"></div>
<script>
    function displayRandomPhoto() {
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
    }
    window.addEventListener('load', displayRandomPhoto);
    
</script>
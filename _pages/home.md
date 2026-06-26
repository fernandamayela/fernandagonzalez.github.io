---
permalink: /
title: "About"
author_profile: true
---
<style>
.hover-image {
    display: none;
    position: absolute;
    width: 300px; /* Adjust the size as needed */
    height: auto;
    z-index: 10; /* Ensure the image is on top */
}
.hover-trigger {
    position: relative;
    cursor: pointer;
}
</style>

<script>
document.addEventListener('DOMContentLoaded', function() {
    var trigger = document.querySelector('.hover-trigger');
    var image = document.querySelector('.hover-image');
    
    trigger.addEventListener('mouseover', function() {
        image.style.display = 'block';
    });
    
    trigger.addEventListener('mouseout', function() {
        image.style.display = 'none';
    });
});
</script>

Hello! My name is Fernanda and I’m a second-year PhD student in the Department of Political Science at Duke University with a focus on political behavior and identity and race and ethnid politics (REP). My current research examines how racial identity shifts over time, theorizing that it follows predictable cycles shaped by the cultural calendar. My prior work has explored nonpartisan elections and the availability of Spanish-language translations in political and institutional contexts, and the various forms of identity formation. 

My previous work can be found in PNAS and has been presented at conferences including APSA, SPSA, and ESRA. During my undergraduate years I served as a research assistant at MIT's Election Data and Science Lab (MEDSL) and participated in the Ralph Bunche Summer Institute. I hold a B.A. in Political Science from Wellesley College and am originally from Austin, Texas and enjoy reading, cross-stitching, traveling, music, and spending time with my dachshunds 
<span class="hover-trigger" style="color: #F58FC0;">(Coco & Pepa)</span>!

<img src="https://fernandagonzalez.github.io/images/coco_and_pepa.png" alt="Coco and Pepa" class="hover-image" style="top: 245px; left: 780px;">

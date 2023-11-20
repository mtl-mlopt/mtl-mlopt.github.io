---
layout: page
title: Organizers
hero_height: is-fullwidth
---

<style>
.inner {
max-width: 75em;
margin: 0 auto;
}

section.special, article.special {
text-align: center;
}

section.special article, article.special article {
text-align: left;
}

section.wrapper, article.wrapper {
padding: 1em 0;
}

section.wrapper header, article.wrapper header {
margin-bottom: 1em;
}

section.wrapper header h2, article.wrapper header h2 {
font-size: 2.0em;
margin: 0 0 .5em 0;
}

section.wrapper header p, article.wrapper header p {
font-size: 1.5em;
}

section.wrapper article header, article.wrapper article header {
margin: 0;
}


@media screen and (max-width: 980px) {

section.wrapper, article.wrapper {
padding: 1em 0;
}

}

@media screen and (max-width: 736px) {

section.wrapper header, article.wrapper header {
margin-bottom: 2em;
}

section.wrapper header h2, article.wrapper header h2 {
font-size: 2em;
}

}

@media screen and (max-width: 480px) {

section.wrapper, article.wrapper {
text-align: center;
}

section.wrapper article, article.wrapper article {
text-align: left;
}

}

/* Flex */

.flex {
display: -ms-flexbox;
-ms-flex-wrap: wrap;
-ms-flex-pack: justify;
display: -moz-flex;
display: -webkit-flex;
display: -ms-flex;
display: flex;
-moz-flex-wrap: wrap;
-webkit-flex-wrap: wrap;
-ms-flex-wrap: wrap;
flex-wrap: wrap;
-moz-justify-content: space-between;
-webkit-justify-content: space-between;
-ms-justify-content: space-between;
justify-content: space-between;
}

.flex.flex-2 article {
width: 47%;
}

.flex.flex-3 article {
position: relative;
width: 28%;
}

.flex.flex-3 article:before {
content: '';
position: absolute;
width: 100%;
height: 100%;
right: -2em;
top: 0;
pointer-events: none;
}

.flex.flex-3 article:last-child:before {
border: none;
}

.flex.flex-4 .box {
width: 21%;
}

@media screen and (max-width: 980px) {

.flex.flex-2 article {
width: 100%;
margin-bottom: 3em;
}

.flex.flex-2 article:last-child {
margin-bottom: 0;
}

.flex.flex-3 {
-moz-flex-direction: column;
-webkit-flex-direction: column;
-ms-flex-direction: column;
flex-direction: column;
}

.flex.flex-3 article {
width: 100%;
padding-bottom: 2.5em;
margin-bottom: 3em;
}

.flex.flex-3 article:last-child {
border: none;
padding-bottom: 0;
margin: 0 0 1em 0;
}

.flex.flex-3 article:before {
display: none;
}

.flex.flex-4 .box {
width: 47%;
}

}

@media screen and (max-width: 480px) {

.flex.flex-4 .box {
width: 100%;
}

}

/* Box */

.box {
margin-bottom: 2em;
padding: 1.5em;
/* remove shadow */
box-shadow: none;
}

.box > :last-child,
.box > :last-child > :last-child,
.box > :last-child > :last-child > :last-child {
margin-bottom: 0;
}

.box.alt {
border: 0;
border-radius: 0;
padding: 0;
}

.box.person {
padding: 3em 1.5em;
}

.box.person h3 {
margin: 0;
}

.box.person .image {
margin-bottom: 1em;
}

.box.person .image img {
max-width: 100%;
}

/* Image */

.image {
border-radius: 0;
border: 0;
display: inline-block;
position: relative;
}

.image img {
border-radius: 0;
display: block;
}

.image.left, .image.right {
max-width: 40%;
}

.image.left img, .image.right img {
width: 100%;
}

.image.round img {
border-radius: 100%;
}

.image.left {
float: left;
padding: 0 1.5em 1em 0;
top: 0.25em;
}

.image.right {
float: right;
padding: 0 0 1em 1.5em;
top: 0.25em;
}

.image.fit {
display: block;
margin: 0 0 2em 0;
width: 100%;
}

.image.fit img {
width: 100%;
}

.image.main {
display: block;
margin: 0 0 3em 0;
width: 100%;
}

.image.main img {
width: 100%;
}
</style>

<!-- Organizers page module-->

<section id="two" class="wrapper special">
  <div class="inner">
    <header>
    <h2 id="current">Current</h2>
    </header>
    <div class="flex flex-4">
      {% for researcher in site.current_organizers %}
        {% include researcher_profile.html %}
      {% endfor %}
    </div>
    <header>
      <h2 id="alumnis">Alumnis</h2>
    </header>
    <div class="flex flex-4">
      {% for researcher in site.alumnis %}
        {% include researcher_profile.html %}
      {% endfor %}
    </div>
  </div>
</section>

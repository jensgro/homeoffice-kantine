---
title: Homeoffice Kantine
subtitle: Schnelles und leckeres Essen zuhause selber machen
layout: layouts/base.njk
nav: index
---

In der aktuellen Situation sind alle, denen es beruflich möglich ist, auf Homeoffice angewiesen. Hin und wieder lese ich auf Twitter, dass dort die Kantine so schlecht sei. Dem gilt es Abhilfe zu schaffen. Diese Seite listet ein paar Ideen für einfache und schnelle Gerichte auf.

Du kannst Dich mit eigenen Ideen beteiligen:

<div class="btn-cnt">
  <a href="https://docs.google.com/document/d/1mwB8c1QlyyUqDCTcn9XJN40UPImn0CnPtqCK8ubxXwI/edit?usp=sharing" class="btn btn--warning">eigene Ideen eintragen</a>
</div>

<main class="index-main">

  <div class="card">
    <div class="card__header">
      <h2 class="card__headline">Rezeptideen <strong>mit</strong> Fleisch</h2>
    </div>
    <div class="card__body">
      <ul class="listing">
      {%- for page in collections.fleisch -%}
        <li>
          <a href="{{ page.url }}">{{ page.data.title }}</a>
        </li>
      {%- endfor -%}
      </ul>
    </div>
  </div>

  <div class="card">
    <div class="card__header">
      <h2 class="card__headline">Rezeptideen <strong>ohne</strong> Fleisch</h2>
    </div>
    <div class="card__body">
      <ul class="listing">
      {%- for page in collections.fleischlos -%}
        <li>
          <a href="{{ page.url }}">{{ page.data.title }}</a>
        </li>
      {%- endfor -%}
      </ul>
    </div>
  </div>

</main>

<p>Dieses Projekt soll wachsen und gedeihen. Ich möchte demnächst zu jeder Idee Links zu Videotutorials oder Rezepten im Netz zur Verfügung stellen. Gerne nehme ich auch diesbezüglich Anregungen entgegen. Einfach <a href="https://docs.google.com/document/d/1mwB8c1QlyyUqDCTcn9XJN40UPImn0CnPtqCK8ubxXwI/edit?usp=sharing">ins Dokument zur passenden Idee eintragen</a>.</p>

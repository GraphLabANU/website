---
title: 'Graph Research Lab @ ANU - Home'
layout: homelay
excerpt: 'Graph Research Lab @ ANU'
sitemap: true
permalink: /
---


<!-- Hero / Tagline Section -->
<p style="font-family: 'Montserrat', sans-serif; font-size: 2rem; text-align: center; font-weight: bold; margin: 20px 0;">
  <em>"Graph Power: Unlocking Real-World Challenges"</em>
</p>


<div id="html" markdown="0">
  {% assign number_printed = 0 %}
  <div class="row topic-row">
      {% for project in site.data.projects %}
      <div class="col-md-3 col-xs-5 topic-card">
        <a class="card" style="width: 18rem;" href="{{ site.url }}{{ site.baseurl }}/{{ project.page }}">
          <img class="card-img-top" src="{{ site.url }}{{ site.baseurl }}/images/propic/{{ project.image }}" alt="{{ project.title }} image" height="120" width="auto">
          <div class="card-body">
            <h6 class="card-title">{{ project.title }}</h6>
          </div>
        </a>
      </div>
     {% endfor %}
  </div>
</div>

We are a research team at the [School of Computing](https://cs.anu.edu.au/), Australian National University. Our overarching research goal is to explore and understand graph-structured data. In today's real-world applications, graphs are ubiquitously used for representing complex objects and their relationships such as cities in a road network, atoms in a molecule, friendships in social networks, connections in computer networks, and links among web pages. We focus on the following research areas:

- Graph theory and algorithms
- Machine learning on graphs
- Bridging graph theory and machine learning

<h5>
  Explore our <a href="{{ site.url }}{{ site.baseurl }}/publications">research highlights</a> and <a href="{{ site.url }}{{ site.baseurl }}/vacancies">PhD opportunities</a>.
</h5>

<div markdown="0" id="carousel" class="carousel slide" data-ride="carousel" data-interval="4000" data-pause="hover">
    <!-- Menu -->
    <ol class="carousel-indicators">
        <li data-target="#carousel" data-slide-to="0" class="active"></li>
        <li data-target="#carousel" data-slide-to="1"></li>
        <li data-target="#carousel" data-slide-to="2"></li>
        <li data-target="#carousel" data-slide-to="3"></li>
        <li data-target="#carousel" data-slide-to="4"></li>
        <li data-target="#carousel" data-slide-to="5"></li>
        <li data-target="#carousel" data-slide-to="6"></li>
    </ol>

    <!-- Items -->
    <div class="carousel-inner" markdown="0">
        <div class="item active">
            <img src="{{ site.url }}{{ site.baseurl }}/images/slider7001400/anu1.jpg" alt="Slide 1" />
        </div>
        <div class="item">
            <img src="{{ site.url }}{{ site.baseurl }}/images/slider7001400/anu2.jpg" alt="Slide 2" />
        </div>
        <div class="item">
            <img src="{{ site.url }}{{ site.baseurl }}/images/slider7001400/subset.jpg" alt="Slide 3" />
        </div>
        <div class="item">
            <img src="{{ site.url }}{{ site.baseurl }}/images/slider7001400/canberra.jpg" alt="Slide 4" />
        </div>
        <div class="item">
            <img src="{{ site.url }}{{ site.baseurl }}/images/slider7001400/kangaroo.jpg" alt="Slide 5" />
        </div>
        <div class="item">
            <img src="{{ site.url }}{{ site.baseurl }}/images/slider7001400/koala.jpg" alt="Slide 6" />
        </div>
        <div class="item">
            <img src="{{ site.url }}{{ site.baseurl }}/images/slider7001400/map.jpg" alt="Slide 7" />
        </div>
    </div>

  <a class="left carousel-control" href="#carousel" role="button" data-slide="prev">
    <span class="glyphicon glyphicon-chevron-left" aria-hidden="true"></span>
    <span class="sr-only">Previous</span>
  </a>
  <a class="right carousel-control" href="#carousel" role="button" data-slide="next">
    <span class="glyphicon glyphicon-chevron-right" aria-hidden="true"></span>
    <span class="sr-only">Next</span>
  </a>
</div>

---
title: 'Graph Research Lab @ ANU - Home'
layout: homelay
excerpt: 'Graph Research Lab @ ANU'
sitemap: true
permalink: /
---

<!-- Hero Section -->
<section class="hero" style="background-image: url('{{ site.url }}{{ site.baseurl }}/images/hero-background.jpg');">
  <div class="hero-overlay" style="background: rgba(0,0,0,0.5); padding: 80px 0;">
    <div class="container text-center">
      <h1 style="color: #fff; font-size: 3rem; margin-bottom: 20px;">Bridging Graph Theory and Machine Learning</h1>
      <p style="color: #fff; font-size: 1.2rem; margin-bottom: 30px;">
        Join us in exploring graph-structured data to unlock innovative solutions for real-world challenges.
      </p>
      <a href="{{ site.url }}{{ site.baseurl }}/vacancies" class="btn btn-primary" style="padding: 10px 20px; font-size: 1.1rem;">Explore PhD Opportunities</a>
    </div>
  </div>
</section>

<!-- Optional Slider (if you wish to retain dynamic visuals) -->
<div id="carousel" class="carousel slide" data-ride="carousel" data-interval="4000" data-pause="hover">
  <!-- Carousel Indicators -->
  <ol class="carousel-indicators">
      <li data-target="#carousel" data-slide-to="0" class="active"></li>
      <li data-target="#carousel" data-slide-to="1"></li>
      <li data-target="#carousel" data-slide-to="2"></li>
      <li data-target="#carousel" data-slide-to="3"></li>
      <li data-target="#carousel" data-slide-to="4"></li>
      <li data-target="#carousel" data-slide-to="5"></li>
      <li data-target="#carousel" data-slide-to="6"></li>
  </ol>

  <!-- Carousel Items -->
  <div class="carousel-inner" markdown="0">
      <div class="item active">
          <img src="{{ site.url }}{{ site.baseurl }}/images/slider7001400/anu1.jpg" alt="ANU Campus View 1" />
      </div>
      <div class="item">
          <img src="{{ site.url }}{{ site.baseurl }}/images/slider7001400/anu2.jpg" alt="ANU Campus View 2" />
      </div>
      <div class="item">
          <img src="{{ site.url }}{{ site.baseurl }}/images/slider7001400/subset.jpg" alt="Research Data Visualization" />
      </div>
      <div class="item">
          <img src="{{ site.url }}{{ site.baseurl }}/images/slider7001400/canberra.jpg" alt="Canberra Landscape" />
      </div>
      <div class="item">
          <img src="{{ site.url }}{{ site.baseurl }}/images/slider7001400/kangaroo.jpg" alt="Kangaroo" />
      </div>
      <div class="item">
          <img src="{{ site.url }}{{ site.baseurl }}/images/slider7001400/koala.jpg" alt="Koala" />
      </div>
      <div class="item">
          <img src="{{ site.url }}{{ site.baseurl }}/images/slider7001400/map.jpg" alt="Map of Graph Research" />
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

<!-- About Section -->
<section id="about" class="container" style="padding: 50px 0;">
  <div class="row">
    <div class="col-md-12 text-center">
      <h2>About Our Research Lab</h2>
      <p>
        We are a research team at the <a href="https://cs.anu.edu.au/">School of Computing</a>, Australian National University.
        Our mission is to explore and understand graph-structured data — a powerful tool to represent complex objects and their relationships.
      </p>
      <p>
        Our research focuses on:
      </p>
      <ul class="list-unstyled">
        <li>Graph theory and algorithms</li>
        <li>Machine learning on graphs</li>
        <li>Bridging graph theory and machine learning</li>
      </ul>
      <h5>
        Discover our <a href="{{ site.url }}{{ site.baseurl }}/publications">research highlights</a> and <a href="{{ site.url }}{{ site.baseurl }}/vacancies">PhD opportunities</a>.
      </h5>
    </div>
  </div>
</section>

<!-- Research Projects / Topics Section -->
<section id="projects" class="container" style="padding: 50px 0;">
  <h2 class="text-center">Our Research Projects</h2>
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
</section>

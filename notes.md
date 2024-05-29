---
title: SOC Thoughts
layout: default
subtitle: For many SOC2 represents a barrel of cats, lots of work and its never stays in one place.
---

{% include subStyles.css %}

{% assign articles = site.articles | sort: "order" %}
{% for article in articles %}
  <div class="row">
    <div class="col-6">
      <h4>
        {{ article.title }}
      </h4>
    </div>
    <div class="col-6">
      {{ article.subtitle }}
      <a href="{{ article.url }}">read more...</a>
    </div>
  </div>
  <hr>
{% endfor %}

<div class="mt-5 mb-5 tech-note">
    <h5>
     The CEO Perspective
    </h5>
    <p>
        These articles are written to give CEOs and Founders with think about,
        plan and prepare for the good and bad of getting cyber-ready.
    </p>
</div>

<style>
 hr { border: 1px solid #DFDFDF; }
</style>
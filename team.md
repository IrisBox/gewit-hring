---
layout: default
title: Andy Corrigan
permalink: /andy-corrigan/
image: https://github.com/IrisBox/gewit-hring/blob/main/images/team/AndyCorrigan.jpg
---
<section class="mw10 center">
{% for post in site.andy-corrigan %}
    <article class="pv4  ph3 ph0-l">
      <div class="flex flex-column flex-row-ns">
        <div class="w-100 w-60-ns pr3-ns order-2 order-1-ns">
          <a href="{{site.baseurl}}{{ post.url }}" title="Read about {{ post.title }}">
            <h1 class="f3 avenir dark-grayish-red mt0 lh-title">
              {{ post.title }}
            </h1>
          </a>
          <p class="f4 fw4 f4-l lh-copy avenir ink">
              {{ post.excerpt }}
          </p>
        </div>
        <div class="pl3-ns order-1 order-2-ns mb4 mb0-ns w-100 w-40-ns">
          <img src="{{ post.image }}" class="db" alt="{{ post.alt_text }}">
        </div>
      </div>

    </article>
{% endfor %}
</section>

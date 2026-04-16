---
layout: single
title: All Posts
permalink: /
---

Welcome to my archive. Here is a list of everything I've written:

<ul class="sidebar-links" style="margin-top: 20px;">
  {% for p in site.pages %}
    {% if p.path contains "posts/" and p.url != "/posts/" %}
      <li style="margin-bottom: 15px;">
        <a href="{{ p.url | relative_url }}" style="font-size: 18px; font-weight: 500;">
          {{ p.title }}
          <span class="chevron-icon">
            <svg width="7" height="11" viewBox="0 0 7 11" fill="none" xmlns="http://www.w3.org/2000/svg">
              <path d="M1 1L5.5 5.5L1 10" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
            </svg>
          </span>
        </a>
      </li>
    {% endif %}
  {% endfor %}
</ul>

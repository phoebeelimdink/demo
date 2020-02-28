---
layout: simple-page
title: Current Exhibitions
permalink: /current-exhibitions/
breadcrumb: Current Exhibtions
---
{% assign event-details = site.data.event-list %}
<div class="event-area">
  {% for currentlist in event-details.event %}
  {% if currentlist.category == "current" %}
  <div class="event-list-wrap">
    <div class="event-image-wrap">
      <img class="event-poster" src="/images/event-images{{currentlist.details.thumbnail-link}}">
      <div {% if currentlist.details.price == "nodata" %} class="hide" {% else %} class="event-price" {% endif %}>{{currentlist.details.price}}</div>
    </div>
    <h3>{{currentlist.title}}</h3>
    <div class="time-and-place-info-wrap">
      <p {% if currentlist.details.date == "nodata" %} class="hide" {% else %} class="date-info" {% endif %}>{{currentlist.details.date}}</p>
      <p {% if currentlist.details.time == "nodata" %} class="hide" {% else %} class="time-info" {% endif %}>{{currentlist.details.time}}</p>
      <p {% if currentlist.details.place == "nodata" %} class="hide" {% else %} class="place-info" {% endif %}>{{currentlist.details.place}}</p>
    </div>
    <div class="event-list-partition"></div>
    <p>{{currentlist.details.short-description}}</p>
  </div>
  {% else %}
  {% endif %}
  {% endfor %}
</div>

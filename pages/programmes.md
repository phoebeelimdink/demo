---
layout: simple-page
title: Programmes
permalink: /programmes/
breadcrumb: Programmes
---
{% assign programmes = site.data.programmes %}
{% for prog-listing in programmes.programme %}
<div class="programme-input-wrap">
   <input type="radio" name="event-programme" value="{{prog-listing.date}}">
   <div class="event-programme-brief-wrap">
      <div class="event-programme-brief-date-wrap" style="border-color:{{prog-listing.color}};"><p class="event-programme-brief-date">{{prog-listing.date}}</p></div>
      <div class="event-progremme-brief-info-wrap">
        <p class="programme-title">{{prog-listing.data.event-title}}</p>
        <p class="programme-title-time">{{prog-listing.data.time-start}}</p>
        <p class="programme-title-place">{{prog-listing.data.venue}}</p>
      </div>
   </div>
   <div class="programme-details">
      <div class="programme-details-title-wrap">
        <p class="programme-details-title">Event</p>
        <p>{{prog-listing.data.event-des}}</p>
      </div>
   <div class="programme-details-title-wrap">
      <a class="programme-readmore" href="{{prog-listing.data.url}}">Read More</a>
   </div>
      <div class="programme-details-time-wrap">
         <p class="programme-details-title">Time of Event</p>
         <div class="programme-time-start">
              <span>start</span>
              <p class="programme-details-date">{{prog-listing.data.date-start}}</p>
              <p class="programme-details-time">{{prog-listing.data.time-start}}</p>
         </div>
         <div class="programme-time-end">
              <span>end</span>
              <p class="programme-details-date">{{prog-listing.data.date-end}}</p>
              <p class="programme-details-time">{{prog-listing.data.time-end}}</p>
         </div>
      </div>
      <input type="radio" name="event-programme" class="close-radio">
   </div>
</div>
{% endfor %}

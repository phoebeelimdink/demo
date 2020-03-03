---
layout: post
title: "Poetry on Platforms"
date: 2020-01-01
permalink: /past-exhibitions/poetry-on-platforms
---

{% assign event-details = site.data.event-list %}

{% for thisevent in event-details.event %}
{% if thisevent.short-name == "pop" %}
<!--
<div class="event-tab-area" style="background:url('/images/event-images{{ thisevent.details.tab-banner-image-link }}');">
  <div class="tab-gradient-overlay"></div>
</div> -->
<div class="tab-banner-image"><img src="/images/event-images{{ thisevent.details.tab-banner-image-link }}"></div>
<div class="event-tab-list tab-list-outside">
  <a href="#tab1">About Exhibition</a>
  {% if thisevent.gallery-tab == "show" %}<a href="#tab2">Gallery</a>{% else %}{% endif %}
  {% if thisevent.exhibition-highlight-tab == "show" %}<a href="#tab3">Exhibition Highlights</a>{% else %}{% endif %}
  {% if thisevent.video-tab == "show" %}<a href="#tab4">Featured Video</a>{% else %}{% endif %}
  {% if thisevent.featured-highlight-tab == "show" %}<a href="#tab5">Featured Highlights</a>{% else %}{% endif %}
  {% if thisevent.resources-tab == "show" %}<a href="#tab6">Resources</a>{% else %}{% endif %}
  {% if thisevent.custom-tab1 == "show" %}<a href="#tab7">{{thisevent.custom-tab1-title}}</a>{% else %}{% endif %}
  {% if thisevent.custom-tab2 == "show" %}<a href="#tab8">{{thisevent.custom-tab2-title}}</a>{% else %}{% endif %}
  {% if thisevent.custom-tab3 == "show" %}<a href="#tab9">{{thisevent.custom-tab3-title}}</a>{% else %}{% endif %}
  {% if thisevent.programmes-tab == "show" %}<a href="#tab10">Programmes</a>{% else %}{% endif %}
</div>
<div class="event-details-area">
  
  <div id="tab1">
    <div class="event-main-image-wrap">
      <img src="/images/event-images{{ thisevent.details.main-image-link }}">
      <div class="event-place-date-and-time">
        <p markdown="1" {% if thisevent.details.date == "nodata" %} class="hide" {% else %} class="detail-date-info" {% endif %}>{{ thisevent.details.date }}</p>
        <p markdown="1" {% if thisevent.details.time == "nodata" %} class="hide" {% else %} class="detail-time-info" {% endif %}>{{ thisevent.details.time }}</p>
        <p markdown="1" {% if thisevent.details.place == "nodata" %} class="hide" {% else %} class="detail-place-info" {% endif %}>{{ thisevent.details.place }}</p>
        <p markdown="1" {% if thisevent.details.label == "nodata" %} class="hide" {% else %} class="detail-price-info" {% endif %}>{{ thisevent.details.label }}</p>
      </div>
   </div>
<!-- ---------------------------------------------------CONTENT-START-HERE--------------------------------------------------------- -->
<div class="event-text-area" markdown="1">
Immerse yourself in 82 Singapore poems written beautifully by poets on the City Hall MRT platforms. Commuters and passer-by can look forward to humorous, moving and thought-provoking poems on life, people, and places in Singapore that will strike a chord with them

_Commuters are required to pay applicable fare upon entry and exit from fare gates at SMRT stations._

</div>
<!-- ------------------------------------------------------CONTENT-END------------------------------------------------------------- -->
  </div>
  
  {% if thisevent.gallery-tab == "show" %}
  <div id="tab2">
    <h3>Gallery</h3>
    <div class="event-gallery-wrap">
      {% for image in thisevent.gallery-image %}
         <img src="/images/event-images{{image.photo-link}}">
      {% endfor %}
    </div>
  </div>
  {% else %}
  {% endif %}
  
  {% if thisevent.exhibition-highlight-tab == "show" %}
  <div id="tab3">
    <h3>Exhibition Highlights</h3>
    <div class="exhibition-highlights-wrap">
      {% for eventhighlight in thisevent.exhibition-highlight-list %}
      <a href="/images/event-images{{eventhighlight.exhibition-highlight-hires-image-link}}" target="_blank"><img src="/images/event-images{{eventhighlight.exhibition-highlight-lowres-image-link}}"></a>
      {% if eventhighlight.exhibition-highlight-title== "" %}{% else %}<h4 markdown="1">{{eventhighlight.exhibition-highlight-title}}</h4>{% endif %}
      {% if eventhighlight.exhibition-highlight-subtitle== "" %}{% else %}<p markdown="1"><strong>{{eventhighlight.exhibition-highlight-subtitle}}</strong></p>{% endif %}
      {% if eventhighlight.exhibition-highlight-text== "" %}{% else %}<p markdown="1">{{eventhighlight.exhibition-highlight-text}}</p>{% endif %}
      <hr>
      {% endfor %}
    </div>
  </div>
  {% else %}
  {% endif %}
  
  {% if thisevent.video-tab == "show" %}
  <div id="tab4">
    <h3>Featured Video</h3>
    <div class="featured-video-wrap">
      {% for featuredvideo in thisevent.video-list %}
      <div class="youtube-video-wrap">
          <img src="/images/16-9-ratio.png">
          <iframe src="https://www.youtube.com/embed/{{featuredvideo.video-youtube-embed-code}}" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
      </div>
      {% if featuredvideo.video-title== "" %}{% else %}<h4 markdown="1">{{featuredvideo.video-title}}</h4>{% endif %}
      {% if featuredvideo.video-subtitle== "" %}{% else %}<p markdown="1"><strong>{{featuredvideo.video-subtitle}}</strong></p>{% endif %}
      {% if featuredvideo.video-description== "" %}{% else %}<p markdown="1">{{featuredvideo.video-description}}</p>{% endif %}
      <hr>
      {% endfor %}
    </div>
  </div>
  {% else %}
  {% endif %}
  
  {% if thisevent.featured-highlight-tab == "show" %}
  <div id="tab5">
    <h3>Featured Highlights</h3>
    <div class="featured-highlight-wrap">
      {% for featuredhightlight in thisevent.featured-highlight-list %}
      <img src="/images/event-images{{featuredhightlight.featured-highlight-image-link}}">
      {% if featuredhightlight.featured-highlight-title== "" %}{% else %}<h4 markdown="1">{{featuredhightlight.featured-highlight-title}}</h4>{% endif %}
      {% if featuredhightlight.featured-highlight-subtitle== "" %}{% else %}<p markdown="1"><strong>{{featuredhightlight.featured-highlight-subtitle}}</strong></p>{% endif %}
      {% if featuredhightlight.featured-highlight-description== "" %}{% else %}<p markdown="1">{{featuredhightlight.featured-highlight-description}}</p>{% endif %}
      <hr>
      {% endfor %}
    </div>
  </div>
  {% else %}
  {% endif %}
  
  {% if thisevent.resources-tab == "show" %}
  <div id="tab6">
    <h3>Resources</h3>
    <div class="featured-highlight-wrap">
      <h4>{{thisevent.resources-title}}</h4>
      <p>{{thisevent.resources-text}}</p>
      {% for resourceslist in thisevent.resources-list %}
        <div class="resources-url-style">
          <a href="{{resourceslist.url}}">{{resourceslist.url-name}}</a>
        </div>
      {% endfor %}
    </div>
  </div>
  {% else %}
  {% endif %}
  
  {% if thisevent.custom-tab1 == "show" %}
  <div id="tab7">
    <h3>{{thisevent.custom-tab1-title}}</h3>
<!-- ----------------------------------------------------CONTENT-CUSTOM-1-START-HERE------------------------------------------------ -->
<div markdown="1">      
#### **Programmes**
##### **Poetry on Platforms Talk**
**25 July 2015, 4 pm – 5 pm
Level 1, Visitors’ Briefing Room
National Library Building**

Find out more about the poetry featured in “Poetry on Platforms”, as poet Eric Francis Tinsay Valles and educator and literary critic Ian Chung, share their thoughts about the exhibition.

The first 20 participants will be given a commemorative EZ-Link card.

<p style="color:red;">(Programme has ended, registration is closed.)</p>

<hr>

#### **Be a _Poetry on Platforms_ Star Poet Contest**
**16 July – 13 August 2015**

![POP02](/images/event-images/poetry-on-platforms/POP02.jpg){: .normal-width-img}

Anyone can be a poet. Pen an original poem and submit to POP@nlb.gov.sg to receive a commemorative EZ- Link card.

*Limited to the first 150 original poems received during the stated period. Limited to one EZ-Link per individual

* Terms and conditions apply. For more information, please visit [www.nlb.gov.sg/readsingapore](https://www.nlb.gov.sg/readsingapore).

<p style="color:red;">(Programme has ended, registration is closed.)</p>

An audio recording of the 82 poems that showcased on the City Hall MRT Station from 16 July to 13 August 2015.

</div>      
<!-- ------------------------------------------------------CONTENT-CUSTOM-2-END----------------------------------------------------- -->
  </div>
  {% else %}
  {% endif %}
  
  {% if thisevent.custom-tab2 == "show" %}
  <div id="tab8">
    <h3>{{thisevent.custom-tab2-title}}</h3>
<!-- ---------------------------------------------------CONTENT-START-HERE--------------------------------------------------------- -->
<div markdown="1">      

</div>      
<!-- ------------------------------------------------------CONTENT-END------------------------------------------------------------- -->
  </div>
  {% else %}
  {% endif %}
  
  {% if thisevent.custom-tab3 == "show" %}
  <div id="tab9">
    <h3>{{thisevent.custom-tab3-title}}</h3>
<!-- ----------------------------------------------------CONTENT-CUSTOM-3-START-HERE------------------------------------------------ -->
<div markdown="1">     

</div>      
<!-- -------------------------------------------------------CONTENT-CUSTOM-3-END---------------------------------------------------- -->
  </div>
  {% else %}
  {% endif %}
  
  {% if thisevent.programmes-tab == "show" %}
  <div id="tab10">
    {% assign programmes = site.data.programmes %}
    {% for prog-listing in programmes.programme %}
    {% if prog-listing.group-name == "" %}
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
    {% else %}
    {% endif %}
    {% endfor %}
  </div>
  {% else %}
  {% endif %}
  
  
</div>

{% else %}
{% endif %}
{% endfor %}


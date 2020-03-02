---
layout: post
title: "From The Stacks: Highlights of the National Library"
date: 2020-01-01
permalink: /past-exhibitions/from-the-stacks
---

{% assign event-details = site.data.event-list %}

{% for thisevent in event-details.event %}
{% if thisevent.short-name == "from-the-stacks" %}
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
Documents, publications and photographs from Singapore’s early days reveal fascinating insights into our history and culture. For instance, an 1819 document on the establishment of Malay College reveals how Raffles envisioned Singapore not just as a commercial hub but also as a centre for learning, culture and the arts.

Early literary works, religious tracts and dictionaries point to a thriving publishing industry in Singapore with printing presses run by English missionaries, Chinese literati and Muslim publishers. Cross-cultural exchanges, which have always been an element of Singapore society, gave rise to the first ‘fusion’ recipes in early cookbooks such as _The Mem’s Own Cookery Book_, published in 1929. As Singapore came into its own, discussions and debates about the Singapore identity are reflected in early 20th century magazines and 1950s poetry.

Discover early Singapore from a fresh perspective through over 100 highlights from the National Library’s collection of rare publications, manuscripts, documents, maps, photographs and more.

Download your copy of the brochure and exhibition guide by clicking the buttons below.

[Exhibition brochure](/files/from-the-stacks-onsite/MSD172_FTS_BROCHURE_R10_REVISED-FA_low-res.pdf){: .dl-style-1 target="_blank"}
[Exhibition guide (English)](/files/from-the-stacks-onsite/NLB_From_The_Stacks_-_Exhibition_Guide_English.pdf){: .dl-style-1 target="_blank"}
[Exhibition guide (Malay)](/files/from-the-stacks-onsite/NLB_From_The_Stacks_-_Exhibition_Guide_Malay.pdf){: .dl-style-1 target="_blank"}
[Exhibition guide (Chinese)](/files/from-the-stacks-onsite/NLB_From_The_Stacks_-_Exhibition_Guide_Chinese.pdf){: .dl-style-1 target="_blank"}
[Exhibition guide (Tamil)](/files/from-the-stacks-onsite/NLB_From_The_Stacks_-_Exhibition_Guide_Tamil_r.pdf){: .dl-style-1 target="_blank"}

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

<div style="text-align:center;" markdown="1">
[![From the Stacks Microsite](/images/event-images/from-the-stacks/from-the-stacks-main-image.jpg)](http://www.nlb.gov.sg/exhibitions/fromthestacks/web-hires/index.html){: .normal-width-img target="_blank"}
</div>

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
Click on the button below to browse a selection of digitized books at NLB’s e-Resources.
[Browse digitised books](http://eresources.nlb.gov.sg/printheritage/browse/from_the_stacks.aspx){: .resources-url-style target="_blank"}
  
Click on the button below to to read BiblioAsia: Highlights of the National Library.
[Browse articles from BiblioAsia](http://www.nlb.gov.sg/biblioasia/vol-11-issue-4-jan-mar-2016/){: .resources-url-style target="_blank"}

Browse the image gallery below for the exhibition’s Activity Booklet.
<div markdown="1" class="default-p">
[![From the Stacks Booklet Page 1](/images/event-images/from-the-stacks/from-the-stacks_booklet_page_01-low.jpg)](/images/event-images/from-the-stacks/from-the-stacks_booklet_page_01-high.jpg){: .inline50}
[![From the Stacks Booklet Page 2](/images/event-images/from-the-stacks/from-the-stacks_booklet_page_02-low.jpg)](/images/event-images/from-the-stacks/from-the-stacks_booklet_page_02-high.jpg){: .inline50}
[![From the Stacks Booklet Page 3](/images/event-images/from-the-stacks/from-the-stacks_booklet_page_03-low.jpg)](/images/event-images/from-the-stacks/from-the-stacks_booklet_page_03-high.jpg){: .inline50}
[![From the Stacks Booklet Page 4](/images/event-images/from-the-stacks/from-the-stacks_booklet_page_04-low.jpg)](/images/event-images/from-the-stacks/from-the-stacks_booklet_page_04-high.jpg){: .inline50}
[![From the Stacks Booklet Page 5](/images/event-images/from-the-stacks/from-the-stacks_booklet_page_05-low.jpg)](/images/event-images/from-the-stacks/from-the-stacks_booklet_page_05-high.jpg){: .inline50}
[![From the Stacks Booklet Page 6](/images/event-images/from-the-stacks/from-the-stacks_booklet_page_06-low.jpg)](/images/event-images/from-the-stacks/from-the-stacks_booklet_page_06-high.jpg){: .inline50}
[![From the Stacks Booklet Page 7](/images/event-images/from-the-stacks/from-the-stacks_booklet_page_07-low.jpg)](/images/event-images/from-the-stacks/from-the-stacks_booklet_page_07-high.jpg){: .inline50}
[![From the Stacks Booklet Page 8](/images/event-images/from-the-stacks/from-the-stacks_booklet_page_08-low.jpg)](/images/event-images/from-the-stacks/from-the-stacks_booklet_page_08-high.jpg){: .inline50}
[![From the Stacks Booklet Page 9](/images/event-images/from-the-stacks/from-the-stacks_booklet_page_09-low.jpg)](/images/event-images/from-the-stacks/from-the-stacks_booklet_page_09-high.jpg){: .inline50}
[![From the Stacks Booklet Page 10](/images/event-images/from-the-stacks/from-the-stacks_booklet_page_10-low.jpg)](/images/event-images/from-the-stacks/from-the-stacks_booklet_page_10-high.jpg){: .inline50}
</div>


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

<div markdown="1" class="default-p">
[![SS04](/images/event-images/script-and-stage-onsite/SS04-300x209.jpg)](/images/event-images/script-and-stage-onsite/SS04.jpg){: .inline30}
[![SS06](/images/event-images/script-and-stage-onsite/SS06-300x212.jpg)](/images/event-images/script-and-stage-onsite/SS06.jpg){: .inline30}
[![SS05](/images/event-images/script-and-stage-onsite/SS05-300x196.jpg)](/images/event-images/script-and-stage-onsite/SS05.jpg){: .inline30}
</div>

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


---
layout: post
title: "Script & Stage: Theatre in Singapore from the 50s to 80s"
date: 2020-01-01
permalink: /past-exhibitions/script-and-stage
---

{% assign event-details = site.data.event-list %}

{% for thisevent in event-details.event %}
{% if thisevent.short-name == "scriptandstageonsite" %}
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
**Script & Stage** explores the fascinating roots of local playwriting and theatre production, highlighting significant performances, playwrights and prominent theatre companies that have shaped the foundation of contemporary theatre in Singapore.

As we trace the development of Singapore’s vernacular theatre communities from the 1950s to the 1980s, treat yourself to publications such as _Keris Sempena Riau_, the first _sandiwara_ (Malay historical theatre) published and staged locally, as well as the manuscripts and drafts of acclaimed local playwrights like Kuo Pao Kun and Robert Yeo.

Not to be missed are showcases of notable local musicals, such as Beauty World (TheatreWorks) and Chang and Eng (Action! Theatre), at the lobby of the National Library Building.

Download a copy of the brochure by clicking the button below.

[Exhibition brochure](/files/script-and-stage-onsite/Script-Stage-Exhibition-Brochure-Resized.pdf){: .dl-style-1 target="_blank"}

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
[![Script and Stage Microsite](/images/event-images/script-and-stage/selling-dreams-thumbnail.jpg)](http://www.nlb.gov.sg/exhibitions/scriptandstage/virtualtour/Script%20and%20Stage.html){: .normal-width-img target="_blank"}
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
#### **Roving Exhibition**
##### **Theatre Tales!**
Delve into stories from traditional theatre found in Southeast Asia! Get up-close and personal with characters from the epic tales of the _Ramayana, Mahabharataand_ Chinese legends. Learn about the theatre traditions of _wayang kulit_ (shadow puppetry), Chinese street opera and _therukoothu_ (Tamil street theatre) through interactive displays at selected libraries around Singapore.

* **Central Public Library: 31 October – 19 December 2016**
* **Woodlands Regional Library: 20 December 2016 – 31 January 2017**
* **Jurong Regional Library: 1 February – 27 March 2017**

This exhibition is a roving component of _Script & Stage: Theatre in Singapore from the 50s to 80s._

<hr>

#### **Programmes**
Admission to programmes is free and open to all unless otherwise stated. Seats are limited, on a first-come first-served basis. Please register at **library eKiosks** or [www.nlb.gov.sg/golibrary](www.nlb.gov.sg/golibrary). All programmes will be held at the National Library Building (100 Victoria Street, Singapore 188064).

##### **[NL Arts Conversation] The Anatomy of a Great SG Musical**
**Friday, 18 November 2016
7.00pm – 8.30pm
Level 16, The Pod
National Library Building**
Language: English

Learn firsthand from the experts what goes into a great musical and what makes Singapore musicals so distinctive.  Join us for an express tour of the exhibition before the programme at 6.30pm. The meeting point is at the National Library Building, Level 1 (next to the information counter). This programme and tour will be conducted in English.

Speakers:
Stella Kon, playwright and writer
Kenneth Lyen, music composer and writer

Moderator: Jonathan Lum, NAFA Theatre lecturer and actor

<p style="color:red;">Programme has ended, registration is closed.</p>

<div markdown="1" class="default-p">
[![SS04](/images/event-images/script-and-stage-onsite/SS04-300x209.jpg)](/images/event-images/script-and-stage-onsite/SS04.jpg){: .inline30}
[![SS06](/images/event-images/script-and-stage-onsite/SS06-300x212.jpg)](/images/event-images/script-and-stage-onsite/SS06.jpg){: .inline30}
[![SS05](/images/event-images/script-and-stage-onsite/SS05-300x196.jpg)](/images/event-images/script-and-stage-onsite/SS05.jpg){: .inline30}
</div>

<hr>

#### **Singapore English Language Theatre: A Glance**
**Thursday, 1 December 2016
7.00pm – 8.00pm
Level 5, Possibility Room
National Library Building**
Language: English

Join Dr Robin Loon as he provides a snapshot of the history of Singapore English-language theatre, from its modest origins as expatriate theatre to today’s flourishing contemporary scene. This talk will examine some of the milestones and events that have shaped local English-language theatre and how it has always held a mirror up to Singapore society, encouraging introspection.

Speaker:
Robin Loon, Senior Lecturer of Theatre Studies, National University of Singapore (NUS). Playwright, dramaturg and co-founder of Centre 42 (a non-profit arts centre dedicated to the creation, documentation and promotion of texts for the Singapore stage).

<p style="color:red;">Programme has ended, registration is closed.</p>

<hr>

#### **[NL Arts Conversation] Malay Theatre Developments: From the 1950s to Present**
**Saturday, 14 January 2017
10.00am -11.30am
Level 5, Possibility Room
National Library Building**
Language: Malay

Find out how the culturally-rich local Malay contemporary theatre evolved into what it is today through the eyes of its theatre practitioners, before joining us for a tour of the exhibition. This programme and tour will be conducted in Malay.

Speakers:
Nadiputra, Cultural Medallion recipient and director
Aidli Mosbit, director, playwright and actor

Moderator: Hazriq Idrus, author and actor

<p style="color:red;">Programme has ended, registration is closed.</p>

<hr>

#### **[NL Arts Conversation] Social Plays in Singapore Tamil Theatre**
**Saturday, 4 February 2017
2.00pm – 3.30pm
Level 5, Possibility Room
National Library Building**
Language: Tamil

Learn about the various kinds of Tamil social plays staged locally and the impact they had on audiences, before joining us for an express tour of the exhibition. This programme and tour will be conducted in Tamil.

Speakers:
S. Varathan, Cultural Medallion recipient and director
Anantha Kannan, Director of AK Theatre

Moderator: Vadivalagan PVSS, actor and media personality

Admission is free.

<p style="color:red;">Programme has ended, registration is closed.</p>

<hr>

#### **[NL Arts Conversation] Kuo Pao Kun: The Educator**
**Saturday, 18 March 2017
2.00pm – 3.30pm
Level 5, Possibility Room
National Library Building**
Language: Mandarin

Kuo Pao Kun is perhaps Singapore’s greatest dramatist and arts activist. He was also an educator who established The Theatre Practice, The Substation and the Theatre Training & Research Programme. Find out more about Kuo’s role as an educator and how his far-sightedness has nurtured generations of theatre practitioners, before joining us for a tour of the exhibition. This programme and tour will be conducted in Mandarin.

Speakers:
Liu Xiaoyi, Theatre freelance
Tan Beng Tian, Artistic Director of Finger Players

Moderator: Lee Chee Keng, actor and lecturer at Yale-NUS

Admission is free.

<p style="color:red;">Programme has ended, registration is closed.</p>

<hr>

#### **Curator’s Tours**
<strong>Thursdays | 7pm – 8pm</strong>

10 November 2016
8 December 2016
5 January 2017
23 February 2017
9 March 2017
Meeting point: Level 7, Promenade, National Library Building

Discover the roots of local playwriting and theatre production. Learn about significant performances, playwrights as well as prominent theatre companies that have shaped the foundation of contemporary theatre in Singapore.

The curator will share behind-the-scenes stories on some of the productions featured in the exhibition. Conducted by: Georgina Wong, Assistant Curator, National Library

Admission is free.

<p style="color:red;">Programme has ended, registration is closed.</p>

<div markdown="1" class="default-p">
[![SS08](/images/event-images/script-and-stage-onsite/SS08-300x214.jpg)](/images/event-images/script-and-stage-onsite/SS08.jpg){: .inline30}
[![SS09](/images/event-images/script-and-stage-onsite/SS09-300x211.jpg)](/images/event-images/script-and-stage-onsite/SS09.jpg){: .inline30}
[![SS07](/images/event-images/script-and-stage-onsite/SS07-300x182.jpg)](/images/event-images/script-and-stage-onsite/SS07.jpg){: .inline30}
</div>

<hr>

#### **School Tours**
Through guided tours specifically tailored for schools, students will discover facets of local theatre through the manuscripts, photos, posters and oral history records of local theatre and playwrights.

Worksheets will be provided for students during the tour. The activities in the worksheet are designed to enable students to learn the skills of critical analysis and show a greater appreciation for the art of theatre and playwriting.

Interested schools can send an email to [visitnls@nlb.gov.sg](visitnls@nlb.gov.sg) for more details. Book early to secure a tour slot!

<p style="color:red;">Programme has ended, registration is closed.</p>

<div markdown="1" class="default-p">
[![SS10](/images/event-images/script-and-stage-onsite/SS10-300x213.jpg)](/images/event-images/script-and-stage-onsite/SS10.jpg){: .inline30}
[![SS11](/images/event-images/script-and-stage-onsite/SS11-300x213.jpg)](/images/event-images/script-and-stage-onsite/SS11.jpg){: .inline30}
[![SS12](/images/event-images/script-and-stage-onsite/SS12-300x215.jpg)](/images/event-images/script-and-stage-onsite/SS12.jpg){: .inline30}
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
#### Custom Markdown Here for Custom Tab 3
Put your content here!
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

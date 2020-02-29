---
layout: post
title: "Tales of the Malay World: Manuscripts and Early Books"
date: 2020-01-01
permalink: /past-exhibitions/tales-of-the-malay-world
---

{% assign event-details = site.data.event-list %}

{% for thisevent in event-details.event %}
{% if thisevent.short-name == "tmw" %}
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
_Step into the world of Malay stories – fantastical adventure tales of kings and heroes, founding myths of sultanates, and romantic poetry._

For centuries, Malay was the language of trade, diplomacy, religious discourse, and literature for maritime Southeast Asia. This exhibition explores traditional Malay literature captured in ink on paper – from handwritten manuscripts to early lithographed books.

These rarely seen items provide glimpses into the society that produced and read these literary works. Discover lesser-known stories of women authors and 19th-century lending libraries in the Malay world. Learn about the dramatic impact of printing on the manuscript tradition, and Singapore’s role as the early Malay/Muslim printing hub for the region.

The exhibition features precious manuscripts on loan from the United Kingdom and the Netherlands, shown in Singapore for the first time. It is a unique opportunity to see these collections together.

Highlights include a manuscript (copied in 1710) of one of the oldest existing _syair_ (narrative poem), which tells of the war (1666–69) between the Dutch and Makassar; the earliest manuscript on the exploits of the legendary Malay hero, Hang Tuah; one of the most ornate Malay manuscripts; and an 1811 letter from the sultan of Pontianak in Kalimantan to Stamford Raffles.

Come, discover these and other fascinating stories.

Click on the buttons below to download the exhibition brochure and guides.

[Exhibition brochure](/files/tmw/TMW_Brochure_lowres.pdf){: .dl-style-1 target="_blank"}
[Exhibition guide (English)](/files/tmw/NLB-TMW-Exh-Guide_Eng_E-Version.pdf){: .dl-style-1 target="_blank"}
[Exhibition guide (Malay)](/files/tmw/TMW-Exh.-Guide_Malay_E-Version.pdf){: .dl-style-1 target="_blank"}

<hr>

### **Shared Stories: Malay Movies and Manuscripts**
**Level 1, Lobby, National Library Building
18 August 2017 – 25 February 2018
_Free admission_**

In the late 1950s and early 1960s, Singapore was the hub of Malay film production. Some of these films feature stories similar to those in handwritten Malay manuscripts. This display features snippets of seven such films, including _Sultan Mahmud Mangkat di-Julang_ and _Dang Anom_, with accompanying film magazines.

Jointly organised by the National Library of Singapore and Asian Film Archive.

<hr>
### **Tales of the Wily Mousedeer**
* **Geylang East Public Library: 11 August 2017 – 1 October 2017 (Level 2)**
* **Ang Mo Kio Public Library: 2 October 2017 – 16 November 2017 (Level 1)**
* **Jurong West Public Library: 17 November 2017 – 11 January 2018 (Level 1)**
* **Bedok Public Library: 12 January – 25 February 2018 (Level 3)**

In Malay folklore, the wily mousedeer is the king of the forest. Stories of how the mousedeer outsmarts animals bigger than itself have entertained adults and children alike for centuries. The earliest manuscript containing the mousedeer story was written over 350 years ago! Learn more about the mousedeer in this travelling mini-exhibition.

The National Library would like to thank Inch Chua for allowing her music video, Mousedeer, to be featured in the showcase.
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
All programmes will be held at the National Library Building (100 Victoria Street, Singapore 188064).

#### **TALK | Art and Artists in Malay Manuscript Books**
**Friday, 18 August 2017
7.00pm – 8.00pm
Level 16, The Pod
Speaker: Datuk Dr Annabel Teh Gallop
_This talk is conducted in English_**

The art of the Malay book is primarily a religious art, and the finest examples of manuscript illumination in Southeast Asia are found not in literary or historical works, but in copies of the Qur’an. Sumptuously illuminated Qur’ans were produced in certain artistic centres such as Terengganu and Patani on the east coast of the Malay peninsula, Aceh on the northern tip of Sumatra, and across the archipelago from Java to Sulawesi and the island of Sumbawa.

Almost without exception, these exquisite works of art were anonymous, for Malay artists did not traditionally sign their artworks. However, in one finely illuminated Malay literary manuscript from the British Library currently on display in this exhibition – a copy of the _Hikayat Nabi Yusuf_, ‘The Story of the Prophet Joseph’, written in Perlis in 1802 – the artist has inscribed his own name, and his comments and annotations shed valuable light on the mechanics of the book trade in the Malay peninsula in the early 19th century.

Join Dr Annabel Gallop in this talk as she shares about the illumination of Qur’ans and other Islamic manuscripts.

<p style="color:red;">(Programme has ended, registration is closed.)</p>
<div style="text-align:center;" markdown="1">
![Hikayat Nabi Yusuf](/images/event-images/tmw/TMW-old-001.jpg)
<i>Hikayat Nabi Yusuf</i>, 1802, British Library
</div>
**Annabel Teh Gallop** is lead curator for Southeast Asia materials at the British Library. She obtained her doctorate at the School of Oriental and African Studies, London, in 2002 with the thesis, ‘Malay Seal Inscriptions: A Study in Islamic Epigraphy from Southeast Asia’. Her main research interests are Malay manuscripts, letters, documents and seals, and the art of the Qur’an in Southeast Asia.

<hr>

#### **TALK | The Script State (Negeri Naskhah) – Malay Manuscripts in Documenting Memories**
**Saturday, 30 September 2017
3.00pm – 4.00pm
Level 5, Possibility Room
Speaker: Dr Azhar Ibrahim
_This talk is conducted in English_**

Manuscripts are testaments of their time, as they reflect the conditions and people surrounding the text. Today, the reception of manuscripts and texts – the way we read and interpret them – is also subject to the prevailing ideas of our time.

This programme provides an overview of the written tradition of the Malay world, which we have inherited in the form of manuscripts. Discover the stories of these texts; their various forms throughout history; and how the written text has become a symbol of power, intellect and mastery.

**Azhar Ibrahim** is a lecturer at the Department of Malay Studies, National University of Singapore. His research interests include sociology of religion, sociology of literature and critical literacy, and the Malay-Indonesia intellectual development.

<p style="color:red;">(Programme has ended, registration is closed.)</p>
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

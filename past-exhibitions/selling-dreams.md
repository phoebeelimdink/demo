---
layout: post
title: "Selling Dreams: Early Advertising in Singapore"
date: 2020-01-01
permalink: /past-exhibitions/selling-dreams
---

{% assign event-details = site.data.event-list %}

{% for thisevent in event-details.event %}
{% if thisevent.short-name == "dreamsonsite" %}
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
### Selling Dreams: Early Advertising in Singapore
**20 July 2018 – 24 February 2019
10.00am – 9.00pm
Level 10, Gallery
National Library Building
_Free admission_**

Advertisements are fascinating cultural documents that both shape and reflect people’s desires and ideals. This exhibition features advertising materials from the 1830s to 1960s in the National Library collection, and explores the hopes, dreams, aspirations and insecurities of society over the years.

Modelled after a department store, the exhibition highlights advertisements promoting a myriad of products, services and brands that once saturated Singapore’s busy consumer market. Through this colourful showcase of the National Library’s rare publications, magazines, newspapers and ephemera, you will gain a deeper understanding of advertising and its impact on society, while learning more about Singapore’s past.

Click below to download the exhibition brochure and guide.
[Exhibition brochure (with Programmes from October 2018 to February 2019)](/files/sellingdreamsonsite/SEAD_Brochure-B_FINAL.pdf){: .dl-style-1 target="_blank"}
[Exhibition brochure (with Programmes from July 2018 to October 2018)](/files/sellingdreamsonsite/SEAD_DL-Brochure-A_small.pdf){: .dl-style-1 target="_blank"}
[Exhibition guide (English)](/files/sellingdreamsonsite/NLB-Exhibition-Guide-101018-single-pages.pdf){: .dl-style-1 target="_blank"}
[Exhibition guide (Chinese)](/files/sellingdreamsonsite/NLB-SEAD-Exhibition-Guide-CH-11122018.pdf){: .dl-style-1 target="_blank"}
[Exhibition guide (Malay)](/files/sellingdreamsonsite/NLB-SEAD-Exhibition-Guide-MY-05122018.pdf){: .dl-style-1 target="_blank"}
[Exhibition guide (Tamil)](/files/sellingdreamsonsite/NLB-Exhibition-Guide-TM-20122018.pdf){: .dl-style-1 target="_blank"}

<hr>
### **The Art of Persuasion**
**20 July 2018 – 24 February 2019
10.00am – 9.00pm
Level 10, Lobby
National Library Building
_Free admission_**

How do advertisers hook an audience? ‘The Art of Persuasion’ looks at different advertising methods and strategies used in ads drawn from the library’s vast collection of print publications from the 1830s to 1960s. Head down to the National Library’s ‘advertising studio’ in the lobby and check out ads featuring comics and cartoons, witty copy, bold imagery and illustrations as well as early advertising attempts to appeal to local audiences.

A micro exhibition of the same title will be travelling to the following Public Libraries:

* **Ang Mo Kio Public Library: 9 Jul – 26 Aug 2018**
* **Woodlands Regional Library: 27 Aug – 21 Oct 2018**
* **Clementi Public Library: 22 Oct – 16 Dec 2018**
* **Sengkang Public Library: 17 Dec 2018 – 10 Feb 2019**
* **Library@Harbourfront: 11 Feb 2019 – 24 Mar 2019**

Join us as we uncover the nation’s early years through advertising paraphernalia from the National Library’s rich collection.

<hr>
### **School Tours**
Set in a shopping scene in the early 20th century, students and teachers will experience a taste of life in Singapore from the colonial era to the 1960s. Singapore’s social history and businesses, in particular, will be featured through a selection of advertisements from newspapers and other publications. Worksheets for students will also be provided.

Interested schools can email [visitnls@nlb.gov.sg](mailto:visitnls@nlb.gov.sg) for more details. Book early to secure a tour slot!

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
##### **Symposium | TEMASEK AND SINGAPURA: Marvels, Metaphors and Meanings from Sejarah Melayu**
**23 February 2019
2.00pm – 5.00pm
Level 16, The POD, National Library Building**

<i>Conducted in English.</i> <i style="color:red;">(Event has ended, registration is closed.)</i>

Sejarah Melayu is considered one of the most important and finest literary works of the Malay world. Essentially a court text that recorded the dynastic and feudal glories of Palembang-Singapura-Melaka and Johore from the 13th to 16th centuries, this text has piqued the interests of historians, academics as well as politicians in the era of nationalism and post-independence.

This symposium aims to highlight Sejarah Melayu and its effects on the cultural and literary history of Singapore and beyond.
<p>&nbsp;</p>
<u>Programme</u>
<table class="">
  <tr>
    <td width="150">
      <strong>2.00pm – 3.00pm</strong>
    </td>
    <td>
      <p><strong><i>Ceritera Singapura</i>: Narrating Singapore</strong></p>
    </td>
  </tr>
  <tr>
    <td width="150">
    </td>
    <td>
      <u>Speaker</u><p></p>
      <p><strong>Dr Sa’eda Bte Buang</strong>, Assistant Head of the Asian Languages and Cultures Department, National Institute of Education Singapore</p>
    </td>
  </tr>
  <tr>
    <td width="150"><strong>3.00pm – 3.15pm</strong></td>
    <td><p>Performance by Aqmal N, Singer, Musician, Composer and Producer</p></td>
  </tr>
  <tr>
    <td width="150"><strong>3.15pm – 5.00pm</strong></td>
    <td><p><strong>When History becomes a Boon and a Bane: <em>Sejarah Melayu </em>in Retrospection</strong></p></td>
  </tr>
  <tr>
    <td width="150"><strong>&nbsp;</strong></td>
    <td><u>Panellists</u><p></p>
    <p><strong>Dr Sa’eda Bte Buang</strong>, Assistant Head of the Asian Languages and Cultures Department, National Institute of Education Singapore</p>
    <p><strong>Faisal Tehrani</strong>, Author and Playwright</p>
    <p><strong>Idris Rashid Khan Surattee</strong>, Freelance Researcher and Writer</p></td>
  </tr>
  <tr>
    <td width="150"><strong>&nbsp;</strong></td>
    <td><u>Moderator</u><p></p>
    <p><strong>Dr Azhar Ibrahim</strong>, Lecturer and Deputy Head at the Department of Malay Studies, National University of Singapore</p></td>
  </tr>
</table>
<hr>
##### **Chetakan Pertama | Kisah-Kisah Abadi: Nilai, Bahasa dan Wanita dalam Kesusasteraan Melayu Tradisional**
**16 March 2019
10:30am – 12:30pm
Level 5, Possibility Room**

<i style="color:red;">(Event has ended, registration is closed.)</i>

Dalam sesi ini, Dr Kartini Anwar dan Annaliza Bakri akan mengetengahkan beberapa tema, nilai dan idealogi dalam kesusasteraan Melayu awal yang kekal dari generasi ke generasi. Ketahui bagaimana kisah-kisah tersebut telah meninggalkan kesan yang mendalam terhadap masyarakat dan juga dunia kesusasteraan Melayu hingga ke hari ini.

**Ahli Panel:**
* **Dr Kartini Anwar**, Pensyarah, NIE dan NTU
* **Dr Kartini Anwar**, Pensyarah, NIE dan NTU

**Pemudahcara:**
* **Juffri Supa’at**, Pustakawan Kanan, NLB
</div>     
<!-- ------------------------------------------------------CONTENT-CUSTOM-1-END----------------------------------------------------- -->
  </div>
  {% else %}
  {% endif %}
  
  {% if thisevent.custom-tab2 == "show" %}
  <div id="tab8">
    <h3>{{thisevent.custom-tab2-title}}</h3>
<!-- ---------------------------------------------------CONTENT-CUSTOM-2-START-HERE------------------------------------------------- -->
<div markdown="1">      
#### Custom Markdown Here for Custom Tab 2
Put your content here!
</div>      
<!-- ------------------------------------------------------CONTENT-CUSTOM-2-END----------------------------------------------------- -->
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

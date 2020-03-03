---
layout: post
title: "Geo|Graphic: Celebrating maps and their stories"
date: 2020-01-01
permalink: /past-exhibitions/geographic
---

{% assign event-details = site.data.event-list %}

{% for thisevent in event-details.event %}
{% if thisevent.short-name == "geographic" %}
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
<p>Maps are fascinating objects; they not only tell us about the places they depict but also how their makers saw the world around them. For Singapore in particular, maps are a window to our early history – before the arrival of the British in 1819. The National Library is pleased to present Geo|Graphic, an offering of exhibitions and programmes that explore maps and mapping.</p>

Download your copy of the festival brochure by clicking the button below.

[Exhibition brochure](/files/geographic/Geographic_Festival-brochure.pdf){: .dl-style-1 target="_blank"}

### **Geo|Graphic exhibitions**
##### **Singapore’s First Topographical and City Map**
**Lobby, Level 1**

Topographic maps give a three-dimensional sense of the area being mapped, depicting the contours and relief of the terrain. On display are Singapore’s first complete set of topographical maps that were produced in 1924, and the six-sheet 1954 map of the city centre.

![Sheet 14 showing islands like Pulau Bukom and Semakau off the west coast of mainland Singapore 1924](/images/event-images/geographic/geographic-main-image-2.jpg){: .normal-width-img}
<div class="default-p"><small class="image-caption">Sheet 14 showing islands like Pulau Bukom and Semakau off the west coast of mainland Singapore 1924<br>Source: Singapore Land Authority, Courtesy of National Archives of Singapore</small></div>

<hr>

##### **Mind the Gap: Mapping the Other**
**Mind the Gap** presents the works of three Singapore-based contemporary artists who harness the strategies of data collection and mapping to investigate what lies beneath the surface of contemporary life.

<h5><strong>Bibliotopia</strong><strong style="color:#484848 !important"> | by Michael Lee</strong></h5>
**Promenade, Level 7**

![Michael Lee, Work in progress for not here, not there (after Russell Lee) from the Bibliotopia series (2015)](/images/event-images/geographic/geographic-main-image-3.jpg){: .normal-width-img}
<div class="default-p"><small class="image-caption">Michael Lee<br>Work in progress for not here, not there (after Russell Lee) from the Bibliotopia series (2015)</small></div>

In this work titled Bibliotopia, Michael Lee uses the device of the mind map to uncover the “secret bookscape” of Singapore’s book culture. Focusing on the genres of short fiction, horror and the teen novel through the literary output of Catherine Lim, Russell Lee and Adrian Tan – the artist draws out secrets that are hidden within, or exposed by, narratives on identity, adolescence, and the ghostly in Singapore.

Michael Lee is an artist, curator and publisher, whose works focus on urban memory and fiction, with an emphasis on their contexts and issues of loss.


<h5><strong>Outliers</strong><strong style="color:#484848 !important"> | by Jeremy Sharma</strong></h5>
**Promenade, Level 8**

![Jeremy Sharma, Work in Progress for the Outliers, 2014-2015](/images/event-images/geographic/geographic-main-image-4.jpg){: .normal-width-img}
<div class="default-p"><small class="image-caption">Jeremy Sharma<br>Work in Progress for the Outliers, 2014-2015</small></div>

In the installation **Outliers** by Jeremy Sharma, are four white polystyrene blocks with undulating surfaces that capture the signals of dying stars (pulsars) in material form. Sharma, with the help of a pulsar scientist, has been collecting and categorising the radiographic data of selected pulsars. His work contemplates the profound space-time distance the signals of dying stars travel to communicate their death throes.

Jeremy Sharma instigates investigative processes to inform the formal expressions of his painterly and sculptural practice.


<h5><strong>Islands in Between<br>… The seas will sing and the wind will carry us… (Fables of Nusantara)</strong><strong style="color:#484848 !important"> | by Sherman Ong</strong></h5>
**Promenade, Level 9**

![Sherman Ong, Video stills from Fables of Nusantara (2015)](/images/event-images/geographic/geographic-main-image-5.jpg){: .normal-width-img}
<div class="default-p"><small class="image-caption">Sherman Ong<br>Video stills from Fables of Nusantara (2015)</small></div>

In this video installation, Sherman Ong uses the documentary/ethnographic film genre to tell stories of migration, trans-border identities, myths and memories in the islands of Southeast Asia. The histories and contemporary stories of the region are explored through the nine individuals featured in the video vignettes.

Sherman Ong is a filmmaker, photographer and visual artist whose practice centres on the relationship between place and the human condition.

<hr>

##### **Land of Gold and Spices: Early Maps of Southeast Asia and Singapore**
**National Library Gallery, Level 10**

![Land of Gold and Spices](/images/event-images/geographic/geographic-main-image-6.jpg){: .normal-width-img}
Asia, particularly Southeast Asia, had a strong hold over the imaginations of early Europeans as a source of gold, spices and all things exotic. Land of Gold and Spices presents a fascinating look at how Southeast Asia was perceived, conceived of and mapped by the Europeans from the 15th to the early 19th centuries.

The maps featured in this exhibition are from the National Library, Singapore’s rare maps collection and tell stories of the European presence in the region. The exhibition features printed and hand-drawn maps as well as sailing instructions that point to Singapore’s early history before the arrival of the British in 1819. On special loan from European libraries are rare maps, such as indigenous Southeast Asian maps, on display for the very first time in Singapore.

<hr>

##### **Island of Stories: Singapore Maps**
**Lee Kong Chian Reference Library, Level 11**

![Island of Stories: Singapore Maps](/images/event-images/geographic/geographic-main-image-7.jpg){: .normal-width-img}
**Island of Stories**, showcasing the collection of the National Archives of Singapore, draws on an eclectic mix of Singapore maps that captures intriguing moments from our country’s history. Featuring maps of forgotten mileage points to the island’s farmland and soil composition, as well as stories of the former detached mole at Marina Bay, the Orchard Road “circus” and the election fever of 1955 – these maps weave a quirky, multifaceted story of Singapore’s past.

Among other various audiovisual elements, visitors can overlay 19th-century maps over a contemporary map of the island in an interactive display developed with the Urban Redevelopment Authority, to see how the island has changed over the years.

Jointly organised by the National Archives of Singapore and the National Library, Singapore.

<hr>

<h5><strong>SEA STATE 8 SEABOOK</strong><strong style="color:#484848 !important"> | An Art Project by Charles Lim</strong></h5>
**Lee Kong Chian Reference Library, Level 11**

![Charles Lim, Sea Safe (2014)](/images/event-images/geographic/geographic-main-image-8.jpg){: .normal-width-img}
<div class="default-p"><small class="image-caption">Charles Lim<br>Sea Safe (2014)</small></div>

Part of the SEA STATE series, **SEABOOK** follows Charles Lim’s solo-exhibition, “In Search of Raffles’ Light” (2013) held at the NUS Museum. SEABOOK is conceived by the artist, as a site for the accumulation of archival materials, anecdotes and memories that unravels Singapore’s relationship with the sea. Developed with the librarians from the National Library, the project attempts to highlight the range of primary resources available on the sea from the colonial and post-colonial periods. In effect, SEABOOK aspires to be the most extensive cultural study of Singapore’s troubled relationship with the sea.

Charles Lim will represent Singapore in the 2015 Venice Biennale. He has a close relationship with the sea, being a former national sailor and having represented Singapore in the 1996 Olympics.

Jointly organised by the National Library, Singapore and NUS Museum.
 
<hr>

### **MAPS! At the Public Libraries**
Check out our interactive exhibition **MAPS!** which explores maps and navigation through history at the following libraries near you!

Public Library | Date
---|---
Jurong Regional Library, Level 1 | 21 Jan 2015 – 26 Feb 2015
Bishan Public Library, Level 1, Foyer | 28 Feb 2015 – 5 Apr 2015
Central Public Library, Basement 1 | 7 Apr 2015 – 14 June 2015
Woodlands Regional Library, Level 3 | 15 June 2015 – 29 Jul 2015


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

#### **Tours**
**Weekend Guided Tour (Land of Gold and Spices)**
<p>Conducted in English | *All Saturdays and Sundays, 2pm | 2pm – 3pm (Except 11 Apr, 25 Apr, 16 May | 4.30pm – 5.30pm)</p>

<p>Conducted in Mandarin | *All Saturdays and Sundays, 2.30pm | 2.30pm – 3.30pm</p>

Meeting point: Outside the Gallery, Level 10

Free weekend guided tours are available from February 2015. Tours are limited to 20 participants per session, on a first-come-first-served basis. The first 10 participants for each session will receive a free exclusive publication, Visualizing Space: Maps of Singapore and the Region. For enquiries, please email [visitnls@nlb.gov.sg](mailto:visitnls@nlb.gov.sg)

* There will be no tours on public holidays.

<p style="color:red;">(Programme has ended, registration is closed.)</p>
<p>&nbsp;</p>
<p><strong>Curator’s Tour Part 1 (Land of Gold and Spices)</strong><br>Conducted in English | 26 Feb, 20 Mar, 17 Apr, 15 May, 19 Jun, 10 Jul 2015, 7.30pm<br>Meeting point: Outside the Gallery, Level 10<br>
</p>

<p><strong>Curator’s Tour Part 2 (Island of Stories)</strong><br>Conducted in English | 26 Feb, 20 Mar, 17 Apr, 15 May, 19 Jun, 10 Jul 2015, 9.00pm<br>Meeting point: Outside the Lee Kong Chian Reference Library, Level 11<br>
</p>

Admission is free. Tours are limited to 20 participants per session.

<p style="color:red;">(Programme has ended, registration is closed.)</p>

#### **School Self-guided Tour**
Gallery, Level 10 and 11

Schools are able to organise a self-guided tour facilitated by their teachers. A handy educator’s guide/teaching aid for teachers as well as activity sheets for students are available. Interested schools can email [visitnls@nlb.gov.sg](mailto:visitnls@nlb.gov.sg) for more details.

<p style="color:red;">(Programme has ended, registration is closed.)</p>

<hr>

#### **Book Display**
**Maps that Shaped Singapore 
12 Dec 2014 – 28 Feb 2015 | Lee Kong Chian Reference Library, Level 8**

Singapore’s urban landscape has been shaped by its various Concept Plans – the country’s strategic land use and transportation plans. By showcasing these Concept Plans and publications related to land use in Singapore, this book display examines the background and impact of Concept Plans in shaping the country’s urban environment.

<hr>

### **Programmes**
#### **The Spice Islands’ Impact on the Mapping of the World**
**Wednesday, 21 Jan, 7.00pm – 9.00pm | The Pod, Level 16 | Speaker: Dr David E. Parry**

How did the search for a sea route to the “Indies” and “Isles of Spicerie” became the Holy Grail of the great Renaissance explorers, revealing the continents of Africa and North and South America? Discover this and more as renowned soil scientist, Dr Parry shares his experience as an avid map collector and about his book _The Cartography of the East Indian Islands._

<p style="color:red;">(Programme has ended, registration is closed.)</p>

<hr>

#### **Cartography at National Geographic: From Crow Quill Pen to Computer**
**Thursday, 5 Mar, 7.00pm – 8.30pm | Possibility Room, Level 5 | Speaker: Mr Juan José Valdés**

Technology has modified the way maps have been traditionally researched, designed and edited. This is nowhere more evident than at the National Geographic Society, with its cartographic tradition spanning over 100 years; their cartographers have now embraced the fast-paced digital world of map-making. Speaking live from Washington DC via web broadcast, Mr Juan José Valdés, official geographer of the National Geographic Society, addresses the society’s significant milestones and their impact on its maps and map products.

<p style="color:red;">(Programme has ended, registration is closed.)</p>

<hr>

#### **Mapping Histories: Cartographic Representation of Singapore and Its Limits**
**Saturday, 21 Mar, 2.00pm – 4.00pm | Possibility Room, Level 5 | Speaker: Dr Imran bin Tajudeen**

Maps record both cultural and natural physical data to varying degrees and a comparative perspective across time can reveal useful information about changes to multiple aspects of the landscape. In this session, Dr Imran, an assistant professor at the National University of Singapore’s Department of Architecture, will discuss the use of old maps to uncover the lesser-known aspects of place histories in Singapore.

<p style="color:red;">(Programme has ended, registration is closed.)</p>

<hr>

#### **Mapping Singapore in World War II: A Global Perspective**
**Saturday, 11 Apr, 2.00pm – 4.00pm | Possibility Room, Level 5 | Speaker: Mr Mok Ly Yng**

This presentation reviews the organisation of worldwide mapping efforts by the British and American mapping agencies during World War II as well as Singapore’s military mapping from a global perspective. Selected military maps of Singapore that were in use or produced during World War II with significant points of interest reflected will be highlighted during this session by mapping consultant, Mr Mok Ly Yng.

<p style="color:red;">(Programme has ended, registration is closed.)</p>

<hr>

#### **Changing Landscapes of Singapore**
**Saturday, 25 Apr, 2.00pm – 4.00pm | Possibility Room, Level 5 | Speaker: Associate Professor Victor R Savage**

Over the last 190 years of Singapore’s history, the city-state landscapes have undergone tremendous changes and transformations. This talk by Associate Professor Victor R. Savage from the National University of Singapore’s Department of Geography, provides a glimpse into Singapore’s past and current landscapes and their implications in the imageability and legibility of Singapore to residents and tourists alike.

<p style="color:red;">(Programme has ended, registration is closed.)</p>

<hr>

#### **Planning for Singapore: How Do We Do It?**
**Saturday, 16 May, 2.00pm – 4.00pm | Possibility Room, Level 5 | Speaker: Mr Daniel Leong**

Given Singapore’s limited space and multiple land uses, the nation’s planners use a comprehensive framework that provides an integrated approach to sustainable development. Tools developed based on Geographic Information Systems (GIS) help to enhance and plan for the needs of the current and future generations of Singaporeans. Mr Daniel Leong, a planner with the Urban Redevelopment Authority, shares how these GIS tools can help to create a vibrant and sustainable city of distinction.

The programmes are limited to 120 participants per session, on a first-come-first-served basis.Admission is free.

<p style="color:red;">(Programme has ended, registration is closed.)</p>

<hr>

#### **The Past is a Foreign Country: A special presentation by the Singapore Memory Project**
**April to August 2015 | Promenade, Level 10, National Library Building**

**The Past is a Foreign Country** is a selection of projects funded by the irememberSG fund that explore issues of territoriality, space and environment through the trope of memory in Singapore. For more information of the specific exhibitions and programmes, please visit [iremember.sg](http://iremember.sg)

Projects showcase include:

* Points of Departureby Juria Toramae & Jerome Lim
* Island Nation by Captured (Edwin Koo, Zakaria Zainal & Juliana Tan)
* Memories of Pulau Brani by Muhammad Nadjad Abdul Rahim
* The Memories of Trees by Robert Zhao Renhui
* Singapore’s Orchid History by Hedrick Kwan
* BuiltInSG by Meka Studios
* Architecture & Architects by DO NOT DESIGN
* irememberParks by Singapore Furniture Industries Council
* Building Memories by Achates 360 & Koh Hong Teng

Supported by the Singapore Memory Project.

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


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
<p>&nbsp;</p>

In this work titled Bibliotopia, Michael Lee uses the device of the mind map to uncover the “secret bookscape” of Singapore’s book culture. Focusing on the genres of short fiction, horror and the teen novel through the literary output of Catherine Lim, Russell Lee and Adrian Tan – the artist draws out secrets that are hidden within, or exposed by, narratives on identity, adolescence, and the ghostly in Singapore.

Michael Lee is an artist, curator and publisher, whose works focus on urban memory and fiction, with an emphasis on their contexts and issues of loss.

<hr>

<h5><strong>Outliers</strong><strong style="color:#484848 !important"> | by Jeremy Sharma</strong></h5>
**Promenade, Level 8**

![Jeremy Sharma, Work in Progress for the Outliers, 2014-2015](/images/event-images/geographic/geographic-main-image-4.jpg){: .normal-width-img}
<div class="default-p"><small class="image-caption">Jeremy Sharma<br>Work in Progress for the Outliers, 2014-2015</small></div>
<p>&nbsp;</p>

In the installation **Outliers** by Jeremy Sharma, are four white polystyrene blocks with undulating surfaces that capture the signals of dying stars (pulsars) in material form. Sharma, with the help of a pulsar scientist, has been collecting and categorising the radiographic data of selected pulsars. His work contemplates the profound space-time distance the signals of dying stars travel to communicate their death throes.

Jeremy Sharma instigates investigative processes to inform the formal expressions of his painterly and sculptural practice.

<hr>

<h5><strong>Islands in Between<br>… The seas will sing and the wind will carry us… (Fables of Nusantara)</strong><strong style="color:#484848 !important"> | by Sherman Ong</strong></h5>
**Promenade, Level 9**

![Sherman Ong, Video stills from Fables of Nusantara (2015)](/images/event-images/geographic/geographic-main-image-5.jpg){: .normal-width-img}
<div class="default-p"><small class="image-caption">Sherman Ong<br>Video stills from Fables of Nusantara (2015)</small></div>
<p>&nbsp;</p>

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
<div class="resources-url-style">
          <a href="http://eresources.nlb.gov.sg/printheritage/browse/from_the_stacks.aspx" target="_blank">Browse digitised books</a>
</div>
  
Click on the button below to to read BiblioAsia: Highlights of the National Library.
<div class="resources-url-style">
          <a href="http://www.nlb.gov.sg/biblioasia/vol-11-issue-4-jan-mar-2016/" target="_blank">Browse articles from BiblioAsia</a>
</div>

Browse the image gallery below for the exhibition’s Activity Booklet.
<div markdown="1" class="default-p">
[![From the Stacks Booklet Page 1](/images/event-images/from-the-stacks-onsite/from-the-stacks_booklet_page_01-low.jpg)](/images/event-images/from-the-stacks-onsite/from-the-stacks_booklet_page_01-high.jpg){: .inline50}
[![From the Stacks Booklet Page 2](/images/event-images/from-the-stacks-onsite/from-the-stacks_booklet_page_02-low.jpg)](/images/event-images/from-the-stacks-onsite/from-the-stacks_booklet_page_02-high.jpg){: .inline50}
[![From the Stacks Booklet Page 3](/images/event-images/from-the-stacks-onsite/from-the-stacks_booklet_page_03-low.jpg)](/images/event-images/from-the-stacks-onsite/from-the-stacks_booklet_page_03-high.jpg){: .inline50}
[![From the Stacks Booklet Page 4](/images/event-images/from-the-stacks-onsite/from-the-stacks_booklet_page_04-low.jpg)](/images/event-images/from-the-stacks-onsite/from-the-stacks_booklet_page_04-high.jpg){: .inline50}
[![From the Stacks Booklet Page 5](/images/event-images/from-the-stacks-onsite/from-the-stacks_booklet_page_05-low.jpg)](/images/event-images/from-the-stacks-onsite/from-the-stacks_booklet_page_05-high.jpg){: .inline50}
[![From the Stacks Booklet Page 6](/images/event-images/from-the-stacks-onsite/from-the-stacks_booklet_page_06-low.jpg)](/images/event-images/from-the-stacks-onsite/from-the-stacks_booklet_page_06-high.jpg){: .inline50}
[![From the Stacks Booklet Page 7](/images/event-images/from-the-stacks-onsite/from-the-stacks_booklet_page_07-low.jpg)](/images/event-images/from-the-stacks-onsite/from-the-stacks_booklet_page_07-high.jpg){: .inline50}
[![From the Stacks Booklet Page 8](/images/event-images/from-the-stacks-onsite/from-the-stacks_booklet_page_08-low.jpg)](/images/event-images/from-the-stacks-onsite/from-the-stacks_booklet_page_08-high.jpg){: .inline50}
[![From the Stacks Booklet Page 9](/images/event-images/from-the-stacks-onsite/from-the-stacks_booklet_page_09-low.jpg)](/images/event-images/from-the-stacks-onsite/from-the-stacks_booklet_page_09-high.jpg){: .inline50}
[![From the Stacks Booklet Page 10](/images/event-images/from-the-stacks-onsite/from-the-stacks_booklet_page_10-low.jpg)](/images/event-images/from-the-stacks-onsite/from-the-stacks_booklet_page_10-high.jpg){: .inline50}
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
#### **_From the Stacks_ Giftaways**
Fancy trying your hand at vintage recipes? Or going back to a time where library borrowing cards were used? How about bringing home quaint pictures of old-time Singapore?

We are giving away an assortment of souvenirs such as recipe cards, library cards and photo reproductions of old Singapore. Take one of these mementoes home when you visit the exhibition! #

#Souvenirs are subject to availability, while stocks last. Each visitor is entitled to one souvenir per visit.

You can also participate in our monthly Facebook quiz and stand a chance to win^ a framed photo of old Singapore by G. R. Lambert & Co. – a renowned photography studio in the late 19th century. Simply like our Facebook page **@NationalLibrarySG** and keep a lookout for the online quiz on the second Sunday of every month!

^Two winners will be selected monthly for each quiz. [Terms and conditions apply](/files/from-the-stacks-onsite/TCs-for-From-the-Stacks-Monthly-FB-Quiz.pdf){: target="_blank"}.

<p style="color:red;">(Event has ended, registration is closed.)</p>

<hr>

#### **Programmes**
Public Tours
Join our curator- or docent-led weekend tours and discover the rich treasures and fascinating stories of Singapore’s published heritage from the collections of the National Library.

Your journey begins here.

##### **Curator’s Tour**
Conducted in English | 7.30pm – 8.30pm
19 Feb, 18 Mar, 15 Apr, 27 May, 17 Jun, 15 Jul, 19 Aug 2016

Conducted in English | 7.00pm – 8.00pm
2 Sep 2016

Meeting point: Level 10, outside the Gallery entrance
<p>Admission is free. <span style="color:red;">(Programme has ended, registration is closed.)</span></p>

##### **策展员导览**
华语讲解 | 晚上七时到八时
2016年9月16日（星期五）

集合地点: 国家图书馆大厦10楼展厅外
<p>入场免费｡ <span style="color:red;">(Programme has ended, registration is closed.)</span></p>

##### **Weekend Tours**
Conducted in English | 1.00pm – 2.00pm
All Saturdays and Sundays from 20 February to 28 August 2016*

Meeting point: Level 10, outside the Gallery entrance
<p>First-come first-served basis. Admission is free. <span style="color:red;">(Programme has ended, registration is closed.)</span></p>

<strong>*There will be no tours on public holidays.</strong>

##### **周末导览**
华语讲解 | 下午一时半到二时半
每逢星期六﹐从2016年2月20日至8月27日*

集合地点: 国家图书馆大厦10楼展厅外
<p>入场免费｡ 团额有限，额满即止。<span style="color:red;">(Programme has ended, registration is closed.)</span></p>

<strong>*公共假日导览暂停｡</strong>

##### **School Tours**
Experience the history of Singapore through the National Library’s exhibition featuring rare publications, manuscripts, documents, maps, photographs and other resources.

Guided school tours can be arranged for students who will receive the specially produced From the _Stacks: Activity Booklet on Singapore History_. Through puzzles, illustrations, maps and photographs, students will be able to learn and apply the 5W1H approach of research and Information Literacy (IL).

Schools also have the option of enhancing the tour with a customised IL workshop that will teach the critical aspects of research, especially in analysing and using content from a variety of resources.

Interested schools can email [visitnls@nlb.gov.sg](mailto:visitnls@nlb.gov.sg) for more details.
<p>Book early to secure a tour slot! <span style="color:red;">(Programme has ended, registration is closed.)</span></p>

<hr>

#### **180年前新加坡刊行的一部中文小说 -《是非略论》**
**华语讲座 | 2016年1月30日（六）,下午二时到四时 Possibility Room﹐五楼**

讲员：庄钦永博士﹐新加坡新跃大学新跃中华学术中心兼任研究员

1835年﹐新加坡坚夏书院出版了传教士郭实猎（Karl F. A. Gützlaff, 1803-1851）所著的小说《是非略论》— 一部鸦片战争前撰写的重要文学创作｡通过小说﹐著者为旅居广州之泰西人呐喊：他们不满在中国所受到的歧视与限制｡演讲将探讨小说之创作背景﹐将文本与档案进行比读﹐深入挖掘其纸背后之深意以及弦外之音｡

<p style="color:red;">(Programme has ended, registration is closed.)</p>

<hr>

#### **A Chinese Novel Published in Singapore in 1835 – _Shi fei lüe lun (A Brief Discussion of Right and Wrong)_ by Karl F. A. Gützlaff (1803-1851)**
**Conducted in Mandarin | Saturday, 30 Jan 2016,
2.00pm – 4.00pm | Level 5, Possibility Room**

**Speaker: Dr David K. Y. Chng**

![Portrait of Karl F.A.Gützlaff](/images/event-images/from-the-stacks-onsite/FTS02.jpg){: .normal-width-img}

The talk will focus on the novel _Shi fei lüe lun (A Brief Discussion of Right and Wrong)_ written by Protestant missionary Karl F. A. Gützlaff (1803-1851), published in Singapore in 1835 by the American Board Mission Press. It is a very important piece of literature that sheds light on Sino-British relationships in the 1830s. The talk will also explore the historical context of the novel.

Dr David K. Y. Chng is a part-time researcher at the UniSIM Centre for Chinese Studies, SIM University.

<p style="color:red;">(Programme has ended, registration is closed.)</p>

<hr>

#### **In Honour of Dead Friends: The Ethics of Antiquarian Book Collecting** 
**Thursday, 18 Feb 2016, 7.00pm – 9.00pm | Level 16, The Pod**

**Speaker: Dr Farish A. Noor**

Books are the repositories of ideas and world views of those who have come before us, offering a glimpse into other life-worlds that in turn present us with alternative ways of understanding our world. Book collectors, therefore, play an essential role in preserving our published heritage.

Join Dr Farish A. Noor as he shares his 30-year journey of collecting antiquarian books and maps related to Southeast Asia.

Dr Farish A. Noor is an associate professor at the S. Rajaratnam School of International Studies (RSIS), Nanyang Technological University. His research covers topics ranging from Southeast Asian history to contemporary politics, material culture, art and antiquities as well as the media. He is a collector of antiquarian books, maps, prints, photos and memorabilia of Southeast Asia since the 1980s, and is a valued donor to the National Library Board of Singapore.

<p style="color:red;">(Programme has ended, registration is closed.)</p>

<hr>

#### **Birdwatching & Exhibition Tour with Nature Society Singapore (NSS)**
**Saturday, 19 Mar 2016, 8:30am – 12.00pm
National Library Building and Labrador Park**

![An Illustration from Birds of the Malay Peninsula featuring the Eastern Swallow, a frequently spotted bird in Singapore](/images/event-images/from-the-stacks-onsite/FTS03.jpg){: .normal-width-img}

Within the National Library’s exhibition _From the Stacks_, is a beautifully illustrated series of books titled _Birds of the Malay Peninsula_ that date as far back as 1927. Published by the earliest ornithologists in Singapore, Frederick Chasen and Herbert Robinson, the book details hundreds of bird species found in Malaya up to 1976.

In the spirit of exploration, join us for a fascinating walk around Labrador Park to identify and observe birds in their natural habitat.

This tour is organised in partnership with the Nature Society Singapore.

##### **Programme**

**8.30am** | Meet up @ NL Building lobby, level 1 (chartered bus to Labrador Park)
**9.00am** | Introduction to birds and birdwatching
**10.30am** | Return to the National Library
**11.00am** | Tour of From the Stacks exhibition
**12.00pm** | End of programme

A bus will be chartered to bring participants to and from Labrador Park. Participants are advised to dress comfortably (e.g. walking shoes) as well as to bring their own water and binoculars. To join this tour, please email visitnls@nlb.gov.sg with the subject “Birdwatching Tour”, indicating if rental of binoculars is required ($10 per pair).

<p style="color:red;">(Programme has ended, registration is closed.)</p>

<hr>

#### **Art and Cartoons about the Japanese Occupation in Singapore and Malaysia**
**Saturday, 19 Mar 2016, 3.00pm – 4.30pm
Level 5, Possibility Room**

**Speaker: Mr Lim Cheng Tju**

70 years after the end of World War II and 50 years after Singapore’s independence, the Japanese Occupation remains a pivotal period in the history of Singapore. Its importance in nation-building and national education can be seen in textbooks and commemorative dates such as Total Defense Day. Besides textual materials (documents, speeches, diaries, etc), art and cartoons are also important sources of history. What can art and cartoons tell us about the Japanese Occupation in Singapore through how it is portrayed and remembered? This short sharing will examine artist Liu Kang’s _Chop Suey_ (1946), a collection of cartoons about the Japanese Occupation; Lim Yew Kuan’s _Lingering Fear_ (1954), a painting depicting the arrest of his older brother by the Kempeitai in 1944; and a set of cartoons drawn by artist Abdullah Ariff during the Japanese Occupation of Penang in 1942.

Lim Cheng Tju is an educator with an interest in history and popular culture. His articles have appeared in the _Southeast Asian Journal of Social Science, Journal of Popular Culture_ and _Print Quarterly_. He is the country editor (Singapore) for the _International Journal of Comic Art_ and also the co-editor of _Liquid City 2_, an anthology of Southeast Asian comics published by Image Comics. He is one of the authors of _The University Socialist Club and the Contest for Malaya: Tangled Strands of Modernity_ (Amsterdam University Press/National University of Singapore Press).

<p style="color:red;">(Programme has ended, registration is closed.)</p>

<hr>

#### **Conservation Talk by National Archives of Singapore (NAS)**
**Saturday, 16 Apr 2016, 2:30pm – 4.00pm
Level 5, Imagination Room**

![Book pages being repaired through application of glue to its interior spine](/images/event-images/from-the-stacks-onsite/FTS04.jpg){: .normal-width-img}

**Speakers: Dr Phang Lai Tee and Mr Chng Yak Hock**

Ever wondered how Singapore’s historical archives are conserved and preserved? What can you do to safely keep your own family records?

Hear from Dr Phang Lai Tee, Senior Assistant Director, Audio Visual Archives, National Archives of Singapore (NAS), as she shares about NAS’s role in preserving the nation’s audio-visual archives including family videos, broadcast archives and music albums.

Learn from Conservator, Mr Chng Yak Hock, who will introduce the art of paper conservation performed by NAS and provide advice on what you can do to maintain your old paper records at home.

<p style="color:red;">(Programme has ended, registration is closed.)</p>

<hr>

#### **From Priest to an Islamic Reformer – The Life, Works and Legacy of Abdullah Bin Abdul Kadir Munsyi (1796-1854)**
**Saturday, 7 May 2016, 2.30pm – 4.00pm
Level 5, Imagination Room**

**Speaker: Dr Hadijah Rahmat**

Find out more about the life, works, influences and legacy of Abdullah bin Abdul Kadir Munsyi (1796-1854), a prominent and controversial 19th century Malay writer.  Abdullah is widely regarded as the father of modern Malay-Indonesian literature and his works, especially his autobiography (_Hikayat Abdullah_, 1849) and travelogue (_Kisah Pelayaran Abdullah_, 1838), were promoted by both British and Dutch colonial institutions.  However, Abdullah’s pro-colonial stance was strongly criticized by some, with his own communities seeing him as a ‘British stooge’ and mocking him as ‘Abdullah Paderi’ (Abdullah the Priest). Only in the early 21st century was Abdullah regarded by scholars to be an Islamic Reformer. Join Dr Hadijah as she traces Abdullah’s legacy in Southeast Asia, Europe and the United States and sheds light on the man and his works.

Dr Hadijah Rahmat is an Associate Professor and Covering Head/ Deputy Head of the Asian Languages and Cultures Academic Group, Nanyang Technological University. She received her PhD from the School of Oriental and African Studies, University of London in 1996 and was a Fulbright Visiting Scholar at the University of California Berkeley; Library of Congress, Washington D.C. and Harvard University (2002-2003). She was an Affiliated Fellow at the International Institute of Asian Studies, University Leiden, Netherland (2010) and Visiting Scholar at School of Oriental and African Studies, University of London (2011).

<p style="color:red;">(Programme has ended, registration is closed.)</p>

<hr>

#### **A Printmaker’s Tale**
**Saturday, 25 Jun 2016, 2.30pm – 4.00pm
Level 5, Possibility Room**

**Speaker: Ms Lim Bee Ling**

In this interactive session, artist and educator, Lim Bee Ling, will share with audiences different printmaking techniques through the ages. She will also showcase various matrixes and prints. Participants will get the chance to see these various print mediums up close.

Lim Bee Ling is a lecturer from the School of Fine Arts at LASALLE College of the Arts. Bee Ling has been practicing printmaking as a major art form. Her works deal with the notion of physical space as a medium of collective memory through the material and method she works with. She approaches this topic by manipulating the different printing principles in art-making, using archived images which are rooted in the memory of national identity.

<p style="color:red;">(Programme has ended, registration is closed.)</p>

<hr>

#### **Chinese Identity and Loyalty in Singapore in the 19th and 20th Centuries**
**Tuesday, 26 Jul 2016, 7.00pm – 9.00pm
Level 16, The Pod**

**Speaker: Prof Wang Gungwu**

Chinese identity and loyalty to home and country among the Chinese in 19th and 20th centuries evolved over time. Deep cultural links to family origin and anti-colonial movements were some of the sentiments impacting these changes. Join Professor Wang Gungwu, Chairman of the East Asian Institute and University Professor at the National University of Singapore, as he traces the shifts in identity and loyalty of the Chinese in Singapore from the 19th century to post independence in 1965.

Besides holding key appointments such as Chairman of the East Asian Institute, Chairman of the Lee Kuan Yew School of Public Policy, Chairman of the Institute of Southeast Asian Studies, and University Professor, National University of Singapore, Professor Wang Gungwu was also conferred the International Academic Prize and Fukuoka Asian Cultural prizes. He has written numerous publications in both English and Chinese, such as _The Chinese Overseas: From Earthbound China to the Quest for Autonomy_ (2000); _Don’t Leave Home: Migration and the Chinese_ (2001); and _Diasporic Chinese Ventures_  (edited by Gregor Benton and Liu Hong, 2004).

<p style="color:red;">(Programme has ended, registration is closed.)</p>

<hr>

#### **Heritage Food Talk & Cooking Demonstration**
**Saturday, 6 Aug 2016, 2.30pm – 4.00pm
Level 5, Possibility Room & Courtyard**

**Speaker: Ms Aziza Ali**

Join former chef and restaurateur, Aziza Ali, in this interactive session as she shares about the food from her childhood as well as traditional Malay heritage foods. Participants can also look forward to a cooking demonstration by Aziza using some of her family recipes.

Aziza Ali is a former chef, food consultant, business person, artist, jeweler, and author. She is credited with opening Singapore’s first Malay restaurant, as well as introducing the concept of Malay fine-dining to Singapore.

<p style="color:red;">(Programme has ended, registration is closed.)</p>

<hr>

#### **Picturing the Past: 19th-century Photographs of Singapore**
**Saturday, 20 Aug 2016, 2.30pm – 3.30pm
Level 5, Imagination Room**

**Speaker: Ms Gretchen Liu**

In the days before easy amateur photography and picture postcards, travellers had to purchase large-format topographical views supplied by professional photographic firms. As a transportation hub and busy port city, Singapore was home to several such firms from the 1860s. Today these remarkable images are prized as important records of the island’s rapidly changing landscape.  In her illustrated talk, writer Gretchen Liu will introduce the main photographers on the scene then and discuss their contributions to Singapore’s visual heritage.

Gretchen Liu is a former journalist and book editor with a keen interest in Singapore’s visual heritage. She is the author of several illustrated books relating to Singapore history and architecture including A Pictorial History of Singapore 1819-2000.

<p style="color:red;">(Programme has ended, registration is closed.)</p>

<hr>

#### **Featurette | Vice & Virtue: 1800s Singapore**
From colonial power struggles to government sanctioned drug cartels and prostitution rings, 19th century Singapore was full of fantastic stories of vice and virtue. Join academic and history lover, Dr Farish A. Noor, as he takes us on a journey to uncover these forgotten stories buried in a treasure trove of rare collections.

_Vice & Virtue: 1800s Singapore_ was broadcasted on Channel NewsAsia.

Selected artefacts in the exhibition are showcased in this documentary.

![Journal of a Tour Along the Coast of Java and Bali, published by Mission Press](/images/event-images/from-the-stacks-onsite/FTS05.jpg){: .normal-width-img}

<hr>

#### **Roving Exhibition**

![A showcase of some of the interesting library finds](/images/event-images/from-the-stacks-onsite/FTS06.jpg){: .normal-width-img}

<hr>

#### **Library Finds!**
What is the last thing you would expect to find at the National Library? Satisfy your curiosity as you explore cabinets and drawers full of ephemera from the library’s closed shelves. An eclectic assortment of bits and bobs, explore a different side of history through the odds and ends of our collection.

Public Library | Date
---|---
Tampines Regional Library	| 18 Jan – 28 Feb 2016
Toa Payoh Public Library | 29 Feb – 24 Apr 2016
Jurong Regional Library	| 25 Apr – 19 Jun 2016
Woodlands Regional Library | 20 Jun – 31 Aug 2016

This exhibition is a roving component of _From the Stacks: Highlights of the National Library_.

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


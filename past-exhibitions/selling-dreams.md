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
[![From Books to Bytes Microsite](/images/event-images/sellingdreams/selling-dreams-thumbnail.jpg)](http://nlb.gov.sg/exhibitions/sellingdreams/){: .normal-width-img target="_blank"}
<div style="text-align:center;" markdown="1">  
[Click to access the online exhibition.](http://nlb.gov.sg/exhibitions/sellingdreams/)
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
#### **Talk | Early Advertising in Singapore (Fashion, Hospitality and Entertainment)**
**A Librarian’s World
Date: 26 July 2018
Time: 7.00pm – 8.00pm
Venue: Level 5, Possibility Room, National Library Building**
<i>Free admission.</i> <i style="color:red;">(Programme has ended, registration is closed.)</i>

**A Librarian’s World@PL
Date: 1 Sep 2018
Time: 2.00pm – 3.00pm
Venue: library@orchard**
<i>Free admission.</i> <i style="color:red;">(Programme has ended, registration is closed.)</i>

Join us as we reconstruct life and lifestyles in Singapore based on print advertisements from the 1830s to 1960s. Come and discover Singapore’s fashion trends across different cultures and eras as well as the early days of our local hospitality, F&B and entertainment industries.

This programme is organised in conjunction with the series A _Librarian’s World_.

##### **About the Speakers**
**Akshata Patkar** is the Assistant Manager (Research) of Content and Services at the National Library. She conducts research into public policy and current affairs and has a keen interest in cultural studies.

**Fiona Lim** is an Associate Librarian with the National Library’s Singapore and Southeast Asia team. She is interested in the interrogation of places and their histories as a means of engaging with the city. She is both a contributor to and editor of the publication _Between the Lines: Print Advertising in Singapore 1830s – 1960s_.

**Goh Yu Mei** is a Librarian at the National Library. She works with the Chinese arts and literary collection and has recently updated the Bibliography of Singapore Chinese Literature. Her research interest lies in the interaction between society and Chinese literature.

<hr>

#### **Talk | The Sticky Tricky History of Advertising in Singapore**
**Date: 4 Aug 2018
Time: 2.00pm – 3.00pm
Venue: Level 5, Possibility Room, National Library Building**
<i>Free admission.</i> <i style="color:red;">(Programme has ended, registration is closed.)</i>

Before advertising agencies started to use computers in the mid-1990s, advertising production was very much craft-based, with artists sticking down type and photographs for press advertisements and editing film footage with cutters and adhesive tape.

Join Allein Moore as he shares his memories of his career, taking us back to the early years of advertising in Singapore.

##### **About the Speaker**
**Allein Moore** is one of the pioneers of Singapore advertising and is a well-known figure in the industry. He is the founder and curator of Advertising Archive Asia, which aims to preserve advertising and design work.

<hr>

#### **Selling Dreams @ Singapore Night Festival**
Wander about the library’s ‘department store’ and discover the rich treasures and fascinating stories of Singapore’s published heritage through the medium of advertising. During the Singapore Night Festival, the exhibition’s opening hours will be extended until 11.30pm. During this period, our curators will lead special tours that will be available on Saturday nights.

**Exhibition 
17 & 18 Aug 2018, 24 & 25 Aug 2018
Time: 10.00am – 11.30pm
Venue: Level 10, Gallery, National Library Building**
<p style="color:red;">(Event has ended.)</p>

##### **Curator’s Tours**
**18 & 25 Aug 2018
Time: 9.00pm – 10.00pm
Meeting point: Level 10, Gallery entrance, National Library Building**
<i>Free admission.</i> <i style="color:red;">(Programme has ended, registration is closed.)</i>
![selling dreams curator tour](/images/event-images/sellingdreamsonsite/SNF_Credit_Line_Black_940x323.jpg)

<hr>

#### **Talk | Survey of Tamil and Malay Ads in 20th century Singapore**
**Date: 27 Sep 2018
Time: 7.00pm – 8.00pm
Venue: Level 5, Possibility Room, National Library Building**
<i>Free admission.</i> <i style="color:red;">(Programme has ended, registration is closed.)</i>

Join librarians Sundari and Nadirah as they share the trends and variety of Tamil and Malay advertisements from the National Library’s collections. From beauty, food and fashion, discover how advertisements offer glimpses into the lifestyles and world views of local communities.

This programme is organised in conjunction with the series _A Librarian’s World_.

##### **About the Speakers**
**Nadirah Norruddin** is an Associate Librarian (Singapore, Southeast Asia and Exhibitions) at the National Library. Her main responsibility is managing and developing the Singapore and Southeast Asia collection. Her research interest is in the customs and traditions of the Malay world.

**Sundari Balasubramaniam** is a Librarian with the National Library. She compiled three publications. _A Selection of Singapore Tamil Literature, 1872-2009, Annotated Bibliography of Tamil Short Stories and Poetry, 1936-1960 and Literary Criticism of P. Krishnan’s (Puthumaithsan) Works._

<hr>

#### **Talk | Selling Dreams | Behind the Dreams: The Curators’ Perspective**
**Date: 11 Oct 2018
Time: 7.00pm – 8.00pm
Venue: Level 5, Possibility Room, National Library Building**
<i>Free admission.</i> <i style="color:red;">(Programme has ended, registration is closed.)</i>

Join the curators of the National Library’s latest exhibition, _Selling Dreams: Early Advertising in Singapore_, as they share what went on behind the scenes, their curatorial processes as well as the untold stories they discovered in the library’s extensive collection of advertising materials.

##### **About the Curators**
**Chung Sang Hong** is an Assistant Director (Exhibitions & Curation) at the National Library. He is the lead curator of _Selling Dreams: Early Advertising in Singapore_. He is interested in the social history of Singapore.

**Georgina Wong** is an Assistant Curator at the National Library. She is the co-curator of _Selling Dreams: Early Advertising in Singapore._ Her research interests include historical architecture and decorative art history.

<hr>

#### **讲座 | Selling Dreams | 幸福青春梦：1880年代至1960年代新加坡华文报纸广告中的爱与性**
**日期: 2018年10月19日
时间: 晚上七时到8时30分
地点: The Pod, 十六楼**
<i>入场免费。</i> <i style="color:red;">(Programme has ended, registration is closed.)</i>

“既达荷尔蒙期则顺应自然的本能而繁殖之。”看到这则1931年的报纸广告，你能猜出它诉求的是什么吗？

本讲座陪同听众翻阅1880年代到1960年代的新加坡华文报纸，从文图学(Text and Image Studies)的角度，概观和分析早期华文广告中所传达的性爱经济和幸福追求。

内容将包括：广告中的青春梦想；爱慾和性力；性知识．性产品．医疗消费。

本讲座由文图学会和新加坡国家图书馆联合主办。

(本讲座涉及成人话题，请斟酌参与。)

##### **讲员简介**
衣若芬，台湾大学中国文学博士，现任教于新加坡南洋理工大学，新加坡《联合早报》专栏作家，「文图学」创发人，「文图学会」荣誉主席。研究领域为文图学、苏轼研究、东亚汉文学与文化交流。出版学术专著和文学创作20多部，包括《南洋风华：艺文．广告．跨界新加坡》(新加坡：八方文化创作室，2016年) ，本书荣获《联合早报》2016年书选。

<hr>

#### **Talk | Selling Dreams | A.I. – The Future of Advertising (But it’s not what you think)**
**Date: 24 Nov 2018
Time: 2.00pm – 3.00pm
Venue: Level 5, Possibility Room, National Library Building**
<i>Free admission.</i> <i style="color:red;">(Programme has ended, registration is closed.)</i>

As with much of the world, the future of advertising lies in A. I., but not the Artificial Intelligence you are probably thinking of. With the dawn of the fourth industrial revolution, came the advent of A.I. – Augmented Interest and Added Information.

The key to staying ahead of the curve is to think like a Renaissance polymath. After all, knowledge is power. Come join us and find out how you can be the future of the industry.

##### **About the Speaker**
A multi-awarded creative and strategic communications leader, **James Keng Lim**’s career has spanned 20 years. He has experience in network and independent advertising, as well as digital and PR agencies – including running his own integrated communications agency – across cities such as Singapore, Kuala Lumpur, Shanghai, Dubai and Amsterdam.

<hr>

#### **Talk | Selling Dreams | The Journey of a Mad Man**
**Date: 19 Jan 2019
Time: 2.00pm – 3.00pm
Venue: Level 5, Possibility Room, National Library Building**
<i>Free admission.</i> <i style="color:red;">(Programme has ended, registration is closed.)</i>

Join Peter Soh as he shares his journey from a humble traffic assistant to regional chief creative officer of Saatchi & Saatchi – as well as becoming a judge at local and international award shows – all without any formal training.

##### **About the Speaker**
**Peter Soh** founded the World Chinese Creative Awards, or “Long Xi”, with a few good men – Jimmy Lam, David Sun and Tomaz Mok. Today, it is the only Chinese award that is recognised by the western world. A well-respected figure in the advertising circle of greater China, Peter also sits on the Worldwide Creative Board.

<hr>

#### **Talk | Selling Dreams | Selling Utopia: The Good Life as a Commodity in Singapore’s Early Advertisements**
**Date: 2 Feb 2019
Time: 2.00pm – 3.15pm
Venue: Level 5, Possibility Room, National Library Building**
<i>Free admission.</i> <i style="color:red;">(Programme has ended, registration is closed.)</i>

From the pre-modern to contemporary periods, Singapore has had a vibrant history of being imagined as a utopia. Most of these were top-down political narratives, but it was with the onset of print media that utopia began to be packaged as a commodity. Focusing on print advertisements from the late 19th and early centuries, this talk will examine specific imaginings of the Singapore Dream. In doing so, it aims to unveil the underlying prevailing worldviews that dominated these periods, while also making the case that the study of popular culture is serious business.

This session will also feature a short 15-minute presentation by SUTD students about their digital exhibits for ‘Selling Dreams: Early Advertising in Singapore’.

##### **About the Speaker**
**Dr Nazry Bahrawi** is senior lecturer at Singapore University of Technology and Design (SUTD). As a literary critic, he specialises in the comparative study of Muslim texts, thoughts and traditions of Indian Ocean cultures between Southeast Asia and the Middle East.

<hr>

#### **Talk | Selling Dreams | Japanese Brand Presence in Singapore Since the 19th Century**
**Date: 19 Feb 2019
Time: 7.00pm – 8.30pm
Venue: Level 5, Possibility Room, National Library Building**
<i>Free admission.</i> <i style="color:red;">(Programme has ended, registration is closed.)</i>

It is generally thought that Japanese products and services were only present in Singapore from the 1940s onwards. However, there is evidence of Japanese brand presence in Singapore’s “Little Japan” (spanning Hylam, Malabar and Malay streets) from as early as the 19th century. Advertisements from the 1830s to 1930s publicising Japanese curios, stores, dentists, photographers, hotels, masseuses and even a fishing pond all point to the presence of Japanese products and services in early Singapore.

Join Peter Ling as he shares part of his fascinating research on Japanese advertising in Singapore between the 19th and 21st centuries.

##### **About the Speaker**
**Peter Ling** was an advertising practitioner and president of the Association of Accredited Advertising Agents in Singapore before working in the cities of Taipei, Perth and Melbourne. He is the author of _[Be the Innovators](https://www.oup.com.au/books/higher-education/management-and-marketing/9780195590173-be-the-innovators)_ as well as the lead author of _[Consumer Behaviour in Action](https://www.oup.com.au/books/higher-education/management-and-marketing/9780195525601-consumer-behaviour-in-action)_, both published by Oxford University Press (OUP). His third title, _Integrated Marketing Communication: A balanced approach_ (OUP), will be published in mid-2019. He is currently a Visiting Fellow at the Wee Kim Wee School of Communication and Information at Nanyang Technological University, Singapore. Between 2011 and 2017, he was an [associate/deputy dean](http://rmitlibrarynews.blogspot.com/2017/10/rmit-author-showcase-associate.html) at RMIT University, Australia.

<hr>

#### **Talk | Selling Dreams | Decoding Advertisements: The Semiotics of Print Advertisements**
**Date: 23 Feb 2019
Time: 2.00pm – 3.00pm
Venue: Level 5, Possibility Room, National Library Building**
<i>Free admission.</i> <i style="color:red;">(Programme has ended, registration is closed.)</i>

Product advertisements, in essence, are created to offer consumers choices. They persuade us to give ourselves a chance to transform ourselves – and our lives – for the better, through the simple act of choosing to purchase something. The addiction to buying and consumption leads to consumerism as a means to obtain a better life by way of capitalism.

But what lay beneath consumerism in the early settlement of Singapore? In this dialogue, Olivia will share about the significance of the images and text behind the design of print advertisements from early Singapore.

##### **About the Speaker**
**Jessica Olivia** earned her Master Degree in Arts (Design) in 2007 and has 10 years of industry experience as an Art Director at various advertising agencies under her belt. In the course of her creative career, Olivia has translated strategic thinking into big ideas. She is a firm believer of using good design fundamentals in her teaching delivery and many of her students have gone on to become successful designers. She is currently teaching at School of Design Communication, LASALLE College of the Arts.

<hr>

#### **Tours | Selling Dreams | Curator’s Tours (English)**
Join our curator-led tours and discover the rich treasures and fascinating stories of Singapore’s published heritage through the medium of advertising.

**Every third Thursday of the month**

**2018** | **16 Aug, 20 Sept, 18 Oct, 15 Nov, 20 Dec**

**2019** | **17 Jan, 21 Feb**

**Time: 7.00pm – 8.00pm**

**Meeting point: Level 10, Gallery entrance**

<i>Free admission. Tours will be conducted in English.</i> <i style="color:red;">(Programme has ended, registration is closed.)</i>

<hr>

#### **Tours | Selling Dreams | Public Tours (English)**
Join our docent-led tours and discover the rich treasures and fascinating stories of Singapore’s published heritage through the medium of advertising.

**Sep 2018 | 1, 2, 15, 16, 29 & 30 
Oct 2018 | 6, 7, 20 & 21 
Nov 2018 | 3, 4, 17 & 18 
Dec 2018 | 1, 2 & 15 
Jan 2019 | 5, 6, 19 & 20 
Feb 2019 | 16 & 17 
Time: 4.00pm – 5.00pm
Meeting point: Level 10, Gallery entrance**

<i>Led by docents. Free admission, first-come first-served basis.</i> <i style="color:red;">(Programme has ended, registration is closed.)</i>

<hr>

#### **Tours | Selling Dreams | 周末导览 （华语讲解**
**2018年9月 | 8/9/22/23日
2018年10月 | 13/14/27/28日
2018年11月 | 10/11/24/25日
2018年12月 | 8/9/22日
2019年1月 | 12/13/26/27日
2019年2月 | 23/24日
时间: 下午4时至5时
集合地点: 国家图书馆大厦10楼展厅门口**

<i>由义务导览员带领。 入场免费, 人数有限，先到先得 。</i> <i style="color:red">(Programme has ended, registration is closed.)</i>

<hr>

#### **Workshop | Selling Dreams | Chasing Dreams: Shopping in Old Singapore**
**Dates: 21 & 28 Jul, 4,11,18 & 25 Aug, 1 & 8 Sep, 6 Oct, 17 & 24 Nov 2018
Session 1: 2.30pm – 3.30pm
Session 2: 3.30pm – 4.30pm
(2 sessions per day)
Venue: Level 10, Learning Space, national Library Building**
<i>Free admission.</i> <i style="color:red;">(Programme has ended, registration is closed.)</i>

_Limited to 60 pax per session._
<i style="color:#d51918;">Each child must be accompanied by an adult/parent.</i>
_Each participant must purchase one ticket. If you are attending the event with your spouse and child, please purchase three tickets._ 

Calling all parents with children aged 7 to 12!

Come and explore what life was like in Singapore from the colonial era to the 1960s. Join us for this interactive programme set against the backdrop of Singapore’s early shopping scene.

Families will engage in hands-on activities to help their children understand the power of advertisements and strategies used to promote products and services. Facilitated by librarians, these fun and interactive sessions are opportunities for families to come together to solve puzzles as well as share experiences of what life in Singapore used to be like.
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

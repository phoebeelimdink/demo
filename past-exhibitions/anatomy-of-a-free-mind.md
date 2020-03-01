---
layout: post
title: "Anatomy of a Free Mind: Tan Swie Hian’s Notebooks and Creations"
date: 2020-01-01
permalink: /past-exhibitions/anatomy-of-a-free-mind
---

{% assign event-details = site.data.event-list %}

{% for thisevent in event-details.event %}
{% if thisevent.short-name == "aof" %}
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
1973 was a milestone year in Tan Swie Hian’s life during which he experienced a breakthrough in his spirituality and creative capacity. Henceforth, his artistic creations have been characterised by freedom – in medium, subject matter, genre and expression. The artist likens his newfound free mind to a hummingbird that can fly in all directions and experience different realms of reality.

Now, more than 40 years later, Tan’s works are presented again at the National Library in this exhibition featuring over 100 creations in a wide range of media. This is the first time the multidisciplinary artist’s creative process, as documented in his notebooks through writings and sketches, has been featured with his artworks.

Discover the extraordinary world of a free mind through Tan Swie Hian’s creations and notebooks!

**《解析自由心 – 陈瑞献稿本与创作》**

1973年可说是陈瑞献人生里一个重大的里程碑，他突破了自己在灵性上和艺术创作方面的极限。自此以后，他的创作无论是在媒材、主题、类型或表现手法各方面，都以自由为本。陈瑞献把他新发现的自由心比喻成一只蜂鸟，可以任意翱翔，体验不同境界的现实。

睽违40多年，陈瑞献的作品再次于国家图书馆登场。本展览展出了100多件各种媒材的作品；这位多媒体艺术家的创作过程，也透过他稿本中的草图与手稿，首次与他的作品一并呈现在展览中。

本展邀请您透过陈瑞献的艺术创作与稿本，一探这颗自由心非凡的境界!

Download a copy of the brochure by clicking the button below.

[Exhibition brochure](/files/aof/AOFM-A5-brochure-2-17012017.pdf){: .dl-style-1 target="_blank"}

### **About Tan Swie Hian 陈瑞献简介**
Tan Swie Hian was born in Indonesia in 1943. He was educated in Singapore and graduated from the Department of Modern Languages and Literature of Nanyang University in 1968.

Tan was first known for his literary works before he ventured into fine art. He published his first anthology of Modernist poetry The Giant (1968), which earned him recognition as a poet. In 1973, Tan held his first solo art exhibition at the National Library. Since then, he has been a prolific multidisciplinary artist whose works extend across multiple mediums, genres, languages and subject matters. In 2003, TIME magazine described him as “Singapore’s Renaissance Man”.

To date, the acclaimed artist has published 58 works of literary and artistic creations; held 23 solo shows worldwide and won 29 accolades nationally and internationally.

陈瑞献于1943年在印度尼西亚出生。他在新加坡受教育，1968年毕业于南洋大学现代语言文学系。

在涉足艺坛以前，陈瑞献是以文艺创作崭露头角的，他发表的第一部现代诗集《巨人》 (1968年) 使他成为备受瞩目的诗人。1973年, 陈瑞献在国家图书馆举行第一次个人画展。此后，他成了一位多媒体艺术家，作品极其丰硕。 他的创作跨越多元媒材、类型、语文及题材，2003年美国《时代周刊》称他为“新加坡的文艺复兴人”。

迄今，这位蜚声国际的艺术家已出版了58部文学与艺术作品集；在世界各地举办过23次个展；并荣获29项国家级与国际级的奖勋。
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
#### **Guided Tours**
##### **Anatomy of a Free Mind – Artist’s Tour**
**Wednesday, 25 Nov 2016
7.00pm – 8.30pm
Meeting point: Level 10, Gallery entrance, National Library Building**

Join internationally acclaimed artist Tan Swie Hian on this exclusive tour to discover the stories behind his various creations, personal notebooks, manuscripts and artefacts.

<p style="color:red;">(Programme has ended, registration is closed.)</p>

<div markdown="1" class="default-p">
[![AOFM02](/images/event-images/aof/AOFM02-300x200.jpg)](/images/event-images/aof/AOFM02.jpg){: .inline30}
[![AOFM03](/images/event-images/aof/AOFM03-300x200.jpg)](/images/event-images/aof/AOFM03.jpg){: .inline30}
[![AOFM04](/images/event-images/aof/AOFM04-300x200.jpg)](/images/event-images/aof/AOFM04.jpg){: .inline30}
</div>

<hr>

#### **Curator’s Tours 策展员导览**
Join our curator-led tours every Friday and Saturday and discover the fascinating stories behind internationally acclaimed artist Tan Swie Hian’s various creations, personal notebooks, manuscripts and artefacts.

Meeting point: Level 10, Gallery entrance, National Library Building

每月一次于星期五或星期六，策展员将提供导览，带领您观赏蜚声国际的艺术家陈瑞献的各种作品，相关私人稿本和文物，了解作品背后精彩的故事。

集合地点：于国家图书馆大厦10楼展厅门口

December 2016
<ul>
<li>Fri, 16 Dec | 7pm – 8pm | Conducted in English</li>
<li>Sat, 17 Dec | 2pm – 3pm | Conducted in Mandarin  2016年12月17日 (周六)下午2点至3点</li>
</ul>

January 2017
<ul>
<li>Fri, 6 Jan | 7pm – 8pm | Conducted in Mandarin  2017年1月6日 (周五)晚上7点至8点</li>
<li>Sat, 7 Jan | 2pm – 3pm | Conducted in English</li>
</ul>

February 2017
<ul>
<li>Fri, 17 Feb | 7pm – 8pm | Conducted in English</li>
<li>Sat, 18 Feb | 2pm – 3pm | Conducted in Mandarin  2017年2月18日 (周六)下午2点至3点</li>
</ul>

March 2017
<ul>
<li>Fri, 10 Mar | 7pm – 8pm | Conducted in Mandarin  2017年3月10日 (周五)晚上7点至8点</li>
<li>Sat, 11 Mar | 2pm – 3pm | Conducted in English</li>
</ul>

April 2017
<ul>
<li>Fri, 21 Apr | 7pm – 8pm | Conducted in English</li>
<li>Sat, 22 Mar | 2pm – 3pm | Conducted in Mandarin 2017年4月22日 (周六)下午2点至3点</li>
</ul>

<p style="color:red;">(Programme has ended, registration is closed.)</p>

#### **周末员导览**
每逢周末，华语义务导览员将带领您参观展览，与您分享多媒体艺术家陈瑞献的作品背后丰富的涵义和精彩的故事。

集合地点：于国家图书馆大厦10楼展厅门口

<ul>
<li>2017年3月4日 (周六) 下午2点至3点</li>
<li>2017 3月5日 (周日) |下午2点至3点</li>
<li>2017 3月12日 (周日) |下午2点至3点</li>
<li>2017年3月18日 (周六) 下午2点至3点</li>
<li>2017 3月19日 (周日) |下午2点至3点</li>
</ul>

<p>Admission is free. <span style="color:red;">(Programme has ended, registration is closed.)</span></p>

<hr>

#### **Programmes**
##### **Art Journaling Workshop**
**Saturday, 18 February 2017
11.00am – 12.30pm
Level 5, Possibility Room
National Library Building**

Learn how artists record their ideas and inspiration in their art journals in this talk-and-demonstration that offers you a peek into their minds.
<p>Admission is free. <span style="color:red;">(Programme has ended, registration is closed.)</span></p>
[![AOFM05](/images/event-images/aof/AOFM05-300x66.jpg)](/images/event-images/aof/AOFM05.jpg)

<hr>

#### **Prominent Speaker Series: A Thousand-Year Debate on the Imagery of a Plantain Tree in Snow**
**Friday, 24 February 2017
7.00pm – 9.00pm
Level 16, The Pod
For access to the Pod, please proceed to lift lobby opposite the information counter.
Speaker: Tan Swie Hian**

The Tang poet-painter Wang Wei (699-761) is said to have made a painting depicting the noble man Yuan An of the Han Dynasty who, during a snow storm, refused to go out for his livelihood but to lie at home “as the snow is big when everyone is hungry, I should not go and trouble people.” In it, Wang also painted a plantain tree in the snow.

_Yuan An Reclining in Snow_ was first mentioned by its collector Shen Kua (1031-1095) of the Song Dynasty in his _Dream Pool Essays_. Ever since, not only has the subject become one of the perennial for artists throughout the ages, but the imagery of the plantain tree in snow has sparked debate among famed artists, critics, scholars and writers for well over a thousand years.

Plantain trees grow only in hot climates and snow falls only in cold countries. How can a plantain tree survive in the snow? Wang’s detractors comment that he cannot “tell cold and hot apart”. But Wang’s appreciators believe that “Wang disregards the seasons when creating”.

The painting that no one has ever seen since Shen Kua is long lost. But the debate on a non-existent work continues, creating an unprecedented phenomenon that merits meditation. Now, join acclaimed artist Tan Swie Hian as he weighs in on why Wang did what he did.

<p>Admission is free. <span style="color:red;">(Programme has ended, registration is closed.)</span></p>

<hr>

#### **Compassion: Tan Swie Hian’s Literary Creations – Roving Exhibition**
* **Jurong Regional Library: 1 November 2016 – 29 December 2016**
* **Central Public Library: 30 December 2016 – 28 February 2017**

Singapore Cultural Medallion recipient Tan Swie Hian is the top grossing living artist in Southeast Asia who has received numerous accolades both locally and abroad. Although he exhibited impressive artistic talents at a tender age, he was first recognised for his literary creations when he ventured into the arts scene.

Tan wrote and published prolifically in the 1960s under the pseudonym of “Mu Lingnu”. Before long, he had established a reputation for advocating Modernist literature in the local Chinese literary circle. He once said that his literary works “mostly reflected the dark side of reality; and the sorrows of human destiny”, thus compassion for lives has been a key theme in his writings. To date, the multilingual artist/writer has published close to 40 literary titles.

As a complement to the _Anatomy of a Free Mind: Tan Swie Hian’s Notebooks and Creations_ exhibition at National Library Building (22 November 2016 – 23 April 2017), this roving exhibition will feature Tan’s literary accomplishments in various genres – poetry, prose, novels, fables, translated works as well as publications edited by him. Visit the above libraries during the specified periods to learn more about Tan Swie Hian’s written works that took the literary world by storm.

#### **《悲悯人生：陈瑞献的文艺创作》巡回展**
* **裕廊区域图书馆: 2016年11月1日–2016年12月29日**
* **中央公共图书馆: 2016年12月30日–2017年2月28日**

新加坡文化奖得主陈瑞献是东南亚作品拍卖价最高的在世艺术家，他荣获多项本地及国际的奖项与殊荣，享有极高名声。他在年少时便展露非凡的艺术天分，但他刚开始涉足艺术领域时，却是先以文艺创作引起注意的。

1960年代，陈瑞献以笔名 “牧羚奴”发表大量作品，不久后便成了在本地华文文坛提倡现代主义文学的代表人物。他曾经说自己的文学作品 “多反映现实的阴暗面，以及人类悲苦的命运” ，因此对芸芸众生怀抱悲悯是他写作的一个主调。至今，他已出版了将近40部文艺著作。

为了配合在国家图书馆大厦举办的“解析自由心：陈瑞献稿本与创作”特展（2016年11月22日至2017年4月23日），本巡回展将着重介绍陈瑞献的多种文艺作品，如诗作、散文、小说、寓言、译作以及他所编辑的刊物。欲一览陈瑞献当年在文坛备受瞩目的作品，请于举办期间到上述图书馆参观展览。

<div markdown="1" class="default-p">
[![AOFM07](/images/event-images/aof/AOFM07-300x181.jpg)](/images/event-images/aof/AOFM07.jpg)
[![AOFM08](/images/event-images/aof/AOFM08-300x184.jpg)](/images/event-images/aof/AOFM08.jpg)
[![AOFM06](/images/event-images/aof/AOFM06-300x185.jpg)](/images/event-images/aof/AOFM06.jpg)
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

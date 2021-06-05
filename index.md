---
title: Lanka Data Foundation
subtitle: Supporting data integrity, transparency and accountability
layout: landing
# callouts: home_callouts
# show_sidebar: true
hero_height: is-large
# sponsors: example_sponsors
# tools: true
fixed_navbar: top
sort_tools: rating
# Slider Details
slide1_title: Lanka Data Foundation
slide1_subtitle: Strengthening transparency and accountability in governance through verified public data.
slide1_image: /assets/img/banners/banner1.jpg
slide1_link: #
slide1_button: Learn More
slide2_title: My Local
slide2_subtitle: Get insights into your neighborhood.
slide2_image: /assets/img/banners/banner2.jpg
slide2_link: /tools/mylocal.html
slide2_button: Learn More
slide3_title: Lanka Data Foundation
slide3_subtitle: Bringing Data Together
slide3_image: /assets/img/slide4.jpeg
slide3_link: 
slide3_button: Learn More
slides:
- title: Lanka Data Foundation
  subtitle: Strengthening transparency and accountability in governance through verified public data.
  image: /assets/img/banners/banner1.jpg
  link: #
  button: Learn More
- title: My Local
  subtitle: Get insights into your neighborhood.
  image: /assets/img/banners/banner2.jpg
  link: /tools/mylocal.html
  button: Learn More
---
<!-- <section class="section px-0 py-6 is-large" style="background-image: url( {{site.baseurl}}/assets/img/update2.jpg ); background-size: cover; background-position: center"> -->
<section class="section px-0 py-6 is-large" >
    <div class="container "> <!-- is-fluid p-0 m-0 -->
        <p class="title is-3 is-uppercase has-text-weight-bold">Latest News</p>
        <div class="columns">
            {% for post in site.posts limit:4 %}
            <div class="column is-3">
                {% include post-card.html %}
            </div>
            {% else %}
                <p> No News Items </p>
            {% endfor %}
        </div>
    </div>
</section>


{% include tools-card.html height="600" unit="px" duration="7" %}

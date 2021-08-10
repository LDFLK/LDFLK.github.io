---
layout: page
title: About Us
permalink: /about/
hero_image: /assets/img/slide6.jpeg

##---------------
## board memebers
##---------------
board:
- name: Dr. Sanjiva Weerawarana
  pic: sanjiva
  position: Founder, Director & CEO of WSO2

- name: Nuwan Senaratna
  pic: nuwans
  position: Founder & CEO of ColomboLabs Inc.
  
- name: Nishan De Mel
  pic: nishand
  position: Executive Director of Verite Research

##---------------
## team memebers
##---------------
team:
- name: Sherazad Hamit
  pic: sherazad
  position: Program Director

- name: Umayanga Gunawardhana
  pic: umayangag
  position: Software Engineer

---

<!-- # About Us -->
<div class="columns is-multiline is-mobile has-text-centered mt-3">
    <div class="column ">
        <div class="box is-family-monospace has-background-white-bis is-size-4 has-text-centered">
            <p>Lanka Data Foundation aims to make 100% of Sri Lanka's public data, digitized, efficiently processible, and accessible so Sri Lankans can make meaningful use of it.</p>
            <p>---</p>
        </div>

        <p> The Lanka Data Foundation (LDF) is a nonprofit organization, established in December 2019. Our mission is to make 100% of Sri Lanka's public data accessible, in a digitized format that supports efficient processing, to enable the general public to generate valuable insights, and increase accountability and transparency. </p>
        <p> Towards this, LDF aims to develop simple, user-friendly and cost-effective data tools to help organizations manage, analyze and share data more effectively.
        </p>

    </div>
</div>


### Board

---

<div class="columns is-multiline is-mobile has-text-centered">
    {% for member in page.board %}
        <div class="column is-one-fifth">
            <div class="card" style="height:100%;">
                <div class="card-image level-item">
                    <figure class="image is-128x128">
                    <img class="is-rounded" src="{{ site.baseurl }}/assets/img/people/{{ member.pic }}.png" alt="Placeholder image">
                    </figure>
                </div>
                <div class="card-content">
                    <div class="media">
                        <div class="media-content">
                            <p class="title is-5">{{ member.name }}</p>
                            <!-- <p class="subtitle is-6">@johnsmith</p> -->
                        </div>
                    </div>

                    <div class="content">
                        {{ member.position }}
                    </div>
                </div>
            </div>
        </div>
    {% endfor %}
</div>


### Team

---

<div class="columns is-multiline is-mobile has-text-centered">
    {% for member in page.team %}
        <div class="column is-one-fifth">
            <div class="card" style="height:100%;">
                <div class="card-image level-item">
                    <figure class="image is-128x128">
                    <img class="is-rounded" src="{{ site.baseurl }}/assets/img/people/{{ member.pic }}.png" alt="Placeholder image">
                    </figure>
                </div>
                <div class="card-content">
                    <div class="media">
                        <div class="media-content">
                            <p class="title is-5">{{ member.name }}</p>
                            <!-- <p class="subtitle is-6">@johnsmith</p> -->
                        </div>
                    </div>

                    <div class="content">
                        {{ member.position }}
                    </div>
                </div>
            </div>
        </div>
    {% endfor %}
</div>

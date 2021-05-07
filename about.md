---
layout: page
title: About LDF
permalink: /about/

##---------------
## board memebers
##---------------
board:
- name: Dr. Sanjiva Weerawarana
  pic: sanjiva
  position: Director

- name: Nuwan Senaratna
  pic: nuwans
  position: Director
  
- name: Nishan De Mel
  pic: nishand
  position: Director

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

# About Us
> Lanka Data Foundation aims to make 100% of Sri Lanka's public data, digitized, efficiently processible, and accessible so Sri Lankans can make meaningful use of it


### Board

---

<div class="columns is-multiline is-mobile">
    {% for member in page.board %}
        <div class="column is-one-quarter">
            <div class="card">
                <div class="card-image level-item">
                    <figure class="image is-fullwidth">
                    <img class="is-rounded" src="{{ site.baseurl }}/assets/img/people/{{ member.pic }}.png" alt="Placeholder image">
                    </figure>
                </div>
                <div class="card-content">
                    <div class="media">
                        <div class="media-content">
                            <p class="title is-4">{{ member.name }}</p>
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

<div class="columns is-multiline is-mobile">
    {% for member in page.team %}
        <div class="column is-one-quarter">
            <div class="card">
                <div class="card-image level-item">
                    <figure class="image is-fullwidth">
                    <img class="is-rounded" src="{{ site.baseurl }}/assets/img/people/{{ member.pic }}.png" alt="Placeholder image">
                    </figure>
                </div>
                <div class="card-content">
                    <div class="media">
                        <div class="media-content">
                            <p class="title is-4">{{ member.name }}</p>
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


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

The Lanka Data Foundation (LDF) is a citizen driven, not-for-profit, nonpartisan and non-governmental organisation, established in December 2019. LDF leverages ICT know-how to collect, curate and disseminate verified data and information to the public, with the support of research and civil society organisations.

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

# About Our Data

---

<div class="columns is-multiline is-mobile">
    <div class="column is-one-quarter p-0">
         <div class="flip-card">
            <div class="flip-card-inner">
                <div class="flip-card-front has-background-primary-dark has-text-white is-uppercase has-text-weight-semibold ">
                    <p class="has-text-centered is-size-3">Eliminates information asymmetry</p>
                </div>
                <div class="flip-card-back has-background-link-light has-text-primary-dark ">
                    <p>We recognize that the high cost, and difficulty in accessing data are the main barriers to transparency and accountability. Through our online archive of publicly accessible government data, we aim to help the private sector, the broader public, and civil society, access the data they need most, to bridge information asymmetry. </p>
                </div>
            </div>
        </div> 
    </div>
    <div class="column is-one-quarter p-0">
         <div class="flip-card">
            <div class="flip-card-inner">
                <div class="flip-card-front has-background-primary-light has-text-black is-uppercase has-text-weight-semibold ">
                    <p class="has-text-centered is-size-3"> Facilitates individual and organizational needs </p>
                </div>
                <div class="flip-card-back has-background-primary-dark has-text-white ">
                    <p> Whether you’re using data for research, journalism or business, our data and analysis will be available to you in easily accessible, digitized formats, to help you derive insights quickly. </p>
                </div>
            </div>
        </div> 
    </div>
    <div class="column is-one-quarter p-0">
         <div class="flip-card">
            <div class="flip-card-inner">
                <div class="flip-card-front has-background-primary-dark has-text-white is-uppercase has-text-weight-semibold ">
                    <p class="has-text-centered is-size-3"> Supports data integrity, transparency and accountability </p>
                </div>
                <div class="flip-card-back has-background-link-light has-text-primary-dark ">
                    <p> The credibility and integrity of your work depends on the quality of the data you use and whether or not you can trust and reproduce the results. Through data provenance, we help you trace the origin of your data back to verified sources, ensuring data integrity, transparency and accountability. </p>
                </div>
            </div>
        </div> 
    </div>
    <div class="column is-one-quarter p-0">
         <div class="flip-card">
            <div class="flip-card-inner">
                <div class="flip-card-front has-background-primary-light has-text-black is-uppercase has-text-weight-semibold ">
                    <p class="has-text-centered is-size-3"> Accessed through open source software tools and services </p>
                </div>
                <div class="flip-card-back has-background-primary-dark has-text-white ">
                    <p> As an institutional user you will have access to modern open source software tools and services that will help you access verified data and information, and will help streamline and support data-driven decision making. </p>
                </div>
            </div>
        </div> 
    </div>
</div>

---

<div class="columns is-multiline is-mobile">
    <div class="column is-one-third pl-0 pr-0">
        <div class="card has-background-primary-dark has-text-white" style="height:100%">
            <div class="card-content">
                <div class="content is-size-3 about-card-content">
                    <p> Eliminates information asymmetry </p>
                </div>
            </div>
        </div>
    </div>
    <div class="column is-two-thirds pl-0 pr-0">
        <div class="card has-background-primary-light has-text-black" style="height:100%">
            <div class="card-content">
                <div class="content about-card-content">
                    <p> We recognize that the high cost, and difficulty in accessing data are the main barriers to transparency and accountability. Through our online archive of publicly accessible government data, we aim to help the private sector, the broader public, and civil society, access the data they need most, to bridge information asymmetry. </p>
                </div>
            </div>
        </div>
    </div>
    <div class="column is-two-thirds pl-0 pr-0">
        <div class="card has-background-primary-light has-text-black" style="height:100%">
            <div class="card-content">
                <div class="content about-card-content">
                    <p> As an institutional user you will have access to modern open source software tools and services that will help you access verified data and information, and will help streamline and support data-driven decision making. </p>
                </div>
            </div>
        </div>
    </div>
    <div class="column is-one-third pl-0 pr-0">
        <div class="card has-background-primary-dark has-text-white" style="height:100%">
            <div class="card-content">
                <div class="content is-size-3 about-card-content">
                    <p> Facilitates individual and organizational needs </p>
                </div>
            </div>
        </div>
    </div>
    <div class="column is-one-third pl-0 pr-0">
        <div class="card has-background-primary-dark has-text-white" style="height:100%">
            <div class="card-content">
                <div class="content is-size-3 about-card-content">
                <p> Supports data integrity, transparency and accountability </p>
                </div>
            </div>
        </div>
    </div>
    <div class="column is-two-thirds pl-0 pr-0">
        <div class="card has-background-primary-light has-text-black" style="height:100%">
            <div class="card-content">
                <div class="content about-card-content">
                    <p> The credibility and integrity of your work depends on the quality of the data you use and whether or not you can trust and reproduce the results. Through data provenance, we help you trace the origin of your data back to verified sources, ensuring data integrity, transparency and accountability. </p>
                </div>
            </div>
        </div>
    </div>
    <div class="column is-two-thirds pl-0 pr-0">
        <div class="card has-background-primary-light has-text-black" style="height:100%">
            <div class="card-content">
                <div class="content about-card-content">
                    <p> As an institutional user you will have access to modern open source software tools and services that will help you access verified data and information, and will help streamline and support data-driven decision making.  </p>
                </div>
            </div>
        </div>
    </div>
    <div class="column is-one-third pl-0 pr-0">
        <div class="card has-background-primary-dark has-text-white" style="height:100%">
            <div class="card-content">
                <div class="content is-size-3 about-card-content">
                    <p> Accessed through open source software tools and services </p>
                </div>
            </div>
        </div>
    </div>
</div>

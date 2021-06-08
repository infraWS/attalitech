---
layout: base
title: "infra.ws | The DevOps Powerhouse"
css:
  - /assets/css/index.css
ext-css:
  - //fonts.googleapis.com/css?family=Roboto:400,700
js:
  - /assets/js/index.js
---

<div id="header" markdown="1">

<div id="header-inner" markdown="1">

# You build the software. {#title}

## We take care of your cloud infrastructure. {#subtitle}

#### The DevOps powerhouse at the immediate service of your team. {#sub-subtitle}

<a href="/#who-we-are" class="actionbtn">
  <span class="fas fa-angle-double-down" aria-hidden="true"></span>
</a>

</div>
<!-- <div id="particles-js"></div> -->
</div>

<div id="main-sections">

<div id="who-we-are"></div>
<div id="aboutus-out" class="page-section grey-section">
  <div id="aboutus">
    <div class="section-title">WHO WE ARE</div>
    <div class="section-text">
      <p>We are a DevOps powerhouse of elite cloud architects, DevOps/SRE engineers, software engineers, and ex-CTOs. We've addressed countless times the challenges around cloud infrastructure, DevOps, SRE, FinOps, PaaS and SaaS architecture across the Software Development Lifecycle while building several SaaS products for our own and other companies. Each of us is top of our field and as a team, we bring an impact to your engineering organization beyond your current capacity. We focus on more than just delivering ordinary solutions. We do this craft because it is our passion.</p>
      <div id="about-statement">We are here to change your game. </div>
    </div>
  </div>
</div>

<div id="what-we-do"> </div>
<div id="services-out" class="page-section cut1">
  <div id="services">
    <div class="section-title">WHAT WE DO</div>
    <div class="section-text">
      <p>We provide top quality DevOps & SaaS engineering services trusted by over 20 organizations worldwide. Our customers enjoy peace of mind knowing they trust <strong>infra.ws</strong> with their DevOps needs. We care about making your infrastructure equally good with your products and doing things right.</p>
      <p>We work as a member of your in-house team together with your engineers to address your challenges across the Software Development Lifecycle. We usually focus on all your DevOps needs, while adhering to the highest standards and implementing the best practices. We solve any problem as if it was our own, never compromising quality and security. We are here to help you align your infrastructure with your products needs.</p>
    </div>
    <div id="portfolio">
      <div id="shinyapps-big">
        {% for item in site.data.services_overview %}
        <div class="shinyapp">
            {% if item.img %}<img class="appimg" src="/assets/img/screenshots/{{ app.img }}" />{% endif item.img %}
            <div class="apptitle">{{ item.title }}</div>
            {% if item.description %}<<div class="appdesc">{{ item.description }}</div>{% endif item.description %}
            <div>
              <ul>
              {% for service in item.services %}
                <li>{{ service.title }}</li>
              {% endfor %}
              </ul>
            </div>
          </div>
      {% endfor %}
      </div>
   <div class="section-text">
   </div>
  </div>
</div>
</div>
<div id="talk-to-us"></div>
<div id="contact-out" class="page-section">
  <div id="contact">
    <div class="section-title">TALK TO US</div>
    <div class="section-text">
        We're here to help you with your DevOps & SaaS engineering challenges right away. Send us a brief message and <b>we will get back to you within 24 hours</b>.      
    </div>
    <div style="text-align: center; padding-top: 20px;">    
      <a href="mailto:hello@infra.ws?subject=Hello" class="actionbtn">
        <span class="far fa-envelope" aria-hidden="true"></span>
        hello@infra.ws
      </a>
    </div>
  </div>
</div>

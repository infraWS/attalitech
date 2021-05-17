---
layout: base
title: "infraWS | The DevOps Powerhouse"
css:
  - /assets/css/index.css
ext-css:
  - //fonts.googleapis.com/css?family=Roboto:400,700
js:
  # - /assets/js/index.js
ext-js:
  # - //cdn.jsdelivr.net/npm/particles.js@2.0.0/particles.min.js
  # - //cdn.jsdelivr.net/npm/@srexi/purecounter.js/dist/purecounter_vanilla.js
---

<div id="header" class="cut1" markdown="1">

<div id="header-inner" markdown="1">

# You build the software. {#title}

## We take care of your cloud infrastructure. {#subtitle}

#### A DevOps powerhouse at your immediate service. {#sub-subtitle}

<a href="/#contact" class="actionbtn">
  TALK TO US
</a>
{: .actionbtn-out :}

</div>

<!-- <div id="particles-js"></div> -->

</div>

<div id="main-sections">

<div class="cut-buffer aboutus-buffer"></div>

<div id="aboutus-out" class="page-section grey-section cut2">
  <div id="aboutus">
    <div class="section-title">WHO WE ARE</div>
    <div id="aboutus-text">
      <p>We are a DevOps powerhouse of elite cloud architects, DevOps/SRE engineers, software engineers, and ex-CTOs. We've addressed countless times challeges around cloud infrastructure, DevOps, SRE, and SaaS architecture across the Software Development Lifecycle, while building several software as a service products for our own and other companies. Each of us is top of our field and as a team we bring an impact to your engineering organization beyond the ordinary. </p>
      <p>At infraWS, we care about making your infrastructure equally good with your products and doing things right. We work as a member of your in-house team together with your engineers to address your challenges across the Software Development Lifecycle. We usually focus on all your DevOps needs, while adhering to the highest standards and implementing the best practices. We solve any problem as if it was our own, never compromising quality and security. </p>
      <p>We provide top quality DevOps services trusted by over 20 organizations worldwide. Our customers enjoy peace of mind knowing they trust infraWS with their DevOps needs. We focus on more than just delivering solutions. We do this craft because it is our passion. We are here to change your game.</p>
      <br/><br/><b>We are certain of it.</b>
    </div>
  </div>
</div>



<div id="services-out" class="page-section cut1">
  <div id="services">
    <div class="section-title">HOW WE HELP</div>
    <div id="services-list">
      <div class="service">
        <img class="service-img" alt="Service image" src="/assets/img/scale-flexiple/Bug tracking.png" />
        <div class="service-text">Continuous delivery and integration should no longer be a problem for you. We can help you automate and create pipelines to release your new content fast while you keep quality at high standards.
      </div>
      </div>
      <div class="service">
          <img class="service-img" alt="Service image" src="/assets/img/scale-flexiple/Work risk-free.png" />
          <div class="service-text">Infrastructure needs can get big quite fast. Clutter and inconsistencies is not something you want in your service environments. There is no better way to manage infrastructure when everything is controlled by code.</div>
        </div>
      </div>
    <div id="services-break"></div>
    <div class="service">
        <img class="service-img" alt="Service image" src="/assets/img/scale-flexiple/Complex dashboard.png" />
        <div class="service-text">Plan ahead to scale when it is needed and at will. Based on analytics you can automate your whole scaling strategy or scale at will at any given point!</div>
      </div>
      <div class="service">
        <img class="service-img" alt="Service image" src="/assets/img/scale-flexiple/Successful completion of project.png" />
        <div class="service-text">Expert advice on big scale systems. Great products require great availability and delivery. Do not compromise your product's true value.</div>
      </div>
  </div>
</div>
<div class="cut-buffer values-buffer"></div>
<div id="values-out" class="page-section cut2">
  <div id="portfolio">
    <div id="shinyapps-big">
      {% for item in site.data.services_overview %}
	    <div class="shinyapp">
          {% if item.img %}<img class="appimg" src="/assets/img/screenshots/{{ app.img }}" />{% endif item.img %}
          <div class="apptitle">{{ item.title }}</div>
          {% if item.description %}<<div class="appdesc">{{ item.description }}</div>{% endif item.description %}
        </div>
	  {% endfor %}
    </div>
  </div>
</div>

<div class="cut-buffer"></div>

<div id="grow-section-out" class="page-section grey-section cut2">
  <div id="grow-section">
    <div class="section-title">Grow your infrastructure alongside your products</div>
    <p class="grow-text">Your products and services are bound together. Availability is a key aspect. We are here to help you align your infrastructure needs with your products </p>
	<div id="grow-list" markdown="1">
{% for info in site.data.main_info %}
{% if info.icon %}<span class="grow-icon fa-fw {{ info.icon }}" aria-hidden="true"></span>{% endif info.icon %}
<span class="grow-content">{{ info.content }}</span>
{: .grow-text }
{% endfor %}
</div>
<p class="grow-text">Essentially, we can help you be there the way you want to, in order to serve your customers online.</p>
  </div>
</div>


<!-- 
<div class="cut-buffer values-buffer"></div>

<div id="values-out" class="page-section cut2">
  <div id="values">
	  <div class="section-title">Our Values</div>
    <div id="values-text">
      At infraWS, we care about making your infrastructure equally good with your products and doing things <b>right</b>.<br/><br/>We address any problem as if it was our own, <b>never </b>compromising quality and security. We focus on more than just delivering solutions. We are always looking for ways to add more <b>value</b> to our clients. Our clients enjoy peace of mind knowing they can trust us with their DevOps needs.
    </div>
  </div>
</div> -->

<div id="contact-out" class="page-section cut1">
  <div id="contact">
    <div class="section-title">TALK TO US</div>
        <div class="container">
          <div>
            We're here to chat about your cloud infrastructure challenges and how we can help you. Send us a brief message and we will get back to you within 24h, or schedule a brief introductory meeting to discuss your challenges.   
          </div>
          <div style="text-align: center;">    
            <a href="mailto:hello@infra.ws?subject=DevOps inquiry" class="schedule-btn actionbtn">
              <span class="far fa-envelope" aria-hidden="true"></span>
              hello@infra.ws
            </a>
             <a href="https://calendly.com/nmargaritis/30min" class="schedule-btn actionbtn">
              <span class="far fa-calendar-check" aria-hidden="true"></span>
              Meet with us
            </a>
          </div>
        </div>


  </div>
</div>

</div>

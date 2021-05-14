---
layout: base
title: "infra.ws | The DevOps Powerhouse"
css:
  - /assets/css/index.css
ext-css:
  - //fonts.googleapis.com/css?family=Roboto:400,700
js:
  - /assets/js/index.js
ext-js:
  - //cdn.jsdelivr.net/npm/particles.js@2.0.0/particles.min.js
  - //cdn.jsdelivr.net/npm/@srexi/purecounter.js/dist/purecounter_vanilla.js
---

<div id="header" class="cut1" markdown="1">

<div id="header-inner" markdown="1">

# infra.ws {#title}

## Your cloud gateway {#subtitle}

##### We are a team of talented devops engineers that can help you forget about scaling, infrastructure, continuous delivery & integration and focus on your products {#sub-subtitle}

<a href="/contact" class="actionbtn">
  <span class="far fa-envelope" aria-hidden="true"></span>
  Contact us
</a>
{: .actionbtn-out :}

</div>

<div id="particles-js"></div>

</div>

<div id="main-sections">

<div id="services-out" class="page-section cut1">
  <div id="services">
    <div class="section-title">What We Offer</div>
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

<div id="portfolio-out" class="page-section grey-section">
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

<div class="cut-buffer aboutus-buffer"></div>

<div id="aboutus-out" class="page-section grey-section cut2">
  <div id="aboutus">
    <div class="section-title">About Us</div>
    <div id="aboutus-text">
      Infra.ws was launched in 2017 as DevOps house. The goal was simple: address any and all of your DevOps needs, while adhering to the <b>highest standards</b>. Today, Infra.ws is a <b>DevOps powerhouse</b>, that incorporates 15 high caliber DevOps architects and domain experts. Infra.ws provides top quality DevOps services and is trusted by over 20 companies worldwide. We are here to change your game.<br/><br/><b>We are certain of it.</b>
    </div>
  </div>
</div>

<div class="cut-buffer values-buffer"></div>

<div id="values-out" class="page-section cut2">
  <div id="values">
	  <div class="section-title">Our Values</div>
    <div id="values-text">
      At infra.ws, we care about making your infrastructure equally good with your products and doing things <b>right</b>.<br/><br/>We address any problem as if it was our own, <b>never </b>compromising quality and security. We focus on more than just delivering solutions. We are always looking for ways to add more <b>value</b> to our clients. Our clients enjoy peace of mind knowing they can trust us with their DevOps needs.
    </div>
  </div>
</div>

<div id="clients-out" class="page-section cut1">
  <div id="clients">
    <div class="section-title">Clients</div>
     <section id="counts" class="counts">
        <div class="container">
          <div class="row counters">
            <div class="col-lg-3 col-6 text-center">
              <span data-purecounter-start="0" data-purecounter-end="23" data-purecounter-duration="1" class="purecounter"></span>
              <p>Unique Clients</p>
            </div>
            <div class="col-lg-3 col-6 text-center">
              <span data-purecounter-start="0" data-purecounter-end="533" data-purecounter-duration="1" class="purecounter"></span>
              <p>Cloud Migrated Services</p>
            </div>
            <div class="col-lg-3 col-6 text-center">
              <span data-purecounter-start="0" data-purecounter-end="98" data-purecounter-duration="1" class="purecounter"></span>
              <p>Pipeline Automations</p>
            </div>
            <div class="col-lg-3 col-6 text-center">
              <span data-purecounter-start="0" data-purecounter-end="15" data-purecounter-duration="1" class="purecounter"></span>
              <p>Hard Workers</p>
            </div>
          </div>
        </div>
    </section>
    <div id="clients-subtitle">Clients range from startups to betting industry platforms to Fortune 1000 companies</div>
    <div id="client-logos">
      {% for client in site.data.clients %}
        <a class="client-img" href="{{ client.url }}" title="{{ client.name }}">
          <img alt="{{ client.name }}" src="/assets/img/logos/{{ client.img }}" />
        </a>
      {% endfor %}
    </div>
  </div>
  
</div>

<div id="cta-out" class="page-section">
  <div id="cta">
    <div class="section-title">Take Your Apps to the Highest Cloud</div><br/>
  </div>
  <a href="/contact" class="actionbtn">
    <span class="far fa-envelope" aria-hidden="true"></span>
    Contact Us
  </a>
</div>

</div>


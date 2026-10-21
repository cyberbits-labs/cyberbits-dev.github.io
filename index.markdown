---
layout: default
---

<section class="hero">
  <div class="wrap hero__grid">
    <div>
      <span class="eyebrow">{{ site.company }} &middot; Since 2018</span>
      <h1 class="display">Transform your IT infrastructure</h1>
      <p class="lead">Unlock the full potential of your business with expert IT consulting services.</p>
      <div class="actions">
        <a class="btn" href="#contact">Get started <span class="arrow">&rarr;</span></a>
        <a class="btn btn--ghost" href="#services">Services</a>
      </div>
    </div>
    <div class="hero__media">
      <img src="/assets/banner-index.jpg" alt="" width="1080" height="718">
    </div>
  </div>
</section>

<section class="section section--ivory">
  <div class="wrap statement">
    <div>
      <span class="eyebrow">What we do</span>
    </div>
    <div class="statement__body">
      <p>
        We provide hosting services and tailored website development for individuals, <abbr title="Small and medium-sized enterprises">SMEs</abbr> and <a href="https://en.wikipedia.org/wiki/Free_software">Free&nbsp;Software</a> projects.
      </p>
      <p>
        We specialize in decentralized hosting worldwide, mirroring services, DevOps and Linux system administration.
      </p>
      <p>
        We also provide custom software development and consulting in cloud infrastructure, scaling, data analysis, etc.
      </p>
    </div>
  </div>
</section>

<section class="section" id="services">
  <div class="wrap">
    <div class="section-head">
      <div>
        <h2 class="title">Services</h2>
      </div>
    </div>

    <div class="services">
      {% include service-card.html index="01" id="hosting" link="/hosting" description="We provide a hosting service on our battle-tested infrastructure serving terabytes of data every day." %}

      {% include service-card.html index="02" id="consulting" link="/consulting" description="We provide consulting in cloud infrastructure, scaling, data analysis and custom software development." %}
    </div>
  </div>
</section>

<section class="section section--ivory">
  <div class="wrap split">
    <div class="split__media">
      <img src="/assets/about-us.jpg" alt="" width="1080" height="769" loading="lazy">
    </div>

    <div>
      <h2 class="title">About us</h2>

      <p>
        We are an established IT consulting firm with a remote team of highly skilled professionals.
        We provide comprehensive IT solutions to individuals and small businesses.
        We love to help open-source software and privacy-respecting projects.
      </p>

      <p class="muted">
        Our expertise lies in delivering tailored IT strategies and technology infrastructure to help our clients stay ahead in today's rapidly evolving digital landscape.
        We are committed to providing exceptional service, innovative solutions, and measurable results to drive our clients' success.
      </p>
    </div>
  </div>
</section>

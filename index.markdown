---
layout: default
---

<section class="hero">
  <div class="wrap hero__grid">
    <div>
      <span class="eyebrow">Independent technology consultancy &middot; Since 2018</span>
      <h1 class="display">Your technology, in trusted hands</h1>
      <p class="lead">
        Cyberbits is a boutique consultancy for discerning individuals and growing businesses.
        You work directly with a senior engineer who knows your systems, answers your messages and takes responsibility. No call centres, no ticket queues.
      </p>
      <div class="actions">
        <a class="btn" href="#contact">Start a conversation <span class="arrow">&rarr;</span></a>
        <a class="btn btn--ghost" href="#services">Our services</a>
      </div>
    </div>
    <div class="hero__media">
      <img src="/assets/banner-index.jpg" alt="" width="1080" height="718">
    </div>
  </div>
</section>

<section class="section section--ivory">
  <div class="wrap">
    <div class="section-head">
      <div>
        <span class="eyebrow">Why Cyberbits</span>
        <h2 class="title">Expertise you can reach, discretion you can rely on</h2>
      </div>
    </div>

    <div class="pillars">
      <div class="pillar">
        <h3>A senior expert, directly</h3>
        <p>One point of contact who knows your setup inside out. You never have to explain your problem twice, and you always know who is looking after you.</p>
      </div>
      <div class="pillar">
        <h3>Discretion by default</h3>
        <p>Privacy is not an add-on. Your data stays in Europe on infrastructure we operate ourselves, and every engagement is handled in strict confidence.</p>
      </div>
      <div class="pillar">
        <h3>Built to last</h3>
        <p>Proven, open technologies, properly documented. Clear advice in plain language, and no lock-in: you stay in control of what you own.</p>
      </div>
    </div>
  </div>
</section>

<section class="section" id="services">
  <div class="wrap">
    <div class="section-head">
      <div>
        <span class="eyebrow">Services</span>
        <h2 class="title">How we can help</h2>
      </div>
      <p class="lead">From a one-off second opinion to looking after your infrastructure for the long term.</p>
    </div>

    <div class="services">
      {% include service-card.html id="consulting" link="/consulting" description="Independent advice and hands-on engineering: security and privacy for private clients, cloud infrastructure, scaling and custom software for businesses." %}

      {% include service-card.html id="hosting" link="/hosting" description="Fast, private European hosting on our own battle-tested infrastructure, which serves terabytes of data every day, with an engineer you can actually reach." %}
    </div>
  </div>
</section>

<section class="section section--ivory">
  <div class="wrap">
    <div class="section-head">
      <div>
        <span class="eyebrow">Clients</span>
        <h2 class="title">Trusted for years</h2>
      </div>
      <p class="lead">Our relationships are long-term by design. Some of the organisations and projects we have supported for years:</p>
    </div>

    <div class="clients">
      {% include client-card.html domain="smartbox.com" description="Europe's leading experience-gift company, connecting people with more than 140,000 experiences across Europe." tags="enterprise,infrastructure,long-term" %}

      {% include client-card.html domain="dcr.farm" description="A Decred Voting Service Provider, where reliability, security and uptime are non-negotiable." tags="blockchain,security,high-availability" %}

      {% include client-card.html domain="cyberbits.eu" description="Our own public infrastructure in Europe and Asia: package mirrors, an NTP server, an OpenPGP keyserver and a Tor relay, relied on by the open-source community." tags="in-house,open-source,europe-asia" %}
    </div>
  </div>
</section>

<section class="section">
  <div class="wrap split">
    <div class="split__media">
      <img src="/assets/about-us.jpg" alt="" width="1080" height="769" loading="lazy">
    </div>

    <div>
      <span class="eyebrow">About us</span>
      <h2 class="title">Deliberately small. Seriously experienced.</h2>

      <p>
        Cyberbits Labs was founded in 2018 on a simple idea: the people who depend on technology most deserve an expert who knows them, not an anonymous support desk.
      </p>

      <p class="muted">
        We have spent years designing and running infrastructure for businesses, decentralized services and Free&nbsp;Software projects, from points of presence in France and Thailand.
        Our public mirrors, keyserver and Tor relay are used every day by the open-source community: the same infrastructure, and the same care, that our clients get.
        We bring the same rigour to every client, whether that means protecting a family's privacy or preparing a company to scale.
        We take on a limited number of clients so that each one gets our full attention.
      </p>
    </div>
  </div>
</section>

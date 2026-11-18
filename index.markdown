---
layout: default
---

<section class="hero">
  <div class="wrap hero__grid">
    <div>
      <span class="eyebrow">Independent technology consultancy &middot; Since 2018</span>
      <h1 class="display">Your technology, in trusted hands</h1>
      <p class="lead">
        {{ site.title }} helps growing businesses build and run reliable systems, and private clients secure their technology.
        You work directly with a senior engineer on cloud infrastructure, custom software or a security and privacy review. No call centres, no ticket queues.
      </p>
      <div class="actions">
        <a class="btn" href="#contact">Start a conversation <span class="arrow">&rarr;</span></a>
        <a class="btn btn--ghost" href="#services">Our services</a>
      </div>
    </div>
    <div class="hero__media">
      <picture>
        <!-- Hidden on phones; a blank placeholder stops the photo downloading there -->
        <source media="(max-width: 560px)" srcset="data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7">
        <img src="/assets/banner-index.jpg" alt="" width="1080" height="718">
      </picture>
    </div>
  </div>
</section>

<section class="section section--ivory">
  <div class="wrap">
    <div class="section-head">
      <div>
        <span class="eyebrow">Why {{ site.title }}</span>
        <h2 class="title">Expertise you can reach, discretion you can rely on</h2>
      </div>
    </div>

    <div class="pillars">
      <div class="pillar">
        <h3>A senior expert, directly</h3>
        <p>One point of contact who knows your setup inside out. You work with the engineer who does the work, so you never have to explain your problem twice.</p>
      </div>
      <div class="pillar">
        <h3>Discretion by default</h3>
        <p>Privacy is not an add-on. Every engagement is handled in strict confidence, from your first message onwards.</p>
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
      {% include service-card.html id="private clients" link="/consulting" description="Security and privacy reviews, personal infrastructure and a trusted second opinion, for entrepreneurs, families and family offices." %}

      {% include service-card.html id="businesses" link="/consulting" description="Cloud infrastructure, scaling, DevOps and custom software, for SMEs that need senior engineering without hiring a full-time team." %}
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
      <p class="lead">Some of the organisations and projects we have supported over the years:</p>
    </div>

    <div class="clients">
      {% include client-card.html domain="smartbox.com" description="Europe's leading experience-gift company, connecting people with more than 140,000 experiences across Europe." tags="enterprise,infrastructure,long-term" %}

      {% include client-card.html domain="dcr.farm" description="A Decred Voting Service Provider, where reliability, security and uptime are non-negotiable." tags="blockchain,security,high-availability" %}

      {% include client-card.html domain="cool.cash" description="AI-powered wealth management software tracking every major asset class, from stock indices, equities and forex to gold, real estate, Bitcoin and Brent crude. Currently in private alpha." tags="fintech,ai,wealth-management" %}

    </div>
  </div>
</section>

<section class="section" id="infrastructure">
  <div class="wrap split">
    <div>
      <span class="eyebrow">Infrastructure we operate</span>
      <h2 class="title">Proof you can inspect</h2>

      <p class="lead">Alongside our client work, we run public infrastructure for the open-source community in Europe and Asia.</p>

      <p class="muted">
        It puts our infrastructure experience into daily practice, and it is all public:
        <a href="https://cyberbits.eu/" target="_blank" rel="noopener">explore what we run</a> or
        <a href="https://status.{{ site.domain }}/" target="_blank" rel="noopener">check the live service status</a>.
        Command-line users can also host with us there: see <a href="https://cyberbits.eu/#hosting" target="_blank" rel="noopener">static hosting on cyberbits.eu</a>.
      </p>

      <div class="actions">
        <a class="btn" href="#contact">Start a conversation <span class="arrow">&rarr;</span></a>
      </div>
    </div>

    <div class="split__media">
      <img src="/assets/infrastructure.jpg" alt="" width="1080" height="864" loading="lazy">
    </div>
  </div>
</section>

<section class="section section--ivory">
  <div class="wrap split">
    <div class="split__media">
      <img src="/assets/about-us.jpg" alt="" width="1080" height="769" loading="lazy">
    </div>

    <div>
      <span class="eyebrow">About us</span>
      <h2 class="title">Deliberately small. Seriously experienced.</h2>

      <p>
        {{ site.title }} was founded in 2018 on a simple idea: the people who depend on technology most deserve an expert who knows them, not an anonymous support desk.
      </p>

      <p class="muted">
        We have spent years designing and running infrastructure for businesses, decentralized services and Free&nbsp;Software projects, from points of presence in France and Thailand.
        We bring the same rigour to every client, whether that means protecting a family's privacy or preparing a company to scale.
        We take on a limited number of clients so that each one gets our full attention.
      </p>
    </div>
  </div>
</section>

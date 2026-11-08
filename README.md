<div id="stride-home">
  <style>
    #stride-home {
      --blue:#07599c;
      --gold:#f6b326;
      --cream:#f8f5ed;
      --navy:#16324a;
      --sky:#ddecf6;
      font-family:Arial,sans-serif;
      color:var(--navy);
      background:var(--cream);
      line-height:1.6;
    }
    #stride-home * {box-sizing:border-box}
    #stride-home a {text-decoration:none}
    #stride-home .wrap {
      max-width:1150px;
      margin:auto;
      padding:0 26px;
    }
    #stride-home .nav {
      display:flex;
      justify-content:space-between;
      align-items:center;
      gap:20px;
      padding:20px 0;
      flex-wrap:wrap;
    }
    #stride-home .brand {
      font-size:23px;
      font-weight:900;
      color:var(--blue);
      letter-spacing:-1px;
    }
    #stride-home .brand span {color:#c48408}
    #stride-home .links {
      display:flex;
      gap:19px;
      flex-wrap:wrap;
    }
    #stride-home .links a {
      color:var(--navy);
      font-size:14px;
      font-weight:700;
    }
    #stride-home .hero {
      padding:85px 0 100px;
      background:linear-gradient(130deg,#f8f5ed,#e5f1f8);
      position:relative;
      overflow:hidden;
    }
    #stride-home .eyebrow {
      font-size:12px;
      font-weight:800;
      letter-spacing:2px;
      color:var(--blue);
      text-transform:uppercase;
    }
    #stride-home h1 {
      font-size:clamp(43px,7vw,85px);
      line-height:1.07;
      letter-spacing:-3px;
      margin:18px 0 24px;
      max-width:850px;
    }
    #stride-home h1 em {
      color:var(--blue);
      font-style:normal;
    }
    #stride-home .intro {
      max-width:650px;
      font-size:19px;
      margin-bottom:30px;
    }
    #stride-home .btn {
      display:inline-block;
      padding:14px 24px;
      border-radius:7px;
      font-size:15px;
      font-weight:800;
      margin:5px 8px 5px 0;
      transition:transform .2s;
    }
    #stride-home .btn:hover {transform:translateY(-2px)}
    #stride-home .primary {
      background:var(--blue);
      color:white;
    }
    #stride-home .secondary {
      border:2px solid var(--blue);
      color:var(--blue);
    }
    #stride-home section {padding:75px 0}
    #stride-home .section-label {
      color:var(--blue);
      font-weight:800;
      font-size:12px;
      letter-spacing:2px;
      text-transform:uppercase;
    }
    #stride-home h2 {
      font-size:clamp(30px,4vw,47px);
      letter-spacing:-1.5px;
      line-height:1.15;
      margin:12px 0 22px;
    }
    #stride-home .lead {
      max-width:730px;
      font-size:18px;
    }
    #stride-home .cards {
      display:grid;
      grid-template-columns:repeat(3,1fr);
      gap:20px;
      margin-top:36px;
    }
    #stride-home .card {
      background:white;
      padding:30px;
      border-radius:14px;
      border:1px solid #dce6ed;
      box-shadow:0 7px 20px #16324a0b;
    }
    #stride-home .number {
      color:var(--blue);
      font-weight:900;
      font-size:14px;
    }
    #stride-home h3 {
      font-size:23px;
      line-height:1.2;
      margin:16px 0;
    }
    #stride-home .blue-section {
      background:var(--blue);
      color:white;
    }
    #stride-home .blue-section .section-label {
      color:var(--gold);
    }
    #stride-home .steps {
      display:grid;
      grid-template-columns:repeat(3,1fr);
      gap:28px;
      margin-top:35px;
    }
    #stride-home .step {
      border-top:3px solid var(--gold);
      padding-top:20px;
    }
    #stride-home .step strong {
      color:var(--gold);
      font-size:15px;
    }
    #stride-home .step h3 {color:white}
    #stride-home .pillars {
      display:grid;
      grid-template-columns:repeat(3,1fr);
      gap:14px;
      margin-top:30px;
    }
    #stride-home .pillar {
      background:var(--sky);
      border-radius:10px;
      padding:22px;
      font-weight:700;
    }
    #stride-home .event {
      background:white;
      border-left:6px solid var(--gold);
      border-radius:10px;
      padding:30px;
      margin-top:25px;
    }
    #stride-home .community {
      background:#eaf2f7;
    }
    #stride-home .photo {
      background:white;
      border:2px dashed #adc6d8;
      border-radius:12px;
      min-height:210px;
      display:flex;
      align-items:center;
      justify-content:center;
      padding:25px;
      text-align:center;
      color:#506b80;
    }
    #stride-home details {
      background:white;
      margin:12px 0;
      padding:20px;
      border-radius:9px;
      border:1px solid #dce6ed;
    }
    #stride-home summary {
      font-weight:800;
      cursor:pointer;
    }
    #stride-home details p {margin-bottom:0}
    #stride-home .contact {
      background:var(--navy);
      color:white;
      text-align:center;
    }
    #stride-home .contact .section-label {
      color:var(--gold);
    }
    #stride-home .contact a {color:white}
    #stride-home footer {
      background:#102638;
      color:#d8e5ee;
      padding:23px;
      text-align:center;
      font-size:13px;
    }
    #stride-home a:focus-visible,
    #stride-home summary:focus-visible {
      outline:3px solid var(--gold);
      outline-offset:4px;
    }
    @media(max-width:750px) {
      #stride-home .cards,
      #stride-home .steps,
      #stride-home .pillars {
        grid-template-columns:1fr;
      }
      #stride-home .hero {padding:60px 0}
      #stride-home section {padding:55px 0}
      #stride-home h1 {letter-spacing:-1.5px}
    }
  </style>

  <div class="wrap">
    <nav class="nav" aria-label="STRIDE navigation">
      <a class="brand" href="#stride-top">STRIDE <span>AT UCLA</span></a>
      <div class="links">
        <a href="#stride-about">About</a>
        <a href="#stride-involved">Get Involved</a>
        <a href="#stride-pathway">VA Pathway</a>
        <a href="#stride-events">Events</a>
        <a href="#stride-faq">FAQ</a>
      </div>
    </nav>
  </div>

  <div class="hero" id="stride-top">
    <div class="wrap">
      <div class="eyebrow">Student-led • Veteran-centered • Community-driven</div>
      <h1>Move with purpose.<br><em>Serve with heart.</em></h1>
      <p class="intro">
        We're building a UCLA student community around Veteran service,
        learning, outreach, and connection. Together, we're working
        toward supporting the VA STRIDE program in West Los Angeles.
      </p>
      <a class="btn primary" href="mailto:uclaSTRIDE@gmail.com?subject=STRIDE%20Membership%20Interest">Express Interest ↗</a>
      <a class="btn secondary" href="#stride-about">Discover Our Mission</a>
    </div>
  </div>

  <section id="stride-about">
    <div class="wrap">
      <div class="section-label">01 / Who We Are</div>
      <h2>More than a club.<br>A community with a purpose.</h2>
      <p class="lead">
        STRIDE at UCLA is a student organization being developed to
        support the VA's Assisted Early Mobility for Hospitalized
        Veterans program. Our goal is to build a reliable student
        community that contributes through campus engagement,
        outreach, learning, and an appropriately authorized
        volunteer pathway.
      </p>
      <p class="lead">
        We believe meaningful service starts with showing up,
        building trust, and staying committed to the people
        and communities we hope to support.
      </p>
    </div>
  </section>

  <section id="stride-involved" style="background:#eaf2f7">
    <div class="wrap">
      <div class="section-label">02 / Find Your Place</div>
      <h2>There is more than one way to make an impact.</h2>
      <p class="lead">
        Whether you're interested in healthcare, leadership,
        service, or simply meeting students who care,
        there's a place to contribute.
      </p>
      <div class="cards">
        <article class="card">
          <div class="number">01 / SERVICE</div>
          <h3>Explore the VA pathway</h3>
          <p>Learn about the proposed volunteer pipeline and the steps that may be required for approved VA opportunities.</p>
        </article>
        <article class="card">
          <div class="number">02 / COMMUNITY</div>
          <h3>Connect on campus</h3>
          <p>Take part in student gatherings, planning activities, outreach, and a supportive community.</p>
        </article>
        <article class="card">
          <div class="number">03 / GROWTH</div>
          <h3>Develop your skills</h3>
          <p>Build experience in communication, teamwork, education, organizing, and responsible leadership.</p>
        </article>
      </div>
    </div>
  </section>

  <section class="blue-section" id="stride-pathway">
    <div class="wrap">
      <div class="section-label">03 / Understanding the Process</div>
      <h2>How the VA volunteer pathway works.</h2>
      <p class="lead">
        Being a STRIDE member and receiving authorization for
        a VA volunteer role are separate processes.
      </p>
      <div class="steps">
        <div class="step">
          <strong>STEP 01</strong>
          <h3>Connect with STRIDE</h3>
          <p>Express interest, learn about the organization, and explore ways to contribute on campus.</p>
        </div>
        <div class="step">
          <strong>STEP 02</strong>
          <h3>Learn the requirements</h3>
          <p>Any available VA role follows the applicable eligibility, onboarding, training, and approval requirements.</p>
        </div>
        <div class="step">
          <strong>STEP 03</strong>
          <h3>Participate if approved</h3>
          <p>Patient-facing activity is possible only with VA authorization, appropriate supervision, and available placements.</p>
        </div>
      </div>
    </div>
  </section>

  <section>
    <div class="wrap">
      <div class="section-label">04 / What Drives Us</div>
      <h2>Six pillars. One shared purpose.</h2>
      <div class="pillars">
        <div class="pillar">Clinical Volunteer Pipeline</div>
        <div class="pillar">Long-Term Sustainability</div>
        <div class="pillar">Student Engagement</div>
        <div class="pillar">Community Outreach</div>
        <div class="pillar">Professional Development</div>
        <div class="pillar">Fundraising & Program Support</div>
      </div>
    </div>
  </section>

  <section id="stride-events" style="background:#eaf2f7">
    <div class="wrap">
      <div class="section-label">05 / What's Next</div>
      <h2>Good things start with showing up.</h2>
      <div class="event">
        <div class="section-label">Campus Events & Updates</div>
        <h3>Come get to know STRIDE.</h3>
        <p>
          We're building our student community. Confirmed information
          sessions, campus events, and involvement opportunities will
          be announced through our official communication channels.
        </p>
        <a class="btn primary" href="https://www.instagram.com/stride.ucla/" target="_blank" rel="noopener">Follow Updates ↗</a>
      </div>
    </div>
  </section>

  <section class="community">
    <div class="wrap">
      <div class="section-label">06 / Our Community</div>
      <h2>Real people. Real connections.</h2>
      <p class="lead">
        Our story is about the students who come together to serve,
        learn, and build something lasting.
      </p>
      <div class="cards">
        <div class="photo">Future approved campus team photo</div>
        <div class="photo">Future approved student event photo</div>
        <div class="photo">Future approved community recap photo</div>
      </div>
    </div>
  </section>

  <section id="stride-faq">
    <div class="wrap">
      <div class="section-label">07 / Common Questions</div>
      <h2>Questions? Start here.</h2>

      <details>
        <summary>Do I need a healthcare major to join?</summary>
        <p>No. Students with interests in service, outreach, communications, leadership, and healthcare can all contribute.</p>
      </details>

      <details>
        <summary>Does membership guarantee a VA volunteer position?</summary>
        <p>No. VA opportunities depend on institutional approval, training, supervision, eligibility, and available placements.</p>
      </details>

      <details>
        <summary>Can I participate while waiting for VA onboarding?</summary>
        <p>Yes. Campus engagement, planning, learning, and approved outreach can provide ways to participate independently of clinical placement.</p>
      </details>

      <details>
        <summary>Does STRIDE offer research or shadowing placements?</summary>
        <p>Research and shadowing are not established STRIDE membership offerings. Any future opportunities would need to be separately confirmed and authorized.</p>
      </details>

      <details>
        <summary>How can I learn more?</summary>
        <p>Contact the student organization using the email below and ask about the current membership process.</p>
      </details>
    </div>
  </section>

  <section class="contact" id="stride-contact">
    <div class="wrap">
      <div class="section-label">08 / Take the First Step</div>
      <h2>Ready to be part of something meaningful?</h2>
      <p>Get connected, ask questions, and learn how to participate.</p>
      <a class="btn primary" href="mailto:uclaSTRIDE@gmail.com?subject=STRIDE%20Membership%20Interest">Get in Touch ↗</a>
      <p>
        <a href="mailto:uclaSTRIDE@gmail.com">uclaSTRIDE@gmail.com</a>
      </p>
      <p>
        <a href="https://www.instagram.com/stride.ucla/" target="_blank" rel="noopener">Instagram: @stride.ucla</a>
      </p>
    </div>
  </section>

  <footer>
    STRIDE at UCLA • Student community in development<br>
    VA participation is subject to applicable institutional approval.
  </footer>
</div>

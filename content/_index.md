+++
title = "German Reproducibility Network"
description = "Working together for trustworthy and useful research"
template = "landing.html"
+++

{% landing_jumbotron() %}
  <h1 class="display-4 mt-3">
    German<br>
    <span class="highlight-light">Re&shy;pro&shy;ducibil&shy;i&shy;ty</span><br>
    Network
  </h1>
  <p class="lead mt-4 mb-0">
    To promote rigor, reliability, robustness, and <br class="d-none d-md-inline">
    transparency of scientific research in Germany.
  </p>
{% end %}

<!-- Mission -->
{% landing_section(title="Mission", id="mission") %}
  The German Reproducibility Network <span class="text-muted">(DE-RN)</span> is a <strong class="highlight-light">cross-disciplinary consortium that aims to increase trustworthiness and transparency of scientific research</strong> by investigating and encouraging the factors that contribute to robust research. We promote training activities and disseminate best practices, conduct and support meta-scientific research, and work with stakeholders to ensure coordination of efforts. DE-RN’s activities span multiple levels, including researchers, institutions and other stakeholders (e.g., funders, publishers, and Academic Societies).
{% end %}

<!-- Audience groups -->
{% landing_audience_groups() %}
  <div class="card">
    <div class="card-header">
      <img
        src="icons/microscope.svg"
        alt="..."
        loading="lazy"
      >
    </div>
    <div class="card-body">
      <strong class="h5 d-block card-title text-center">Researchers</strong>
      <p class="card-text">We <strong>support researchers</strong> in educating themselves about open science practices, and founding local open science communities.</p>
    </div>
  </div>
  <div class="card">
    <div class="card-header">
      <img
        src="icons/chart-network.svg"
        alt="..."
        loading="lazy"
      >
    </div>
    <div class="card-body">
      <strong class="h5 d-block card-title text-center">Grassroots Networks</strong>
      <p class="card-text">We <strong>connect local initiatives</strong> to a national network, and foster connections between them.</p>
    </div>
  </div>
  <div class="card">
    <div class="card-header">
      <img
        src="icons/landmark.svg"
        alt="..."
        loading="lazy"
      >
    </div>
    <div class="card-body pb-5">
      <strong class="h5 d-block card-title text-center">Institutions</strong>
      <p class="card-text">We <strong>advise institutions</strong> on how to embed open science practices in their work.</p>
    </div>
  </div>
  <div class="card">
    <div class="card-header">
      <img
        src="icons/users.svg"
        alt="..."
        loading="lazy"
      >
    </div>
    <div class="card-body">
      <strong class="h5 d-block card-title text-center">Other Stakeholders</strong>
      <p class="card-text">We <strong>represent the open science community</strong> toward other stakeholders in the wider scientific landscape.</p>
    </div>
  </div>
{% end %}

<!-- Members -->
{% landing_section(title="Founding members", id="members") %}
  <p>Please click on any logo to view the respective organization's representatives in DE-RN.</p>
  <div class="card-columns logo-masonry">
    <div class="card"
      data-toggle="popover"
      data-placement="bottom"
      data-content="<a href='https://www.dgps.de/index.php?id=christianfiebach' target='_blank'>Prof. Dr. Christian Fiebach</a>"
      data-html="true"
    >
      <img
        src="/logos/dgps.png"
        alt="Logo of the Deutsche Gesellschaft für Psychologie"
        class="card-img-top mt-3"
        loading="lazy"
      >
    </div>
    <div class="card"
      data-toggle="popover"
      data-placement="bottom"
      data-content="<a href='https://os.helmholtz.de/open-science-in-der-helmholtz-gemeinschaft/akteure-und-ihre-rollen/' target='_blank'>Dr. Bernadette Fritzsch</a>"
      data-html="true"
    >
      <img
        src="/logos/helmholtz.png"
        alt="Logo of the Helmholtz Association"
        class="card-img-top mt-2"
        loading="lazy"
      >
    </div>
    <div class="card"
      data-toggle="popover"
      data-placement="bottom"
      data-content="<a href='http://www.zbw.eu/de/forschung/klaus-tochtermann/' target='_blank'>Prof. Dr. Klaus Tochtermann</a>"
      data-html="true"
    >
      <img
        src="/logos/leibnitz.png"
        alt="Logo of the Leibniz Association"
        class="card-img-top mr-3"
        loading="lazy"
      >
    </div>
    <div class="card"
      data-toggle="popover"
      data-placement="bottom"
      data-content="<a href='https://www.osc.uni-muenchen.de/members/individual-members/schoenbrodt/index.html' target='_blank'>PD Dr. Felix Schönbrodt</a>"
      data-html="true"
    >
      <img
        src="/logos/lmu-osc.png"
        alt="Logo of the Open Science Center at LMU Munich"
        class="card-img-top mt-3"
        loading="lazy"
      >
    </div>
    <div class="card"
      data-toggle="popover"
      data-placement="bottom"
      data-content="<a href='https://www.coll.mpg.de/susann-fiedler' target='_blank'>Dr. Susann Fiedler</a> and<br> <a href='https://www.coll.mpg.de/135848/dr-rima-maria-rahal' target='_blank'>Dr. Rima-Maria Rahal</a>"
      data-html="true"
    >
      <img
        src="/logos/nosi.png"
        alt="Logo of the Network of Open Science Initiatives"
        class="card-img-top"
        loading="lazy"
      >
    </div>
    <div class="card"
      data-toggle="popover"
      data-placement="bottom"
      data-content="<a href='https://www.bihealth.org/de/forschung/quest-center/team/quest-office/'>Prof. Dr. Ulrich Dirnagl</a>"
      data-html="true"
    >
      <img
        src="/logos/quest.png"
        alt="Logo of the Quest Center"
        class="card-img-top"
        loading="lazy"
      >
    </div>
  </div>
{% end %}

<!-- International partners -->
{% landing_section(title="International partners") %}
  <a href="https://www.ukrn.org/" target="_blank"><strong>UK</strong> Reproducibility Network</a><br>
  <a href="https://www.swissrn.org/" target="_blank"><strong>Swiss</strong> Reproducibility Network</a><br>
  <a href="https://www.aus-rn.org/" target="_blank"><strong>Australian</strong> Reproducibility Network</a><br>
  <strong>Slovak</strong> Reproducibility Network<br>
{% end %}

+++
title = "German Reproducibility Network"
description = "Working together for trustworthy and useful research"
template = "landing.html"
+++

{% landing_jumbotron() %}
  <img src="/logos/grn/RN_German.png" style="position: relative; left: -24px;">
{% end %}

<!-- Mission -->
{% landing_section(title="Mission", id="mission") %}
  The German Reproducibility Network <span class="text-muted">(GRN)</span> is a <strong class="highlight-light">cross-disciplinary consortium that aims to increase trustworthiness and transparency of scientific research</strong> by investigating and encouraging the factors that contribute to robust research. We promote training activities and disseminate best practices, conduct and support meta-scientific research, and work with stakeholders to ensure coordination of efforts. GRN’s activities span multiple levels, including researchers, institutions and other stakeholders (e.g., funders, publishers, and Academic Societies).
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
      <strong class="h5 d-block card-title text-center">Reproducibility Initiatives</strong>
      <p class="card-text">We <strong>connect local or topic-centered Reproducibility Initiatives</strong> to a national network, and foster connections between them.</p>
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
{% landing_members(
  title="Founding members", id="members",
  data_path="content/members/founding_members.toml"
) %}
  <img src="/images/team.jpg" class="rounded mb-4 w-100">
  <p>Please click on any logo to view the respective organization's representatives in GRN.</p>
{% end %}

<!-- International partners -->
{% landing_section(title="International partners") %}
  <a href="https://www.ukrn.org/" target="_blank" rel="noreferrer"><strong>UK</strong> Reproducibility Network</a><br>
  <a href="https://www.swissrn.org/" target="_blank" rel="noreferrer"><strong>Swiss</strong> Reproducibility Network</a><br>
  <a href="https://www.aus-rn.org/" target="_blank" rel="noreferrer"><strong>Australian</strong> Reproducibility Network</a><br>
  <a href="https://slovakrn.wixsite.com/skrn"  target="_blank" rel="noreferrer"><strong>Slovak</strong> Reproducibility Network</a><br>
  <a href="https://www.ptrn.pt"  target="_blank" rel="noreferrer"><strong>Portuguese</strong> Reproducibility Network</a><br>
{% end %}

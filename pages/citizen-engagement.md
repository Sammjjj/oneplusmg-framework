---
title: "Citizen Engagement"
description: "Information and guidance for engaging citizens and building trust in genomic data sharing"
page_id: citizen-engagement
permalink: "/citizen-engagement"
navigation_tiles:
  - title: "Citizen Hub"
    description: "Start with accessible explanations of genomics and its implications for citizens."
    url: "/lets-talk-genomics/"
  - title: "Legal, ethics and governance"
    description: "Explore the safeguards and governance questions surrounding genomic data."
    url: "/governance-elsi"
  - title: "Use cases"
    description: "See examples of the research and healthcare questions that genomic data can support."
    url: "/usecases"
  - title: "About the Framework"
    description: "Learn the background to the 1+MG initiative and its supporting projects."
    url: "/about-the-framework"
---

<div class="my-4">
  <p>Citizen engagement is essential to making genomic data sharing understandable, responsible and responsive to public concerns. This page helps people involved in engagement and communication find accessible information about genomics, alongside Framework resources on public trust, governance and the ways genomic data can be used.</p>
</div>

{% include page-navigation-tiles.html tiles=page.navigation_tiles %}

<div class="my-4">
  <p>Start with the Citizen Hub for plain-language material that can support conversations with the public. Use Legal, ethics and governance to explore consent, access, privacy and trust-related questions, then Use cases to show why genomic data sharing matters in practice. About the Framework provides background on the initiative. These sections serve different audiences: the Citizen Hub is public-facing, while other Framework pages can contain more technical or policy-focused material.</p>
</div>

<div class="role-page-resources-full-width">
  {% include resource-tiles_compact.html
     resource_ids="b1mg-recommendation-citizen-engagement-public-trust,1mg-glossary,policy-vulnerable-subjects-groups,1mg-data-lifecycle"
  %}
</div>

<style>
  /* Match the other landing pages: full-width resource band and a 20px footer gap. */
  .container.min-vh-100 {
    min-height: 0 !important;
  }
  main#main.mb-5 {
    margin-bottom: 0 !important;
    padding-bottom: 20px;
  }
  .role-page-resources-full-width {
    position: relative;
    left: 50%;
    width: 100vw;
    transform: translateX(-50%);
  }
</style>

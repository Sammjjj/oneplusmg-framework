---
title: "Technical Implementers"
description: "Guidance and resources for implementing interoperable genomic data infrastructure"
page_id: technical-implementers
permalink: "/technical-implementers"
navigation_tiles:
  - title: "Technical infrastructure"
    description: "Explore services, infrastructure components and technical implementation guidance."
    url: "/technical-infrastructure"
  - title: "Data and metadata"
    description: "Find approaches to describing and making genomic data interoperable."
    url: "/data-metadata"
  - title: "Use cases"
    description: "See the research and healthcare scenarios that inform technical requirements."
    url: "/usecases"
  - title: "External alignment"
    description: "Understand relationships with wider European initiatives and standards."
    url: "/ehds-data-lifecycle"
---

<div class="my-4">
  <p>Technical implementers contribute to the services, systems and standards that enable secure discovery, access and analysis of genomic and related clinical data. This page directs you to the parts of the 1+MG Framework concerned with technical design, interoperability and practical implementation.</p>
</div>

{% include page-navigation-tiles.html tiles=page.navigation_tiles %}

<div class="my-4">
  <p>Begin with Technical infrastructure for the services and approaches that support federated data access. Use Data and metadata to examine interoperability requirements and Use cases to understand the problems that implementations are intended to solve. External alignment provides context for connecting solutions to broader European efforts. If your work includes data preparation or governance, consult the Data Stewards and Policy, ELSI and Governance role sections as well.</p>
</div>

<div class="role-page-resources-full-width">
  {% include resource-tiles_compact.html
     resource_ids="gdi-d4-2,minimal-metadata-model,gdi-d8-8,refget"
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

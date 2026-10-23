---
title: "Data Stewards"
description: "Guidance for preparing, describing and responsibly managing genomic data"
page_id: data-stewards
permalink: "/data-stewards"
navigation_tiles:
  - title: "Data and metadata"
    description: "Explore data descriptions, metadata requirements and interoperability guidance."
    url: "/data-metadata"
  - title: "Legal, ethics and governance"
    description: "Understand the conditions governing access and responsible data use."
    url: "/governance-elsi"
  - title: "Technical infrastructure"
    description: "See how data are handled through the services supporting the Framework."
    url: "/technical-infrastructure"
  - title: "Use cases"
    description: "Understand how intended uses shape data and metadata requirements."
    url: "/usecases"
---

<div class="my-4">
  <p>Data stewards support the quality, documentation, responsible use and interoperability of genomic and associated clinical data. This page brings together Framework guidance relevant to data preparation and stewardship, including metadata, governance and technical requirements for sharing and reuse.</p>
</div>

{% include page-navigation-tiles.html tiles=page.navigation_tiles %}

<div class="my-4">
  <p>Start with Data and metadata for the information needed to make datasets discoverable and interoperable. Consult Legal, ethics and governance for access conditions and responsible use, and Technical infrastructure for the systems with which data stewardship processes interact. The Use cases section helps relate these requirements to real scientific and clinical questions. For implementation details, the Technical Implementers entry point may also be useful.</p>
</div>

<div class="role-page-resources-full-width">
  {% include resource-tiles_compact.html
     resource_ids="minimal-metadata-model,gdi-d6-1,data-use-ontology,1mg-data-lifecycle"
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

---
title: Data and metadata
description: Guidance on data quality, metadata models, standards and ontologies for interoperable genomic data sharing.
permalink: "/data-metadata"
page_id: data-metadata
hide_sidebar: true
toc: false
navigation_tiles:
  - page_id: data-quality-inclusion
    anchor_id: data-quality-inclusion
    description: "Sequence data generation and quality requirements for WGS/WES data to be labelled as 1+MG compliant."
  - page_id: data-models-ontologies
    anchor_id: data-models-standards-ontologies
    description: "1+MG minimal data models for different use cases and recommendations on ontologies and data standards."
---

The 1+MG Framework provides guidance on the generation, description and exchange of genomic and associated health data. Shared approaches to data quality, metadata and interoperability are essential for making data discoverable and suitable for use across national Nodes.

Explore the two areas below for recommendations on sequencing and data quality requirements, and on the models, standards and ontologies used to describe and exchange data.

{% include page-navigation-tiles.html tiles=page.navigation_tiles %}

<div class="my-4">
  <p><strong>Data quality and inclusion</strong> covers sequence data generation, quality assessment and requirements for including genomic data in the 1+MG infrastructure.</p>
  <p><strong>Data models, standards and ontologies</strong> covers consistent descriptions of genomic, phenotypic and clinical data to enable cross-border discovery, linking and analysis.</p>
</div>

<div class="data-metadata-resources-full-width">
  {% include resource-tiles_compact.html
     resource_ids="quality-metrics-for-sequencing,best-practices-next-generation-sequencing,minimal-metadata-model,phenotypic-clinical-metadata-framework-3v0"
  %}
</div>

<style>
  .container.min-vh-100 { min-height: 0 !important; }
  main#main.mb-5 { margin-bottom: 0 !important; padding-bottom: 20px; }
  .data-metadata-resources-full-width {
    position: relative;
    left: 50%;
    width: 100vw;
    transform: translateX(-50%);
  }
</style>

---
title: 'Technical Infrastructure'
description: 'Technical guidance and interoperability standards for the 1+MG federated infrastructure.'
permalink: "/technical-infrastructure"
page_id: technical-infrastructure
hide_sidebar: true
toc: false
navigation_tiles:
  - page_id: data-discovery
    anchor_id: data-discovery
  - page_id: data-reception
    anchor_id: data-reception
  - page_id: storage-and-interfaces
    anchor_id: storage-interfaces
  - page_id: access-management
    anchor_id: data-access-management-tools
  - page_id: data-processing
    anchor_id: processing
---

The 1+MG technical infrastructure supports secure, interoperable access to genomic and associated clinical data across European nodes. It uses shared technical approaches to enable discovery, data reception, storage, access management and federated processing.

The 1+MG technical infrastructure is broken down into five functionalities as defined in the 2021 paper titled, [“Towards a Proof of Concept of Federated Infrastructure for the EU 1+ Million Genome Initiative”](https://zenodo.org/record/6089583).  This includes: Data Discovery, Data Reception, Storage and Interfaces, Data Access Management, and Processing.  These functionalities were originally defined as follows:

<span id="infrastructure-components"></span>
{% include page-navigation-tiles.html tiles=page.navigation_tiles five_column_grid=true %}

<span id="infrastructure-vision"></span>
## Infrastructure Vision

### [B1MG Secure cross-border data access roadmap v2.0](https://zenodo.org/record/5018526#.YXGlNNbMKdY): June 2021 <span class="badge badge-primary">Informational<i class="fa-sharp fa-solid fa-circle-info"></i></span>

A  roadmap presented here is to define the timelines to provide a proof of concept demonstrator of secure cross border data access, describe the technologies required to develop such a demonstrator, and to detail the work that has gone into determining the roadmap and requirement for the proof of concept demonstrator. The roadmap also outlines how it is expected that the work carried out towards the initial proof of concept will support the developing roadmap for 2022 and beyond, as the proof of concept evolves from a demonstrator with synthetic data to a production system accessing real genetic and phenotypic data.

### [B1MG Secure Access Demonstrator](https://zenodo.org/record/7590822) <span class="badge badge-dark">Recommended<i class="fa-solid fa-thumbs-up"></i></span>

The 1+MG data infrastructure needs to be defined to ensure data managed within the federated network are compliant with the European and national legislation on data protection, security, and ELSI principles agreed in 1+MG. At the same time the aim is to maximise the Findability, Accessibility, Interoperability and Reusability of the 1+MG data, according to FAIR principles. 

In this deliverable a Proof of Concept (PoC) was built using existing standards, applications, and services to demonstrate cross border data access for two 1+MG use cases; rare disease and cancer. The intention is to create a technical infrastructure baseline and advancement for the next iteration of implementation data protection principles according to the GDPR

## Technical interoperability

Global Alliance for Genomics and Health (GA4GH) standards are used to link the different applications supporting the five technical functionalities within the B1MG Proof of Concept.  The chosen standards aligned with the functionalities can be seen in the diagram below.  While none of these standards are required for a Node to implement, they can be seen as the interoperability backbone of the infrastructure.

<img src="{{ 'assets/img/data-infrastructure.png' | relative_url }}" class="m-2" style="max-width: 100%; max-height: 100%; vertical-align: middle" alt="Cancer Proof of Concept Schema" />

<figcaption class="text-center">Proof of Concept Schema</figcaption>

<!--<img src="{{ 'assets/img/technical-infrastructure-figure2.png' | relative_url }}" class="m-2" style="max-width: 100%; max-height: 100%; vertical-align: middle" alt="Rare Disease Proof of Concept Schema" />

<figcaption class="text-center">Rare Disease Proof of Concept Schema</figcaption>-->

<span id="european-genomes-dashboard"></span>
<span id="user-portal-central-services"></span>
## [European Genomes Dashboard](https://dashboard.onemilliongenomes.eu/)
This dashboard shows the current number of genomic datasets across the 1+MG Member States.

## User Portal & Central Services
* Under development by the European Genomic Data Infrastructure project, the User Portal will be the main European-level entry point for data access within the infrastructure.

<div class="technical-resources-full-width">
  {% include resource-tiles_compact.html
     resource_ids="b1mg-secure-cross-border-data-access-roadmap-v2,b1mg-secure-access-demonstrator,beacon,life-science-login"
  %}
</div>

<style>
  .container.min-vh-100 { min-height: 0 !important; }
  main#main.mb-5 { margin-bottom: 0 !important; padding-bottom: 20px; }
  .technical-resources-full-width {
    position: relative;
    left: 50%;
    width: 100vw;
    transform: translateX(-50%);
  }
</style>

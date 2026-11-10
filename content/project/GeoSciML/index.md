---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "GeoSciML"
summary: "A collaborative OGC-CGI working group for the GeoSciML geological data standard"
authors: [eric-boisvert]
tags: [active]
categories: []
featured: true
date: 2020-06-12T11:49:33+01:00

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

*   [What is GeoSciML?](#what-is-geosciml)
*   [Why do we need GeoSciML?](#why-do-we-need-geosciml)
*   [History of GeoSciML](#history-of-geosciml)
*   [Downloads and Other Resources](#downloads-and-other-resources)
*   [GeoSciML Standards Working Group](#geosciml-standards-working-group)
*   [Global Use of GeoSciML](#global-use-of-geosciml)

[Join the GeoSciML team](mailto:eric.boisvert2@canada.ca?subject=Application%20to%20join%20the%20GeoSciML%20Standards%20Working%20Group)

## What is GeoSciML

![GeoSciML map](/img/map_image.jpg)

**GeoSciML** is an XML–based data transfer standard for the exchange of digital geoscientific information. It accommodates the representation and description of features typically found on geological maps, as well as being extensible to other geoscience data such as drilling, sampling, and analytical data.

GeoSciML provides a standard data structure for a suite of common geologic features (eg, geologic units, structures, earth materials) and artefacts of geological investigations (eg, boreholes, specimens, measurements). Supporting objects such as the geologic timescale and vocabularies are also provided as linked resources, so that they can be used as classifiers for the primary objects in the GeoSciML standard.

The GeoSciML data standard is underpinned by several established OGC and ISO standards, including Web Feature Service (WFS – ISO 19142), Geography Markup Language (GML – ISO 19136), Observations & Measurements (O&M – ISO 19156), and SWE Common.

A parallel data standard for simple map visualisation, **GeoSciML-Portrayal**, has also been developed. It enables portrayal of a small simplified subset of the GeoSciML data model using Web Map Services (WMS) or simple Web Feature Services (WFS).

## Why do we need GeoSciML

Users of geoscience maps and data know that geological features have no respect for national or provincial borders. Inevitably users of geoscience data will need to source data from more than one data provider. Receiving data in a number of local data formats is recognised as a major impediment to efficient and effective use of data.

GeoSciML seeks to provide a single, open source, globally agreed data structure that is used to deliver digital geological data over the internet. Additionally, the use of agreed vocabularies of geoscience terminology provides consistency in the semantic language used across geological datasets. Data providers do not need to change their internal databases to match the GeoSciML structure, but instead translate their data to the GeoSciML structure at the point of delivery.

## History of GeoSciML

The GeoSciML project was initiated in 2003 under the auspices of the CGI Working Group on Data Model Collaboration. The project was incorporated into the newly formed CGI Interoperability Working Group in 2004. In 2013, development of GeoSciML was moved to the current GeoSciML Standards Working Group, a collaboration between the CGI and the Open Geospatial Consortium (OGC).

A number of predecessor projects from North America, Europe, Australia and Asia have had a strong influence on the development of GeoSciML. These include activities undertaken within national statutory bodies (eg, British and Japanese Geological Surveys), in multi-jurisdictional contexts (eg, the [North American Data Model](http://ngmdb.usgs.gov/www-nadm/) for geological maps) or oriented to an industry sector (eg, the Australian Exploration and Mining Markup Language - [XMML](https://www.seegrid.csiro.au/wiki/bin/view/Xmml/WebHome)).

The international GeoSciML development team meets at least annually to ensure that GeoSciML continues to address the needs of data providers and users. Most recent meetings have been held in St Petersburg (2013), Tuscon (2014), Ispra (2015), Dublin (2016) and Vienna (2017).

## Downloads and Other Resources


*   [www.geosciml.org](http://www.geosciml.org) — Documentation, cookbooks, UML models, examples, and XML schemas for GeoSciML and GeoSciML-Portrayal.
*   [schemas.geosciml.org](http://schemas.geosciml.org) — XML schemas for GeoSciML and GeoSciML-Portrayal.
*   [resource.geosciml.org](http://resource.geosciml.org) — Geoscience vocabularies to support the GeoSciML data model, developed by the CGI Geoscience Terminology Working group and its predecessors.
*   [Publications and presentations](https://www.seegrid.csiro.au/wiki/CGIModel/GeoSciMLPresentations) — Articles and conference abstracts, posters and presentations describing GeoSciML and related projects from 2006 to 2016. (Please respect the copyright of the authors of these publications.)

## GeoSciML Standards Working Group


*   The [GeoSciML SWG](http://www.opengeospatial.org/projects/groups/geoscimlswg) is responsible for development and governance of GeoSciML. Members of the OGC can join the OGC GeoSciML Standards Working Group (SWG) as observers through the [OGC Portal](https://portal.opengeospatial.org/), and can apply to be full SWG members after a short period.
*   A [mailing list](https://lists.opengeospatial.org/mailman/listinfo/geosciml) is available for anyone interested in GeoSciML development. You do not have to be a member of OGC or the GeoSciML SWG to be on this mailing list.
*   [Wiki](http://external.opengeospatial.org/twiki_public/GeoSciMLswg/WebHome) - The work of the GeoSciML SWG is recorded on its [public wiki site](http://external.opengeospatial.org/twiki_public/GeoSciMLswg/WebHome). The wiki also contains links to all previous development of the GeoSciML model which was done under the CGI Interoperability Working Group.

The SWG contains members from all over the world, including:

*   Eric Boisvert (Chair - Geological Survey of Canada)
*   Oliver Raymond (Geoscience Australia)
*   Sylvain Grellet (BRGM, France)
*   Tim Duffy (British Geological Survey)
*   Marcus Sen (British Geological Survey)
*   James Passmore (British Geological Survey)
*   Jouni Vuollo (Geological Survey of Finland)
*   Mark Rattenbury (GNS, New Zealand)
*   Alistair Ritchie (Landcare Research, New Zealand)
*   Carlo Cipolloni (APAT, Italy)
*   Simon Cox (CSIRO, Australia)

as well as many observers.

## Global Use of GeoSciML


GeoSciML is used, or is endorsed, as the geoscientific data transfer standard by data sharing initiatives across the world. Some examples include:

*   The [OneGeology project](http://www.onegeology.org) is currently demonstrating the use of GeoSciML web feature services and GeoSciML-Portrayal web map services in its portal of world-wide geological map data.
*   The [European INSPIRE Directive](http://inspire.ec.europa.eu/) is using GeoSciML as its data standard for exchange of geological information between countries of the European Union.
*   The [US Geoscience Information Network](http://usgin.org/) is using GeoSciML-Portrayal and GeoSciML to share geological data between government agencies, educational and private institutions.
*   The [Canadian Groundwater Information Network](http://ngwd-bdnes.cits.nrcan.gc.ca/service/api_ngwds/en/wmc/aquifermap.html) uses an extension of GeoSciML – GroundwaterML – to integrate water well information from multiple jurisdictions.
*   The [Australian Geoscience Information Network](http://portal.geoscience.gov.au/) and [AuScope](http://auscope.org.au/site/) projects are using GeoSciML to deliver borehole data from Australian state and territory agencies.
*   The [African-European Georesources Observation System](http://www.aegos-project.org/index.php) is promoting GeoSciML as the standard for geoscience data exchange across Africa.

[![OneGeology logo](/img/onegeology.jpg)](http://www.onegeology.org) [![INSPIRE logo](/img/inspire_logo.jpg)](http://inspire.ec.europa.eu/) [![USGIN logo](/img/l-logo-usgin-75.png)](http://usgin.org/) [![Groundwater Information Network logo](/img/CanGIN.png)](http://ngwd-bdnes.cits.nrcan.gc.ca/service/api_ngwds/en/wmc/aquifermap.html) [![AUSGIN logo](/img/AUSGIN-logo.jpg)](http://portal.geoscience.gov.au/) [![AuScope logo](/img/auscope_2019.png)](https://www.auscope.org.au/) [![AEGOS logo](/img/aegos.png)](https://cordis.europa.eu/project/rcn/89340/factsheet/en)
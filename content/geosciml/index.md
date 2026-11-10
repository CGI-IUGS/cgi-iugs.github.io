---
title: GeoSciML
summary: "A data model and data transfer standard for geological data, from basic map data to complex relational geological databases."
---

GeoSciML is a data model and data transfer standard for geological data, from basic map data to complex relational geological databases. It is an [OGC standard](http://www.opengeospatial.org/standards/geosciml) developed by the CGI and the Open Geospatial Consortium. See the [GeoSciML working group](/project/geosciml/) page for its background, history and how to take part.

The documents, schemas and vocabularies listed here stay at their addresses on geosciml.org, because XML documents, papers and INSPIRE data cite them by URL.

## Current version: GeoSciML 4.1

**Data model documentation**

* OGC Implementation Specification document ([html](http://docs.opengeospatial.org/is/16-008/16-008.html))
  * Chinese translation ([docx](https://geosciml.org/doc/geosciml/4.1/documentation/ogc_spec_translations/16-008_OGC_Geoscience_Markup_Language_GSML4.1-CN2018.08.18.docx)), with many thanks to the China Geological Survey
* UML model ([html](https://geosciml.org/doc/geosciml/4.1/documentation/html/index.htm))
* Enterprise Architect UML file ([eap](https://geosciml.org/doc/geosciml/4.1/documentation/uml/))
* UML summary wall poster ([pdf](https://portal.opengeospatial.org/files/?artifact_id=72895))

**XML schemas and encoding examples** ([xsd, xml](http://schemas.opengis.net/gsml/4.1/)), at the OGC schema repository.

**Guides for building GeoSciML web feature services**

* How To Serve a GeoSciML Web Feature Service (WFS) Using GeoServer ([pdf](http://www.onegeology.org/docs/technical/OneGeologyWFSCookbook_v1.2.pdf))
* GeoSciML Encoding Cookbook for OneGeology and INSPIRE ([pdf](http://www.onegeology.org/docs/technical/GeoSciML_Cookbook_1.2.1.pdf))

**Changes from version 4.0**

GeoSciML 4.1 differs from 4.0 in two respects:

* The XSD schemas are now at the [OGC schema repository](http://schemas.opengis.net/gsml).
* "GeoSciML-Portrayal", the package for simple WFS and WMS services, is now called "GeoSciML-Lite".

All other aspects of the 4.1 model and schemas are the same as 4.0.

## Previous versions

### GeoSciML

* [Version 4.0](https://geosciml.org/doc/geosciml/4.0/documentation/) (2015)
* [Version 3.2](https://geosciml.org/doc/geosciml/3.2/documentation/) (2013)
  * Instructional cookbook for encoding GeoSciML web services for INSPIRE ([pdf](https://geosciml.org/doc/geosciml/3.2/documentation/cookbook/INSPIRE_GeoSciML_Cookbook%20_1.0.pdf))
* [Version 3.1](https://geosciml.org/doc/geosciml/3.1/documentation/)
* [Version 3.0](https://geosciml.org/doc/geosciml/3.0/documentation/) (2012)
  * Example database for mapping geological data to GeoSciML 3 web services ([zip](https://geosciml.org/reference_database/reference_database_2013-11-07.zip))
* [Version 2.1](https://geosciml.org/doc/geosciml/2.1/)
* [Version 2.0](https://geosciml.org/doc/geosciml/2.0/) (2009)
* [Version 1.1.1](https://geosciml.org/doc/geosciml/1.1.1/)
* [Version 1.1.0](https://geosciml.org/doc/geosciml/1.1.0/)
* [Version 1.0.0](https://geosciml.org/doc/geosciml/1.0.0/) (2005)
* [Version 0.9.0](https://geosciml.org/doc/geosciml/0.9.0/)

### GeoSciML-Portrayal

GeoSciML-Portrayal is now the GeoSciML-Lite package of GeoSciML 4.

* [Version 2.0](https://geosciml.org/doc/geosciml-portrayal/2.0.1/) (2013)
* Version 1.0 (2011): [XML schema](https://geosciml.org/schemas/geosciml-portrayal/1.0/)
  * Guide for building GeoSciML-Portrayal (version 1) web services ([pdf](http://repository.usgin.org/sites/default/files/dlio/files/2012/u11/geosciml-portrayalcookbook0.7.pdf)), © [USGIN](http://usgin.org/USGIN)

### Geologic Time

* [Version 2.0](https://geosciml.org/geotime/2.0/) (2009)

### CGI Utilities

* [Version 3.0](https://geosciml.org/doc/cgiutilities/3.0/)
* [Version 1.0](https://geosciml.org/doc/cgiutilities/1.0/)

## Schemas and vocabularies

* [XML schemas for all versions](https://geosciml.org/schemas/), also at schemas.geosciml.org
* [Geoscience vocabularies for linked data](https://geosciml.org/resource/), for describing geological features, geological time, mineral occurrences and mining-related features
  * [CGI vocabulary service](https://cgi.vocabs.ga.gov.au/vocab/): all CGI vocabularies, with SPARQL endpoints and APIs
  * [Register of CGI vocabularies](https://geosciml.org/resource/vocabularies-full-list.html) and their URIs
  * [Vocabulary files for GeoSciML](https://github.com/CGI-IUGS/cgi-vocabs/tree/master/vocabularies/geosciml) (TTL)
  * The vocabularies are maintained by the [Geoscience Terminology Working Group](/project/geoscienceterminology/)

## News archive

* **March 2017**: [GeoSciML version 4.1 is now an official OGC standard](http://www.opengeospatial.org/standards/geosciml). Read the [OGC press release](http://www.opengeospatial.org/pressroom/pressreleases/2563).
* **August 2014**: [An example database](https://geosciml.org/reference_database/reference_database_2013-11-07.zip) is now available to demonstrate mapping of geological data to GeoSciML 3 WFS schemas.
* **April 2014**: UK INSPIRE publishes a new guide for building GeoSciML 3 WFS using GeoServer. As part of the European INSPIRE initiative, the UK INSPIRE team have published a guide to setting up an INSPIRE-compliant GeoSciML Web Feature Service (WFS 2.0). It addresses requirements for INSPIRE services, but much of it can also be used by service providers outside Europe to build GeoSciML services using [GeoServer](http://geoserver.org/). [Download the guide](http://data.gov.uk/sites/default/files/library/INSPIREWFSCookbook_v1.0.pdf).
* **December 2013**: [Instructional cookbook for encoding GeoSciML web services for INSPIRE](https://geosciml.org/doc/geosciml/3.2/documentation/cookbook/INSPIRE_GeoSciML_Cookbook%20_1.0.pdf).
* **July 2013**: [GeoSciML-Portrayal 2.0.1 schema and documentation released](https://geosciml.org/schemas/).
* **February 2013**: [GeoSciML-Portrayal 2.0.0 simple features WFS and WMS schema released](https://geosciml.org/schemas/).
* **December 2012**: [Updated version 3.1 schemas released](https://geosciml.org/schemas/).

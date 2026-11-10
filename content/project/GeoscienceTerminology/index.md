---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Geoscience Terminology Working Group (GTWG)"
summary: "A CGI working group developing and publishing multi-lingual geoscience vocabularies"
authors: [mark-rattenbury]
tags: [active]
categories: []
featured: true
date: 2019-06-12T11:50:03+01:00

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

[Join the Geoscience Terminology team](mailto:chair.gtwg@gmail.com?subject=[Application]%20to%20join%20the%20Geoscience%20%20Working%20Group)

What GTWG does
--------------

The Geoscience Terminology Working Group develops, reviews, adopts, publishes and acts as steward for internationally accepted geoscience vocabularies under the auspices of the Commission for the Application and Management of Geoscience Information (CGI). The GTWG manages these vocabularies and their associated documentation for use in geoscience information systems, in particular for the [GeoSciML](/project/geosciml/) and [EarthResourceML](/project/earthresourceml/) data transfer standards. The group assesses proposals for new geoscience vocabularies and change requests for existing CGI vocabularies. GTWG also liaises with other semantic interoperability groups to ensure cross-domain interoperability and promotes the use of vocabularies for enhanced dataset interoperability.

Our vocabularies
----------------

More than 100 geoscience vocabularies have been identified to support the [GeoSciML](http://www.geosciml.org/) and [EarthResourceML](http://www.earthresourceml.org/) data models and over 50 of these have now been compiled and adopted. These are available through the [CGI vocabularies register](http://resource.geosciml.org/def/voc/). These vocabularies include key lists such as:

[lithology](http://resource.geosciml.org/classifier/cgi/lithology)

265 lithological rock names, hierarchically organised around up to six levels e.g. tholeiitic basalt, basalt, basic igneous rock, basic igneous material, igneous material, compound material

[resource commodity types](http://resource.geosciml.org/classifier/cgi/commodity-code)

293 types of earth-sourced commodity, hierarchically organised around up to six levels e.g. anthracite, coal, carbonaceous material, organic material, industrial material, direct use commodity

[nature of rock unit contacts](http://resource.geosciml.org/classifier/cgi/contacttype)

36 types of geological contacts, hierarchically organised around up to five levels, e.g. angular unconformable contact, unconformable contact, depositional contact, lithogenetic contact, contact

[borehole drilling method](http://resource.geosciml.org/classifier/cgi/boreholedrillingmethod)

30 types of drilling technology, hierarchically organised around up to three levels e.g. gravity core, direct push, core drilling

The important [CGI geological time vocabulary service](http://resource.geosciml.org/) will be merged into the main CGI vocabularies register in the near future. The geological time vocabulary draws on age definitions established by the [International Commission on Stratigraphy](http://www.stratigraphy.org/) and was the first CGI vocabulary to provide multi-lingual terms, currently in 19 languages.

The CGI vocabulary service is hosted by the [Australian National Data Service](http://www.ands.org.au/) and is administered through [Geoscience Australia](http://www.ga.gov.au/). Additional resources are available from the [Research Vocabularies Australia website](https://vocabs.ands.org.au/search#!/?q=&p=1&publisher=CGI%20Geoscience%20Terminology%20Working%20Group), including downloadable code-lists in Resource Description Framework (RDF) formats (e.g. RDF/XML, JSON, Turtle) and Linked Data APIs.

Background
----------

The CGI has had two previous workgroups involved in vocabulary production. The Multi-lingual Thesaurus Working Group was formed in 2003 to continue work of the Multhes working group of the 1990s. The Concept Definition Task Group was formed by the CGI Interoperability Working Group in 2007 to develop concept vocabularies for populating GeoSciML interchange documents. Because of the overlapping interests the CGI council has determined that it will be more efficient and effective to merge the efforts. The Geoscience Terminology Working Group was established early in 2013 to undertake this combined role.

Why are vocabularies needed?
----------------------------

![Granite lithology](/img/granite_lithology.jpg)

Vocabularies are restricted lists of agreed terms that describe features contained in database fields. By limiting database values to the contents of common agreed vocabularies the interoperability and interchange of the information is enhanced. The list contents are also multi-lingual where translations of the originating list language are made available in other languages. Vocabularies also organise their terms hierarchically so that terms can be parts of a group that is a valid term itself. For example "basalt" and "gabbroic rock" are narrower adopted CGI terms for the broader level "basic igneous rock". and this enables database searching or map portrayal based on either the broader or the narrower term.

How vocabularies are adopted
----------------------------

Proposals for new geoscience vocabularies or change requests for existing CGI vocabularies, are lodged with the GTWG, usually instigated from within the group but can be initiated from outside for a specific requirement. Each proposal is assessed by the group to establish whether the changes are minor and do not require the GTWG's formal consultation, review and adoption process or whether the proposed changes are significant and need input from the group. Each new or changed vocabulary proposal is assigned a 'shepherd' responsible for developing a draft vocabulary if new, or modifying a version of an existing vocabulary. The vocabulary proposal is then reviewed by the GTWG and through them colleagues and the wider community. After consultation and response to comments, the shepherd recommends voting for its adoption to the GTWG. Upon adoption, the vocabulary is registered in the CGI vocabulary repository.

Initial vocabulary development typically begins with a spreadsheet compilation of candidate terms using Excel and Google Sheets shared spreadsheets on the GTWG Google Drive facility. When a vocabulary has been completed, reviewed and adopted, it is migrated into [SKOS](http://www.w3.org/2004/02/skos/), an [RDF](https://www.w3.org/2001/sw/wiki/RDF) application for encoding concepts with identifiers, definitions, source information, standard thesaurus type relationships, and language-localized labels. The RDF-encoded file is then migrated on to the vocabulary server, for example the [commodity code vocabulary](http://resource.geosciml.org/classifier/cgi/commodity-code/).

How to lodge a Request for Change
---------------------------------

A Request for Change refers to a proposal to modify an adopted existing CGI vocabulary or to propose a new geoscience vocabulary. The GTWG recognise that the adopted vocabularies will not always suit all user requirements and that needs of the wider geoscience community will evolve. Adopted vocabularies should be regarded as live working versions rather than irrevocably finalised. The GTWG will consider a Request for Change from groups or individuals outside of the working group. These Requests for Change can be sent to the working group via an email request to <chair.gtwg@gmail.com>. Alternatively a Request for Change can be sent to a GTWG member directly.

Membership
----------

The GTWG contains members from all over the world. The current membership of 27 includes representatives from geological surveys of Australia, Brazil, Canada, China, Denmark, Finland, France, Germany, Great Britain, Italy, New Zealand, Russia, Slovenia, Sweden and USA.

The GTWG needs active participation in the construction of geoscience vocabularies. Participants with expertise in specialist geoscience domains, information science and data models are particularly welcomed. For those who would like to contribute to the GTWG should contact the Chair, outlining their areas of expertise and their capacity to assist.
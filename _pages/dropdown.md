---
# NOTE: This file is inactive and safe to delete.
#
# In stock al-folio, the navbar is generated automatically from page front
# matter, and this file is what creates the "Resources" dropdown. On this
# site the navbar is hardcoded in _includes/header.liquid instead, so nothing
# reads the `children` list below.
#
# Left here (unpublished) only so the nav structure is documented in one
# place. `published: false` stops Jekyll from generating a stray, empty
# /dropdown/ page. To change the navbar, edit _includes/header.liquid.
published: false
layout: page
title: Resources
nav: false
nav_order: 5
dropdown: true
children:
  - title: All Resources
    permalink: /resources/
  - title: High School
    permalink: /resources/hs/
  - title: Higher Education
    permalink: /resources/he/
---

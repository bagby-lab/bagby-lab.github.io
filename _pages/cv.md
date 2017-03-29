---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* BS in Biological chemistry, BA in Chemistry, BA in Philosophy, University of Chicago, 2000
* BA(Hons) in Physiological sciences, Oxford University, 2002
  * Marshall Scholar
* PhD in Biology, Massachusetts Institute of Technology, 2009
  * HHMI Pre-doctoral Fellow

Research
======
* 2009-2016: Postdoctoral research
  * UCSB Department of Earth Science, Marine Science Institute
  * Advisor: David L. Valentine

* 2002-2009: Graduate research
  * Massachusetts Institute of Technology Department of Biology
  * Advisors: Sallie W. Chisholm, David P. Bartel
  
* 2001-2002: Undergraduate research
  * Oxford University Department of Biochemistry
  * Advisor: James McDonnell
  
* 1998-2000: Undergraduate research
  * University of Chicago Department of Biochemistry & Molecular Biology
  * Advisor: Phoebe A. Rice
  
Publications
======
{% for post in site.publications reversed %}
 {% include archive-single-cv.html %}
{% endfor %}
   

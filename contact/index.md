---
layout: page
title: Contact Information
tags: [papers]
modified: Sat May 16 14:50:50 EDT 2015
comments: false
share: false
image:
  feature: near-ilulissat.jpg

---


{% if page.author %}
  {% assign author = site.data.authors[page.author] %}{% else %}{% assign author = site.owner %}
  {% endif %}



<div style="margin: 10px" itemscope itemtype="http://schema.org/Person">
<p>
  {% if author.email %}<a href="mailto:{{ author.email }}" class="author-social" target="_blank"><i class="fa fa-fw fa-envelope-square"></i> Email</a>{% endif %}
  {% if author.twitter %}<a href="http://twitter.com/{{ author.twitter }}" class="author-social" target="_blank"><i class="fa fa-fw fa-twitter-square"></i> Twitter</a>{% endif %}
<a class="author-social" href="tel:+17322002705"><i class="fa fa-fw fa-phone-square"></i> Phone: +1-732-200-2705</a>
</p>
</div>


### Mailing address

Dept. of Earth & Planetary Sciences  
Wright Labs, 610 Taylor Road  
Rutgers University  
Piscataway, NJ 08854-8066, USA

### Offices 

Wright Labs, Rm. 225  
Dept. of Earth & Planetary Sciences  
610 Taylor Road, Busch Campus, Piscataway, NJ  
&nbsp;  
Civic Square Building, Rm. 248  
Bloustein School of Planning & Public Policy  
33 Livingston Ave., New Brunswick, NJ

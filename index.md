---
layout: page
excerpt: "Bob Kopp, Associate Professor of Earth & Planetary Sciences, Rutgers University"
# tags: []
image:
  feature: near-ilulissat.jpg
  # credit: Bob Kopp
  # creditlink: http://wegraphics.net/downloads/free-ultimate-blurred-background-pack/

share: false
---

I am a climate scientist, Earth historian, geobiologist, and energy policy wonk. I serve at [Rutgers University](http://www.rutgers.edu/) as an associate professor in
the [Department of Earth & Planetary Sciences](http://geology.rutgers.edu/) and as Associate Director of the [Rutgers Energy Institute](http://rei.rutgers.edu/). I am also a member of the
[Institute of Earth, Ocean, and Atmospheric Sciences](http://eoas.rutgers.edu/) and of the [Rutgers Climate Institute](http://climatechange.rutgers.edu), and I am affiliated with graduate programs in [Atmospheric Sciences](http://atmos.rutgers.edu), [Geological Sciences](http://eps.rutgers.edu), [Oceanography](http://marine.rutgers.edu), [Statistics](http://statistics.rutgers.edu), and [Planning and Public Policy](http://policy.rutgers.edu/).

My [research](research/) focuses on understanding uncertainty in past and future climate change, with major emphases on sea-level change and on the interactions between physical climate change and the economy. I served as the lead scientist for the [ _American Climate Prospectus: Economic Risks in the United States_](http://www.climateprospectus.org/), the technical analysis underlying the [Risky Business Project](http://www.riskybusiness.org/). I also served on the
[Maryland Climate Change Commission’s sea-level rise expert group](http://www.umces.edu/project/sea-level-along-maryland%E2%80%99s-shorelines-could-rise-2-feet-2050-according-new-report) and was a contributing author to Working Groups 1 and 2 of the [Intergovernmental Panel on Climate Change](http://www.ipcc.ch)’s Fifth Assessment Report.

Prior to joining the Rutgers faculty, I served as a [AAAS Science & Technology Policy Fellow](http://fellowships.aaas.org/) in the [U.S. ](http://www.energy.gov)[Department of Energy](http://www.energy.gov)'s Office of Policy and International Affairs and as a [Science, Technology, and Environmental Policy](http://www.princeton.edu/step/) postdoctoral research fellow at Princeton University. I received my Ph.D. in geobiology from Caltech and my undergraduate degree in geophysical sciences from the University of Chicago. 

 <div id="index" style="width: 100%" >
     {% for post in site.posts limit:1 %}
    <h2><a href="{{ site.url}}/posts/">Recent Posts</a></h2>
    {% endfor %}
  {% for post in site.posts limit:5 %}    
    <article>
      {% if post.link %}
        <h4 class="link-post"><a href="{{ site.url }}{{ post.url }}" title="{{ post.title }}">{{ post.title }}</a> <a href="{{ post.link }}" target="_blank" title="{{ post.title }}"><i class="fa fa-link"></i></a></h4>
      {% else %}
        <h4><a href="{{ site.url }}{{ post.url }}" title="{{ post.title }}">{{ post.title }}</a></h4>
        <p>{{ post.excerpt | strip_html | truncate: 160 }}</p>
      {% endif %}
    </article>
    {% endfor %}
	
	</div><!-- /#index -->

#### [In the media](http://www.google.com/search?hl=en&gl=us&tbm=nws&q="Robert+Kopp"+OR+"Bob+Kopp"+Rutgers)

* [_Rutgers Today_ (Dec. 2014)](http://news.rutgers.edu/feature/earth-scientists-urgent-mission-takes-shape-rutgers/20141217)
* [Radio Times with Marty Moss-Coane [WHYY] (July 2014)](http://goo.gl/DfPnc9)
* [_New York Times_ Sunday Review (Nov. 2012)](http://nyti.ms/TcArGg)

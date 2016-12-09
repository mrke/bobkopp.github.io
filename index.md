---
layout: page
excerpt: "Bob Kopp (Robert E. Kopp) is a climate scientist, Earth historian, geobiologist, and energy policy wonk at Rutgers University."
image:
  feature: near-ilulissat.jpg

share: false
---

I am a climate scientist, Earth historian, geobiologist, and energy policy wonk. I serve at [Rutgers University](http://www.rutgers.edu/) as an associate professor in
the [Department of Earth & Planetary Sciences](http://geology.rutgers.edu/) and as Associate Director of the [Rutgers Energy Institute](http://rei.rutgers.edu/). 

<div style="float: right; margin: 20px; max-width: 150px; box-shadow: 10px 10px 5px #888888; border:  1px solid gray;"><a href="http://www.climateprospectus.org" target="_blank"><img src="images/EconomicRisksOfCC.jpg"></a></div>

My [research](research/) focuses on understanding uncertainty in past and future climate change, with major emphases on sea-level change and on the interactions between physical climate change and the economy. I am a lead author of [_Economic Risks of Climate Change: An American Prospectus_](http://www.climateprospectus.org/) and served as lead scientist for the technical analysis underlying the [Risky Business Project](http://www.riskybusiness.org/). I was a contributing author to the [Intergovernmental Panel on Climate Change](http://www.ipcc.ch)’s Fifth Assessment Report, and have served on sea-level rise expert groups for several states and and the city of Boston. 

In addition to the  Rutgers  [Department of Earth & Planetary Sciences](http://geology.rutgers.edu/) and
the [Rutgers Energy Institute](http://rei.rutgers.edu/), I am also a member of the
[Institute of Earth, Ocean, and Atmospheric Sciences](http://eoas.rutgers.edu/) and of the [Rutgers Climate Institute](http://climatechange.rutgers.edu). I am affiliated with Rutgers graduate programs in [Atmospheric Sciences](http://atmos.rutgers.edu), [Geological Sciences](http://eps.rutgers.edu), [Oceanography](http://marine.rutgers.edu), [Statistics](http://statistics.rutgers.edu), and [Planning and Public Policy](http://policy.rutgers.edu/).


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

* [_The Conversation_ (November 2016)](https://goo.gl/OWovmZ)
* [_The Conversation_ (June 2016)](https://goo.gl/nOadXV)
* [Radio Times with Marty Moss-Coane [WHYY] (February 2016)](http://goo.gl/zWLUsW)
*  [PRI's The World (February 2016)](http://goo.gl/RuhXl3)
* [_New York Times_ Sunday Review (June 2015)](http://nyti.ms/1JyXkk7)
* [_Rutgers Today_ (Dec. 2014)](http://news.rutgers.edu/feature/earth-scientists-urgent-mission-takes-shape-rutgers/20141217)
* [Radio Times with Marty Moss-Coane [WHYY] (July 2014)](http://goo.gl/DfPnc9)
* [_New York Times_ Sunday Review (Nov. 2012)](http://nyti.ms/TcArGg)


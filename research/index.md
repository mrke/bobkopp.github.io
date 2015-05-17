---
layout: page
title: Research
tags: [research]
modified: 15 May 2013
comments: false
share: false
image:
  feature: near-ilulissat.jpg

---


<section id="table-of-contents" class="toc">
<div id="drawer" markdown="1">
<!--<header> <h3>Overview</h3></header>-->
*  Auto generated table of contents
{:toc}
</div>
</section><!-- /#table-of-contents -->


Over the last two centuries, human civilization has become a geological force. We are inducing planetary environmental conditions like those that Earth has not experienced for millions of years. Without mitigation of emissions, we may generate greenhouse gas concentrations and global temperatures more akin to those of the early Paleogene, over forty million years ago, than those of the current geological period, the Neogene.

The course society steers today -- through decisions made in institutions that act on the timescales of news cycles, quarterly reporting periods, and elections -- will have consequences that linger into geological time. Yet these decisions must be made under conditions of sometimes-profound uncertainty. The geological record of past environmental changes is a key resource for testing the models used to make future projection. But this resource, too, is riveted by uncertainty; it is noisy, diverse, and full of gaps.

My research focuses on using statistical approaches, primarily Bayesian in nature, to understand this record and apply it to test and improve models of future global change. Bayesian statistics, simply put, provides a formal methodology for updating estimates of the likelihood of different hypotheses about nature of Earth system using diverse observational or proxy data. Complementing these geohistorical investigations, my research group also explores how humanity’s uncertain climate impacts can be incorporated into climate change mitigation and adaptation decision-making. Just as Bayesian approaches provide a natural way for interpreting uncertainty and combining different data source about the past, they also provide a natural framework for interpreting uncertainty within and integrating diverse constraints into projections of future risks and costs.

## Bayesian Earth history

Though rarely identified by name, Bayesian analysis has deep roots in Earth history. T.C. Chamberlain’s method of multiple working hypotheses, which he presented in Science in 1890 and which involves guiding research through simultaneous consideration of several possible explanations of observed phenomena, is qualitatively Bayesian. But the application of the quantitative methods of the Bayesian revolution of the last couple decades to Earth history is quite new. Two areas of particular interest in my own research are the inference of changes in ancient ice sheets from paleo-sea level records and constraining the planet’s climate sensitivity from paleo-temperature and paleo-carbon dioxide records.

### Sea level and ice sheet volume in the geological record
{: .no_toc}

Ice sheets have waxed and waned throughout Earth history in response to changes in temperature and insolation, and for most of geologic time sea level proxies provide our best guide to their behavior. When interpreting sea level records, whether observational or proxy-based, it is critical to be aware of the difference between local sea level and mean global sea level (GSL). The latter is almost linearly related to changes in ice sheet volume; the former, however, is influenced by a range of factors, including ocean dynamics and changes in Earth’s gravitational field, rotation, and crustal and the mantle deformation associated with the redistribution of mass between land ice and the ocean (e.g., [Kopp et al., 2010](/papers/pubs/Kopp2010_postprint-sealevel.pdf)). These factors complicate inference of GSL from records; without uniform geographic coverage, averaging local records does not necessarily produce an unbiased estimate of GSL. But because the sea level patterns caused by melting different ice sheets differ, these factors may also make it possible to infer how much ice was lost from different ice sheets.

[Kopp et al. (2009)](/papers/pubs/Kopp2009-LIGSealevel.pdf) took a first step down this road, applying a Bayesian framework to reduce bias in the estimates of GSL during the Last Interglacial stage (LIG; ~130-115 thousand years ago). During the LIG, polar temperatures were comparable to those expected to accompany 1-2°C above pre-Industrial levels of future global warming. Taking into account uncertainties in the interpretation of geological sea level proxies, the ages of geological sea level proxies, crustal thickness, and mantle viscosity, we conditioned a prior probability distribution for sea level based upon a model of key geophysical processes with a geographically wide spread database of sea level proxies. We found a 95% probability that GSL during the LIG peaked at least 6.6 m higher than today, a 67% probability that it exceeded 8.0 m, and a 33% probability that it exceeded 9.4 m.

Subsequent analysis ([Kopp et al., 2013](http://mss3.libraries.rutgers.edu/dlr/showfed.php?pid=rutgers-lib:39293)) found a 95% probability that a GSL fall followed by a subsequent GSL rise occurred in the middle of Last Interglacial, with a 67% probability that the swing exceeded 4 m; it also a found a 95% probability that the maximum rate of transgression during this swing was less than 11 m/ky. These paleo-rates inform our expectations about the rate of ice sheet response to modest levels of future warming.

We are now working to go beyond GSL estimates, to the attribution of ice loss during the LIG. The key challenges involved are algorithmic: minimizing assumptions of normality, which can lead to unreasonable projections of negative ice sheet volumes, and displacing Monte Carlo sampling with approximation approaches, which will accelerate the analysis so as to enable use of larger data sets and a broader range of sensitivity tests. 

One key question is the relative importance of deterministic and stochastic drivers in controlling ice sheet behavior. At the scale of Quaternary glacial-interglacial cycles and the associated >100 m swings in mean global sea level (GSL), there is little doubt of a causal linkage between insolation- and greenhouse gas-driven changes in climate and changes in ice sheet volume and sea level. But whether a similar causal relationship can explain the differences (<~10 m GSL) between interglacials, or whether such differences are primarily the product of the inherent stochasticity of the cryosphere, is far less clear: If the Earth were to experience again the insolation and greenhouse gas forcing history that characterized the last 25 thousand years ago, would we expect the ice sheets and sea level to end up in their current configuration? Or might we expect a few meters’ discrepancy in GSL? If the former, then a characterization of the relationship between forcing and ice sheet extent can directly inform long-term projections of future ice sheet changes; if the latter, then a characterization of past changes provides a measure of the stochasticity that a skillful process-based model of ice sheet changes should reproduce.

To investigate the roles of deterministic and stochastic processes, we are extending our analysis to additional warm periods: other Quaternary and (data permitting) Pliocene warm periods, for example. In parallel. we are also tackling other questions related to Quaternary sea level history, such as the estimation of total ice volume during the Last Glacial Maximum (~25 thousand years ago) and the attribution of ice sheet changes during Meltwater Pulse 1A (~14.7-14.2 thousand years ago). These approaches have also inspired a fresh look at observational and recent geological sea level records, searching for the fingerprints of Greenland and Antarctic melt in the twentieth century tide-gauge record of sea level and the geological record of the Common Era.

### Geological constraints on climate sensitivity
{: .no_toc}

Climate sensitivity – the response of global mean temperature to climate forcing – has many parallels with the sensitivity of ice sheet and sea level to warming. Paleo-constraints are needed to validate long-term climate models, yet the proxies for both temperature and forcing are diverse and noisy. In the Cenozoic record, local temperature estimates come from geochemical proxies including oxygen isotopes, Mg/Ca ratios, lipids, and pollen. Climate models can help relate local temperatures to global mean temperature. Prior to the ice core record, carbon dioxide concentration estimates must be derived from proxies such as the abundance of leaf stomata, boron isotopes in carbonates, and the carbon isotopic composition of alkenones. Overall carbon isotope mass balance provides additional constraints. The challenge of fusing these diverse data sources is well suited to Bayesian hierarchical modeling. Although some recent efforts have sought to compile paleo-CO2 and paleo-temperature constraints and to draw inferences about climate sensitivity from them, none have sought to track uncertainty consistently through the entire pathway from proxy observations to climatic inference.

## Climate change decision-making under uncertainty

Projections of the Earth’s response to human activity and of the effects of those responses on human beings are inherently uncertain. Climate change integrated assessment research focuses on joining natural and social science together to inform decisions about responses to climate change. Since humans are generally bad judges of risks that play out over an extended period of time, integrating probabilistic projections into decision frameworks can play a crucial role in policy deliberation about interactions between humans and the Earth system. My work in this area is two-fold: (1) constructing probabilistic sea level rise projections that can be embedded in a risk analysis framework to inform coastal adaptation decisions, and (2) integrating probabilistic impact projections into climate change benefit-cost analyses like those used to guide U.S. regulatory policy.

### Informing sea level projections with the historical record
{: .no_toc}

While, as described above, the Quaternary and pre-Quaternary record are well suited for investigating the steady-state response of the cryosphere to different forcings and thus potentially for inferring cryospheric evolution on multi-century timescales, but they lack the temporal resolution to inform inferences about nearer-term responses. A parallel decomposition of Common Era sea level change could, however, be useful in this regard.

Previous researchers have constructed semi-empirical sea level models, in which a statistical relationship between sea level change and temperature during the Common Era is projected forward to infer the sea level response to anthropogenic global warming. These models are viewed skeptically by many because they use a relationship derived during a period when the cryosphere was relatively stable to infer changes during a period when the Greenland and Antarctic ice sheets may undergo large-scale change. In general, semi-empirical models project faster rates of sea level rise than bottom-up models that undertake the still extremely challenging task of physically modeling the cryospheric response to warming.   

A Common Era sea level record decomposed into its individual components by leveraging the spatial fingerprints of different sources of sea level change will enable a hybrid approach: a bottom-up semi-empirical sea level model that allows incorporation not just of the historically observed relationship between warming and temperature response but also prior physical expectations about the response of different contributors. Such an approach would combine the strengths of both semi-empirical and bottom-up models: it would be grounded in observational record while being cognizant of the mechanisms underlying the sea level response. Being grounded in mechanisms, it would, unlike semi-empirical models, allow for regional, not just global, sea level projections. Being almost as computationally simple as extant semi-empirical models, it would be easily amenable to Monte Carlo analysis and therefore to a fully probabilistic risk assessment.

Sea level projections alone are insufficient to guide regional decision-making; full assessments must include other natural factors that control coastal flooding, such as storm surge, as well as human factors such as the vulnerability of exposed infrastructure and the consequences of flooding. Risk tolerance differs for shore homes and for nuclear power plants. A secondary goal of my group’s sea level projection research is to embed these probabilistic projections in infrastructure risk assessment tools that can help policy-makers make judgments about capital investments and coastal adaptation in vulnerable areas.

### Benefit-cost analysis of climate change policy under uncertainty
{: .no_toc}

In a world increasingly stressed by climate change, wise adaptation, mitigation and potentially geoengineering decisions require balancing the costs and risks of policies against the highly uncertain costs and risks of climate change. Integrated assessment models (IAMs), which couple together representations of human and natural systems, are potentially a key tool in such assessments, but to be useful for decision-making purposes, they must be consistent with the best-available underlying science and reflect the uncertainty in this science. For a risk-averse population, underestimating uncertainty leads to insufficiently stringent policies (e.g., [Kopp et al., 2012](http://dx.doi.org/10.5018/economics-ejournal.ja.2012-13); [Kousky et al., 2011](http://dx.doi.org/10.5018/economics-ejournal.ja.2011-21)).

The U.S. government currently uses the "social cost of carbon" (SCC), an economic measure of the increase in social welfare associated with reduced carbon dioxide emissions, in benefit-cost analysis of regulations that mitigate emissions. In 2009-2010, I was involved in the White House-led process that arrived at the first government-wide SCC estimates; these estimates have subsequently been employed in a range of energy efficiency and air pollution regulatory impact assessments. But these estimates, and all the IAMs currently capable of performing global benefit-cost analyses, suffer from significant limitations and over-simplifications (see [Kopp & Mignone, 2012](http://dx.doi.org/10.5018/economics-ejournal.ja.2012-15), for a review). These include, among other limitations, a failure to incorporate recent empirical estimates of climate change impacts and the absence of natural and human system stochasticity. My research group and our collaborators are pursuing research to address these limitations.

To improve climate change damage estimates, we are developing a framework for geographically downscaling the global climate projections of reduced form IAMs, and we are using these downscaled climate projections to project impacts based on econometrically-identified historical relationships between temperature and economic factors such as agricultural and labor productivity. While past performance is certainly no guarantee of future results, projections based on historical relationships are more reliable than projections based on models that fail to reproduce historical relationships. For example, the observed negative relationship between temperature trends and productivity of maize and wheat should led to skepticism about IAMs that project positive agricultural benefits for low levels of warming. 

The role of stochasticity in climate change impacts is illustrated by the sea level example raised previously. Just as coastal flooding depends upon the juxtaposition of sea level rise and storm surge, so many climate change impacts depend upon the juxtaposition of a changing baseline climate and extreme weather events. The agricultural impacts of warming, for example, will be most severe in years during which a stochastically warm heat wave is juxtaposed upon a hotter base climate; in many places, warming will serve to make severe crop loss years more frequent. The associated welfare effects will likely be more severe when such impacts come during an economic low than during an economic high. My research group is working to assess the significance of such stochasticity in assessing the social cost of carbon. For regions with risk averse population that do not have robust governments and insurance markets, we expect the welfare effects of climate damages delivered through weather shocks to be significantly more severe than the same damages when viewed only through their average effects.

Social cost of carbon estimates also need to take into account policy uncertainty. Ongoing research is examining the role of uncertain expectations about mitigation reciprocity among nations and of “punctuated equilibrium” effects in environmental policy making.

## Other projects in deep time

### An "Appalachian Amazon" in the early Eocene: A magnetofossil record of stormier times?
{: .no_toc}

Because iron, the fourth-most abundant element in Earth’s crust, is redox-active under surface conditions, it is a critical element in Earth surface processes: both a key player in many abiotic reactions and an essential nutrient for living organisms. The bio-availability of iron is a product of environmental conditions; through its effects on biological productivity, it is also a feedback. Changes in the sedimentary record of iron cycling therefore reflect broader biogeochemical and climatic changes.

Our current research in this area focuses on understanding the paleoenvironmental implications of a radical change in sedimentary iron biogeochemistry in the mid-Atlantic U.S. during the Paleocene-Eocene Thermal Maximum (PETM), a severe global warming event that occurred 55 million years ago. [Kopp et al. (2007)](http://resolver.caltech.edu/CaltechAUTHORS:KOPpal07) and [Schumann et al. (2008)](http://resolver.caltech.edu/CaltechAUTHORS:20091205-144532263) found that a clay layer deposited during the PETM in the Salisbury Embayment (which stretches from New Jersey to Virginia) recorded the unusually rich growth of magnetotactic bacteria and of other unique and presumptively eukaryotic iron biomineralizing organisms. Combined with knowledge about the ecological distribution of modern magnetotactic bacteria, this finding suggests that biogeochemical changes during the PETM led to the development of enlarged suboxic zones in the sediments of the Atlantic Coastal Plain.

Because meter-scale suboxic zones occur today within the mobile mud belts of tropical river-dominated continental shelves, such as the Amazon Shelf, we hypothesize that sedimentological and hydrological changes during the PETM fostered the development of analogous conditions on the Eastern seaboard of North America. By mapping the distribution of magnetofossils and the PETM clay, [Kopp et al. (2009)](http://resolver.caltech.edu/CaltechAUTHORS:SCHpnas08) found support for an Appalachian-fed, Amazon-like river system located around the modern Potomac or Susquehanna rivers. The development of this river system may be linked to changes in temperature, precipitation, rainwater acidity, and storminess.

Key next steps in this research area focus on testing the “Appalachian Amazon” hypothesis by examining Paleogene geochemical and sedimentological changes across the Salisbury Embayment, expanding the magnetofossil database to other regions and other times and on better understanding the preservation of magnetofossils in modern analog environments.

### The rise of oxygen and the co-evolution of life and climate
{: .no_toc}

In the Archean eon, three billion years ago, Earth's atmosphere was free of oxygen. This absence is reflected in numerous proxies, particularly the record of mass-independent fractionation of sulfur isotopes. By two billion years ago, in the middle of the Paleoproterozoic era, many proxies suggest that oxygen had built up to a small but significant level in the atmosphere. Aside from the origin of life itself, the transition from the anoxic Archean to the oxic Proterozoic is the most radical change to occur in the history of the Earth system.

While all geohistorical data is sparse, the Precambrian eons are times of particular sparsity. In light of this sparsity, Chamberlin’s method of multiple working hypotheses becomes particularly important. While many researchers believe the transition from an anoxic world to an oxic world  occurred gradually, Joe Kirschvink (Caltech) and I have suggested instead -- based on a critical analysis of the available data, with a strong dose of caution applied to the use of uniformitarian interpretations in such a radically different world -- that the transition occurred rapidly ([Kopp et al., 2005](http://resolver.caltech.edu/CaltechAUTHORS:KOPpnas05); [Kirschvink and Kopp, 2008](http://resolver.caltech.edu/CaltechAUTHORS:KIRrstb08)). We proposed that the Makganyene Snowball Earth event, which occurred at ~2.3 billion years ago, was a direct consequence of the transition. During the Snowball Earth, the presence of which is indicated by glacial deposits with low paleolatitudes from the Transvaal Supergroup in South Africa, the entire planet may have been sheathed in ice for tens of millions of years.

Simple biogeochemical flux modeling suggests that, if the Archean Earth was kept warm by a methane greenhouse, then the evolution of oxygenic photosynthesis could have triggered a Snowball Earth event on a time scale as short as about a million years ([Kopp et al., 2005](http://resolver.caltech.edu/CaltechAUTHORS:KOPpnas05)). Rather than a gradual transition, the anoxic-to-oxic transition, triggered by a chance evolution occurrence, may have been a catastrophic event: the world's first biologically-caused climate disaster. This hypothesis is an end-member hypothesis, but it is testable and serves to motivate research in this critical interval in Earth history.
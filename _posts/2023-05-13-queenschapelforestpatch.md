---
title: "Queens Chapel Forest Patch"
permalink: /issues/queenschapelforestpatch/
excerpt: "Four Acres of Natural Tree Canopy"
author_profile: false
header:
  overlay_image: /assets/images/modelcities/forest.jpg
  overlay_filter: rgba(127, 127, 127, 0.5)
  caption: "[Paper Street Forest Patch](/assets/images/modelcities/forest.jpg)"
categories: active development 5c02
# toc: true
toc_label: "Page Contents"
toc_icon: "bullseye"
toc_sticky: true
last_modified_at: 2023-09-24T22:51:18
---
<div id="development-map" class="map-container"></div>
This community concern is in 5C02.
{: .notice--warning}

## tl;dr
- **The Queens Chapel Forest Patch is an unofficial name for a patch of natural forested area** located at the confluence of 20th St NE, Evarts St NE, and Queens Chapel Rd NE
- **The forested area is made up of a few DC-owned, DGS-controlled parcels, as well as land designated for streets** that were never built; these are so-called "[paper streets](https://wamu.org/story/20/02/17/paper-streets-arent-real-but-they-can-lead-to-big-problems-for-developers/)"
- **Along with the Langdon Park Forest Stewards, I'm advocating for the protection and sustainable activation** of this forest patch, similar to the efforts undertaken in the Langdon Park Forest Patch
- **Volunteer stewardship in the two-acre [Langdon Park Forest Patch](https://biologistsoup.wordpress.com/2022/10/04/a-little-more-about-langdon-forest-patch/) was facilitated by the $25k investment** in a 680-foot unpaved trail constructed through the forest by CaseyTrees, so **the projected cost to do the same in the Queens Chapel patch would be $50k**
- **Prospects for DDOT trail-building have been considered**, but it's unlikely any such project could occur soon given archeological concerns in the forest and the need for DDOT to build a paved and ADA-accessible trail, a far costlier capital project.
- **The QCFP has also been nominated for conservative easement**, a process that would indefinitely protect the entirety of the forest from any future development.

## More Forest Info
Thanks to Allison Clausen and Delores Bushong, Langdon Park Forest Stewards, for helping with the below.
{: .notice--info}

The Queens Chapel Forest Patch covers the entirety of two undeveloped DC-owned plots, part of the plot containing the Model Cities and Office of Aging facilities, and four paper street segments (20th, Douglas, Channing, and Park Ave). The Model Cities building and Office of Aging facilities are to the west, with a shuttle parking facility nestled in the middle of the forest patch (built, as far as I've been able to determine, sometime in the 00's). [Langdon Elementary School](https://www.langdonelementaryschool.org/) is across Evarts to the north, and [The Ionia Whipper Home](http://ioniawhipperhome.org/about-us/) (a shelter for families experiencing homelessness) and a few detached houses are around Park Ave to the south.

[![Real Property Map](/assets/images/modelcities/plats.png)](/assets/images/modelcities/plats.png)
<p class="caption">Platted land, snapshotted from DC's <a href="https://dcgis.maps.arcgis.com/apps/webappviewer/index.html?id=9a5c11c11dd347cc9c05d64499cc98ee">Real Property Map</a></p>

The forest patch is currently the site of frequent dumping, is minimally maintained, and is surrounded by uninviting No Trespassing/Dumping signs.

[![DC Government Property](/assets/images/modelcities/no-trespassing.png)](/assets/images/modelcities/no-trespassing.png)
<p class="caption">DC Government Property sign at the site</p>

The forest patch sits on a slope and absorbs/filters stormwater that would otherwise flow to the PDR Zones at the bottom of the hill, ultimately reaching Hickey Run and then the Anacostia. It absorbs particulate matter and noise pollution from the PDR zones and nightlife establishments to the south (that would otherwise affect the seniors and students). It cools the air, offsetting the area's extreme [heat island effect](https://www.dcpolicycenter.org/publications/urban-heat-islands/). It helps towards [DC's 40% canopy goal](https://storymaps.arcgis.com/stories/62580ba81fc34563b1bae8e8416ee16d) and plays a part in [slowing climate change](https://www.rainforest-alliance.org/insights/how-forests-fight-climate-change/). It also provides habitat for migratory species and supports DC's ecosystem. Research also shows living near trees makes people [happier](https://www.mdpi.com/1660-4601/15/12/2804) and [healthier](https://www.washingtonpost.com/news/energy-environment/wp/2015/07/09/scientists-have-discovered-that-living-near-trees-is-good-for-your-health/).

[![Forest Patch](/assets/images/modelcities/forest.jpg)](/assets/images/modelcities/forest.jpg)
<p class="caption">Forest patch, looking north from Park Ave NE</p>

All of this is particularly important here in Ward 5, which has outsized share of DC's PDR zones and has experienced [dramatic canopy loss in recent years](https://caseytrees.org/get-involved/conservation-easements/).

Efforts could conceivably be made to clean up, nurture, and protect this forest patch, while making it available to visitors as with the recently built 680-foot Langdon Park Forest Patch trail. If built, such a trail could allow community volunteers to freely enter and assess tree health, plant new trees, remove invasive species, and otherwise maintain the forest patch and set it up to thrive.

## Name
I've unofficially called this forest patch the **Douglas Street Forest Patch** and the **Paper Street Forest Patch**; **South Langdon Forest Patch** has also been used by neighbors engaged in advocating for the patch. Folks have since consolidated behind calling it the **Queens Chapel Forest Patch**, after the [slaveholding Queens family that established their family chapel](https://bygonebrookland.com/2014/07/06/just-where-was-queens-chapel/) nearby in the 18th century.

*[DPR]: DC Department of Parks and Recreation
*[FEMS]: DC Fire and Emergency Medical Services
*[DCRA]: DC Department of Consumer and Regulatory Affairs
*[DDOT]: DC Department of Transportation
*[E26]: DC FEMS Engine Company 26
*[RFP]: Request for Proposal
*[PDR]: Production, Distribution, and Repair

<script>
var map = L.map('development-map',  {
      zoomSnap: 0.25
  }).setView([38.92331221130734, -76.97628769922949], 17.5);
  L.tileLayer('https://{s}.tile.openstreetmap.org/{z}/{x}/{y}.png', {
      maxZoom: 19,
      attribution: '© OpenStreetMap'
  }).addTo(map);

  var polygon = L.polygon([[38.924159526531064, -76.97599908296874], [38.9231215639874, -76.97756196724863], [38.92240557281122, -76.97771444376374], [38.92242251943143, -76.9760753212263], [38.92339270668859, -76.97540006808794], [38.924159526531064, -76.97599908296874]], {color: 'red'}).addTo(map);
</script>

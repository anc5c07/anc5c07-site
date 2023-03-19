---
title: "22nd and Franklin mudslide"
permalink: /issues/22nd-franklin-modslide/
excerpt: "a church and a mudslide"
author_profile: false
header:
  overlay_image: /assets/images/22ndfranklin/muddy-pre-fix.jpg
  overlay_filter: rgba(127, 127, 127, 0.5)
  caption: "[Franklin looking west on 1/17/23](/assets/images/22ndfranklin/muddy-pre-fix.jpg)"
categories: active traffic-safety problematic-construction 5c07
# toc: true
toc_label: "Page Contents"
toc_icon: "bullseye"
toc_sticky: true
last_modified_at: 2023-03-19T21:38:00
---
<meta name="format-detection" content="telephone=no"/>
<div id="development-map" class="map-container"></div>

## tl;dr
- Since early 2021, land-disrupting construction at the church at 22nd and Franklin has led to deteriorating land and sidewalk conditions.
- A number of citations have been issued over the years, and DDOT has currently put the sidewalk back together
- However, there are still risks to mitgate to come to a final stable solution
- There are also a number of sidewalk issues related to both sides of Franklin here

## Current Status
There is a hearing scheduled for DOEE enforcement on 5/16/2023. There is an additional case by DCRA/DOB pending judge assignment after the church entered a `deny` plea. While these hearings are pending, Kelley Cislo from Councilmember McDuffie's office is working with DLCP on options regarding the operating capability of the church while these cases are ongoing

In response to my own Illegal Construction Inspection request (case number `Z4N-PNN7U`) and subsequent photographic evidence of work being done sent to DOB on 2/22/2023, an additional stop-work order was issued by DOB on 2/23/2023.

There is ongoing effort at DDOT to install a new sidewalk on the north side of the block here, but there is extra work due to the proximity to federal land (containing Langdon Park).

## In the Media
Ms. Vicki Moore, whose home is experiencing foundation issues due to the ground disruption, gave an interview for a story by [NBC4 news](https://www.nbcwashington.com/news/local/its-a-mess-mudslide-next-door-threatens-dc-residents-home/3163475/).

## Timeline

I'm continuing to collect photos and events for this timeline; if you have any to share, send them to me!
{: .notice--info}

|time|status|references|
|---|---|---|
|early 2021|Ground disrupting construction begins in the area||
|September 2021|The wall and sidewalk are relatively unharmed|<img src="/assets/images/22ndfranklin/9-2021-streetview.jpg" width="200px"/><br/>[Google Street View](https://www.google.com/maps/@38.9256014,-76.9738305,3a,75y,220.21h,73.93t/data=!3m7!1e1!3m5!1s71kO-PcThuo8O4HCxxM2VA!2e0!5s20210901T000000!7i16384!8i8192)|
|February 2022|The retaining wall and hill begin collapsing into the sidewalk over time|<img src="/assets/images/22ndfranklin/2-2022-aarondenutweet.jpg" width="200px"/><br/>[tweet from 2/17/22](https://twitter.com/AaronDeNu/status/1494443842552184833)|
|March 2022|DDOT erected a traffic cone boundary on the site|<img src="/assets/images/22ndfranklin/3-2022-aarondenutweet.jpg" width="200px"/><br/>[tweet from 3/6/22](https://twitter.com/AaronDeNu/status/1500606095097798659)|
|April 2022|DDOT's Public Space Inspector issued a corrective notice, and a proper Public Space Construction Permit was issued to retaining wall work||
|June 2022|The retaining wall was largely gone and the sidewalk completely compromised.|<img src="/assets/images/22ndfranklin/6-2022-streetview.jpg" width="200px"/><br/>[Google Street View](https://www.google.com/maps/@38.9255702,-76.9738167,3a,75y,220.21h,73.93t/data=!3m7!1e1!3m5!1sZFHZmVhsBqAj-FO7-9U2NA!2e0!5s20220601T000000!7i16384!8i8192)|
|late 2022|the retaining wall was rebuilt at some point since June 2022||
|January 2022|the sidewalk remained in disrepair|<img src="/assets/images/22ndfranklin/1-2023-vjtweet.jpg" width="200px"/><br/>[tweet from 1/17/23](https://twitter.com/VJKapur/status/1615456860752203776)|
|February 2023|localized fixes performed on sidewalk|<img src="/assets/images/22ndfranklin/2-2023-vjtweet.jpg" width="200px"/><br/>[tweet from 1/22/23](https://twitter.com/VJKapur/status/1615456860752203776)|
|February 2023|ground disruption and runoff remain problems|<img src="/assets/images/22ndfranklin/2-2023-vjtweet-2.jpg" width="200px"/><br/>[tweet from 1/22/23](https://twitter.com/VJKapur/status/1628513850839470081)|


*[DOB]: DC Department of Buildings
*[DOEE]: DC Department of Energy & Environment
*[DCRA]: DC's Department of Consumer and Regulatory Affairs (split into DOB and DLCP)
*[DLCP]: DC's Department of Licensing and Consumer Protection

<script>
var map = L.map('development-map',  {
      zoomSnap: 0.25
  }).setView([38.925584375788354, -76.97315317893013], 18.5);
  L.tileLayer('https://{s}.tile.openstreetmap.org/{z}/{x}/{y}.png', {
      maxZoom: 19,
      attribution: '© OpenStreetMap'
  }).addTo(map);

  var polygon = L.polygon([[38.92536043535926, -76.97404377155027], [38.92552288934426, -76.97403955297732], [38.92552288934426, -76.97368519284896], [38.92535387155406, -76.97368941142193], [38.92536043535926, -76.97404377155027]], {color: 'red'}).addTo(map);

  //var polygon = L.polygon([[38.92566784207662, -76.97415096071829], [38.92566992873257, -76.97225463887897], [38.92563028225906, -76.97225732108807], [38.92563028225906, -76.9741214564181], [38.92566784207662, -76.97415096071829]], {color: 'orange'}).addTo(map);

  //var polygon = L.polygon([[38.92552594932813, -76.97368693854261], [38.92545291618519, -76.97368962075173], [38.925446656198, -76.97225463887897], [38.92552803598826, -76.97231364747933], [38.92552594932813, -76.97368693854261]], {color: 'yellow'}).addTo(map);
</script>

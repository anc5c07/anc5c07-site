---
title: "Langdon Park Rec Center Modernization"
permalink: /issues/langdonrec/
excerpt: "a big opportunity for a new facility"
author_profile: false
header:
  overlay_image: /assets/images/langdon-park/rec-center.jpg
  overlay_filter: rgba(127, 127, 127, 0.5)
  caption: "[Langdon Park Rec Center](/assets/images/langdon-park/rec-center.jpg)"
categories: development active
last_modified_at: 2023-11-02T16:25:16
---
<div id="development-map" class="map-container"></div>

## tl;dr
- **The Langdon Park Rec Center** (also referred to variously as Langdon Park Community Center or Langdon Park East Recreation Center) **is a facility located at 2901 20th St NE within Langdon Park**
- **The building has likely not seen significant modernization since its 1966 construction**, and its age is fairly apparent
- **It's slated for modernization** which will likely involve razing the existing structure and constructing a modern one
- **The community engagement process is kicking off** with a [meeting on-site at 6pm on Thursday November 2nd](https://langdoncm.splashthat.com/), and [a DPR project page](https://dgs.dc.gov/page/langdon-park-community-center)
- **I'm [beginning to formulate my priorities](#priorities)** and would love to hear yours!

## Priorities

[![Gymnastics at Langdon Rec](/assets/images/langdon-park/gymnastics.jpg)](/assets/images/langdon-park/gymnastics.jpg)
<p class="caption">Langdon Rec's amazing gymnastics facility, set up in Spring 2023</p>

From my perspective and through my conversations to date, present priorities I plan to push are:
- **building amazing and purpose-built spaces for all-ages children's activities** inside and out of the rec center; the recently (re-)introduced gymnastics classes and basketball league games have been a delightful increase in utilization and vibrancy at the park
- **building a taller structure rather than expanding the building footprint** to preserve the forestry behind the building, our amazing skate park, and the east-west passage at the park's nadir (this is separated, but related, to the [need to improve the safety of the 20th St crossing](https://anc5c07.com/issues/20thst/#envisioning-the-new-crosswalk) in front of the rec center)
- **making sure that east-west passage is also made more accessible to users of rolling mobility devices;** presently, access by stroller, wheelchair, or bike requires looping around to the parking lot driveway (access from 20th St to the far east side of the park through the park would also require going through the dog park area)
- **reclaiming parts of the east side of the park from vehicular traffic,** including the long driveway running between the basketball courts and forestry to enable a very small number of vehicle spaces in the middle of the park; this asphalt is taking up space better left to other uses, and permitting drivers to bring cars into the park raises a lot of safety and livability concerns in one of our few car-free spaces
- **improving the water drainage and ecological resiliency of the surrounding area of the park:** Langdon Park is built on buried/piped waterways, and increased rainfall (plus decaying older infrastructure and a lot of impermeable asphalt) makes water issues a common problem for park usage after rainfall, and a runoff issue for the Hickey Run Watershed generally. There should be capacity to add funding to the project for elective watershed improvements through the [Clean Water Construction Grant Program](https://doee.dc.gov/service/cwc) (CWC).

I will continue to refine these priorities, as well as capturing controversy/debate over community priorities, as the process continues. I would love to determine some elements that combine accessibility, watershed, and traffic safety needs, as there should be a lot of common cause among these priorities.

## Funding and Scope
The FY24 budget contains nearly $25M in funding for this project. For context, the Edgewood Rec Center development (including at least the athletic fields) [was an $18M project](https://dpr.dc.gov/edgewood). The DPR project page lists the current budget as $31M.

While getting the best possible facility is the highest priority, there appears to be some possibility of DPR reallocating some of these funds around the park for other capital improvements if the community advocates for it. The first stage of the project is assessing the scope of work.


<script>
var map = L.map('development-map',  {
      zoomSnap: 0.25
  }).setView([38.9268068249159, -76.97582807825951], 18.5);
  L.tileLayer('https://{s}.tile.openstreetmap.org/{z}/{x}/{y}.png', {
      maxZoom: 19,
      attribution: '© OpenStreetMap'
  }).addTo(map);

  var polygon = L.polygon([[38.92691815660863, -76.97611953256383], [38.926981968597616, -76.97555582154408], [38.92667920056542, -76.9755662929562], [38.92668191597955, -76.9761212777992], [38.92691815660863, -76.97611953256383]], {color: 'red'}).addTo(map);
</script>
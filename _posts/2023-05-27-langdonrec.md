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
last_modified_at: 2024-02-20T21:51:14
---
<div id="development-map" class="map-container"></div>

## tl;dr
- **The Langdon Park Rec Center** (also referred to variously as Langdon Park Community Center or Langdon Park East Recreation Center) **is a facility located at 2901 20th St NE within Langdon Park**
- **The building has likely not seen significant modernization since its 1966 construction**, and its age is fairly apparent
- **It's slated for modernization** which will likely involve razing the existing structure and constructing a modern one
- **The community engagement process has kicked off** with a [November 2 meeting](#112-meeting), and [a DPR project page](https://dgs.dc.gov/page/langdon-park-community-center)
- **I'm [beginning to formulate my priorities](#priorities)** and would love to hear yours!
- **You can submit feedback to DPR** [using this form](https://forms.office.com/Pages/ResponsePage.aspx?id=8Unkj5SLt0-ZBm-Tnagtc_myyzzTfjZAu3mqLOlcVz9UOEpXWFFDTzZVVVlYS0JZRDQwQ0NBNUJWNi4u) (select "Langdon" for the first question).

## Priorities

[![Gymnastics at Langdon Rec](/assets/images/langdon-park/gymnastics.jpg)](/assets/images/langdon-park/gymnastics.jpg)
<p class="caption">Langdon Rec's gymnastics facility, set up in Spring 2023</p>

From my perspective and through my conversations to date, present priorities I plan to push are:
- **proper consideration of delivery timeline and expected unavailability of the building;** nearby Theodore Hagans rec center in Fort Lincoln remains indefinitely closed after an indefinitely delayed modernization; we should seek to understand and track DPR/DGS's timeline and risks to delivery to avoid a repeat of this scenario
- **building state-of-the-art and purpose-built spaces for all-ages children's activities** inside and out of the rec center; the recently (re-)introduced gymnastics classes and basketball league games have been a delightful increase in utilization and vibrancy at the park (while not immediately in scope, we should certainly be mindful that the value of this $31M investment also depends on programming operations to better meet the demand for these youth activities than we do today)
- **building a taller structure rather than expanding the building footprint** to preserve the forestry behind the building, our amazing skate park, and the east-west passage at the park's nadir (this is separate, but related, to the [need to improve the safety of the 20th St crossing](https://anc5c07.com/issues/20thst/#envisioning-the-new-crosswalk) in front of the rec center)
- **making sure that east-west passage is also made more accessible to users of rolling mobility devices;** presently, access by stroller, wheelchair, or bike requires looping around to the parking lot driveway (access from 20th St to the far east side of the park through the park would also require going through the dog park area)
- **reclaiming parts of the east side of the park from vehicular traffic,** including the long driveway running between the basketball courts and forestry to enable a very small number of vehicle spaces in the middle of the park; this asphalt is taking up space better left to other uses, and permitting drivers to bring cars into the park raises a lot of safety and livability concerns in one of our few car-free spaces
- **improving the water drainage and ecological resiliency of the surrounding area of the park:** Langdon Park is built on buried/piped waterways, and increased rainfall overwhelms this old (and decaying) infrastructure. Impermeable surfaces also prevent the ground from absorbing this water and naturally filtering it through dirt; it instead rolls over the asphalt picking up toxins/chemicals/trash and pulling it into the Hickey Run Watershed which flows into the Anacostia River. There should be capacity to add funding to the project for elective watershed improvements through the [Clean Water Construction Grant Program](https://doee.dc.gov/service/cwc) (CWC) which is set up to improve this situation during capital projects such as this one.

I will continue to refine these priorities, as well as capturing controversy/debate over community priorities, as the process continues. I would love to determine some elements that combine accessibility, watershed, and traffic safety needs, as there should be a lot of common cause among these priorities.

## Funding and Scope
The FY24 budget contains nearly $25M in funding for this project. For context, the Edgewood Rec Center development (including at least the athletic fields) [was an $18M project](https://dpr.dc.gov/edgewood). The DPR project page lists the current budget as $31M. During FY24 budget discussions, Mayor Bowser's summary materials listed it as $25M, but $6M was added in late in the process due to the escalating costs of constructing a project like this.

While getting the best possible facility is the highest priority, there appears to be some possibility of DPR reallocating some of these funds around the park for other capital improvements if the community advocates for it. The first stage of the project is assessing the scope of work.

A rough estimate thrown around for constructing a rec center building is $1k/SF. The current building is 22,206 SF, so just a straight rebuild in place is already $22M of the budget. Adding an additional floor would likely consume the whole budget.

## 11/2 meeting
At the 11/2 meeting, folks were invited to put ideas on post-its on a board.

[![11/2 meeting idea board (left)](/assets/images/langdon-rec/nov2-leftboard.jpg)](/assets/images/langdon-rec/nov2-leftboard.jpg)
<p class="caption">11/2 meeting idea board (left)</p>

[![11/2 meeting idea board (right)](/assets/images/langdon-rec/nov2-rightboard.jpg)](/assets/images/langdon-rec/nov2-rightboard.jpg)
<p class="caption">11/2 meeting idea board (right)</p>

Most active discussion centered more on programming than the facility itself. Topics included:
- basketball games being too loud
- gymnastics and other classes being too hard to secure spots in
- the community center no longer having an open door and being available to the community

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
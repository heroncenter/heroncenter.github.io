---
layout: page
title: Events
description: 
image: 
permalink: /events/
imagefolder:
---

# Events

Experiences that Educate, Empower and Inspirit!
Live Performances, Open Mics for Creatives, Mindfulness, Workshops, Trainings, Seasonal Celebrations & More

<a class="btn btn-xl text-uppercase js-scroll-trigger" href="https://www.eventbrite.com/o/the-heron-center-83561553823">View Our Live Events</a>

<br />
<br />

# Past Events

{% include events-carousel.html %}

{%- if page.imagefolder -%} 
{% assign folder = page.imagefolder %}
{% include my-gallery.html folder = folder %}
{%- endif -%}

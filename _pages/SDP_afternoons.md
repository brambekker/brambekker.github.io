---
layout: page_no-navbar
title: Events of the Dutch SDP community
permalink: /sdp-community-events/
description: 
horizontal: false
---

## SDP Afternoons

<!-- Edit the events, talk titles and abstracts in _data/sdp_afternoons.yml -->
{% include sdp_events.html events=site.data.sdp_afternoons %}

{% if jekyll.environment == "production" %}
  <script data-goatcounter="https://brambekker.goatcounter.com/count"
        async src="//gc.zgo.at/count.js"></script>
{% endif %}
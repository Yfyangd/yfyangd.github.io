---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

<script>
 window.difyChatbotConfig = { 
  token: 'FLDVs1lMPmClxxJW'
 }
</script>
<script
 src="https://udify.app/embed.min.js"
 id="FLDVs1lMPmClxxJW"
 defer>
</script>

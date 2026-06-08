---
layout: default
title: "Latest Brief"
permalink: /latest/
---

<script>
  var url = "{{ site.posts.first.url | prepend: site.baseurl }}";
  if (url && url !== "{{ site.baseurl }}") {
    window.location.replace(url);
  }
</script>

<div style="text-align:center; padding: 3em 1em; font-family: monospace;">
  <p>Redirecting to the latest brief…</p>
  <p><a href="{{ site.posts.first.url | prepend: site.baseurl }}">
    {{ site.posts.first.title }}
  </a></p>
</div>

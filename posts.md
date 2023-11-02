---
layout: page
title: Posts
---


{% if page.background == "grey" or page.background == "gray" %}
<script>
document.getElementById("page-top").className="bg-light";
</script>
{% endif %}

{% include post-item.html %}

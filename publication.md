---
layout: default
title: Publication
---
{% include head.html %}
{% include nav.html %}

{% if page.background == "grey" or page.background == "gray" %}
<script>
document.getElementById("page-top").className="bg-light";
</script>
{% endif %}

{% include portfolio_grid.html %}




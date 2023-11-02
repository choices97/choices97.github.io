---
layout: page
title: Posts
---

{% include nav.html %}

{% if page.background == "grey" or page.background == "gray" %}
<script>
document.getElementById("page-top").className="bg-light";
</script>
{% endif %}

<br> <br> <br>

{% include post-item.html %}

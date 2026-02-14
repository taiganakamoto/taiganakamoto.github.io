---
layout: page
permalink: /en/publications/
title: Publications
nav: false
tabs: true
---

[日本語](/publications/)

[Google Scholar](https://scholar.google.com/citations?user=G3gsbSgAAAAJ)

{% tabs publications_en %}

{% tab publications_en Preprints %}
<div class="publications">
{% bibliography --query @*[pubtype=preprint]* %}
</div>
{% endtab %}

{% tab publications_en Papers %}
<div class="publications">
{% bibliography --query @*[pubtype=paper]* %}
</div>
{% endtab %}

{% tab publications_en Others %}
<div class="publications">
{% bibliography --query @*[pubtype=review]* %}
</div>
{% endtab %}

{% endtabs %}

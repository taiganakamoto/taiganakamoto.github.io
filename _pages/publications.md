---
layout: page
permalink: /publications/
title: Publications
nav: true
nav_order: 5
tabs: true
---

[English](/en/publications/)

[Google Scholar](https://scholar.google.com/citations?user=G3gsbSgAAAAJ)

{% tabs publications_ja %}

{% tab publications_ja プレプリント %}
<div class="publications">
{% bibliography --query @*[pubtype=preprint]* %}
</div>
{% endtab %}

{% tab publications_ja 論文 %}
<div class="publications">
{% bibliography --query @*[pubtype=paper]* %}
</div>
{% endtab %}

{% tab publications_ja 解説 %}
<div class="publications">
{% bibliography --query @*[pubtype=review]* %}
</div>
{% endtab %}

{% endtabs %}

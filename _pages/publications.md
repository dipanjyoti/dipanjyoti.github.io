---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<!-- Dipanjyoti Paul published his research findings in many conferences and Journals such as ICLR, Knowledge-Based Systems, Pattern Recognition, Expert Systems with Applications, IEEE Transactions on Computational Social Systems, Pattern Recognition Letters, ACM Transactions on Knowledge Discovery from Data etc. 


Total Citation: 197
h-index: 7

{% if site.author.googlescholar %}
  <div class="wordwrap">You can find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %} -->

<!-- {% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %} -->



<div class="publication-block">
  <!-- <h2>Publications</h2> -->
  <p>Dipanjyoti Paul published his research findings in many conferences and journals such as ICLR, Knowledge-Based Systems (KBS), Pattern Recognition (PR), Expert Systems with Applications (ESWA), IEEE Transactions on Computational Social Systems (TCSS), Pattern Recognition Letters (PRL), ACM Transactions on Knowledge Discovery from Data (TKDD), etc.</p>
  
  <div class="citation-stats">
    <p><strong>Total Citations:</strong> 198</p>
    <p><strong>h-index:</strong> 7</p>
  </div>

  {% if site.author.googlescholar %}
    <div class="google-scholar">
      <p>You can find my articles on <a href="{{site.author.googlescholar}}" target="_blank">my Google Scholar profile</a>.</p>
    </div>
  {% endif %}
</div>

<style>
.publication-block {
  border: 1px solid #ddd;
  padding: 20px;
  margin: 20px 0;
  border-radius: 5px;
  background-color: #f9f9f9;
}
.publication-block h2 {
  font-size: 24px;
  margin-bottom: 10px;
}
.citation-stats {
  margin: 10px 0;
}
.citation-stats p {
  margin: 5px 0;
}
.google-scholar {
  margin-top: 10px;
}
.google-scholar a {
  color: #007bff;
  text-decoration: none;
}
.google-scholar a:hover {
  text-decoration: underline;
}
</style>

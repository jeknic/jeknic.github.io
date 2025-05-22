---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
<span style="font-size: 25px"> <strong> 2025 </strong></span>
<!-- ## 2025 -->

<ul  style="font-size: 15px">
    <li>
        <a href="https://arxiv.org/abs/2505.15490"><strong>Collaborative Problem-Solving in an Optimization Game</strong></a><br>
        <em><strong>Isidora Jeknić</strong>, Alex Duchnowski and Alexander Koller</em><br>
        Under review.
    </li>
</ul>

<span style="font-size: 25px"> <strong> 2024 </strong></span>
<!-- ## 2024 -->

<ul  style="font-size: 15px">
    <li>
        <a href="https://coli-saar.github.io/balancedcollab"><strong>A Dialogue Game For Eliciting Balanced Collaboration</strong></a><br>
        <em><strong>Isidora Jeknić</strong>, David Schlangen and Alexander Koller</em><br>
        Proceedings of the 25th Annual Meeting of the Special Interest Group on Discourse and Dialogue, pages 477-489, Kyoto, Japan.
    </li>
    <br>
    <li>
        <strong>Enhancing Process Planning in the Automotive Industry: Extracting Procedural Knowledge from Assembly Operation Descriptions using Large Language Models</strong><br>
        <em>Thomas Mayr, Simon Knollmeyer, <strong>Isidora Jeknić</strong>, Leon Fink, Ralph Hensel, Marco F Huber, Daniel Großmann</em><br>
        Proceedings of the 18th CIRP Conference on Intelligent Computation in Manufacturing Engineering, pages n-m, Naples, Italy.
    </li>
</ul>



<!-- - [**A Dialogue Game For Eliciting Balanced Collaboration**](https://coli-saar.github.io/balancedcollab)<br>
***Isidora Jeknić**, David Schlangen and Alexander Koller*<br>
Proceedings of the 25th Annual Meeting of the Special Interest Group on Discourse and Dialogue, pages 477-489, Kyoto, Japan.  <br>


- **Enhancing Process Planning in the Automotive Industry: Extracting Procedural Knowledge from Assembly Operation Descriptions using Large Language Models** <br>
*Thomas Mayr, Simon Knollmeyer, **Isidora Jeknić**, Leon Fink, Ralph Hensel, Marco F Huber, Daniel Großmann*<br>
Proceedings of the 18th CIRP Conference on Intelligent Computation in Manufacturing Engineering, pages n-m, Naples, Italy.  <br> -->


{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

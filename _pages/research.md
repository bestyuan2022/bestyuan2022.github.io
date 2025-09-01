---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

## Working Papers

<style>
  .paper{margin:1.25rem 0 2rem;}
  .paper-title{margin:0 0 .2em 0; line-height:1.25;}
  .paper-meta{font-size:.95em; margin:0 0 .1em 0;}
  .paper-id{font-size:.9em; color:#777; margin:0;}
  .paper-id a{color:#777; text-decoration:none;}
  .abs-btn{font-size:.9em; padding:2px 6px; margin:.35em 0 0 0; background:none; border:none; color:#555; cursor:pointer; font-weight:500;}
  .abs-btn:hover{text-decoration:underline;}
  .abstract{display:none; margin:.5em 0 0 1rem; font-size:.9em;}
</style>

<div class="paper">
  <p class="paper-title">
    <a href="/files/cgr_rights.pdf"><strong>Preferences for Rights</strong></a>
    (with <a href="https://sites.google.com/view/avivcaspi/home">Aviv Caspi</a> and
    <a href="https://www.charlierafkin.com/">Charlie Rafkin</a>), December 2024
  </p>

  <button id="btn-abs1" class="abs-btn"
          onclick="toggleAbstract('abs1','btn-abs1')">Abstract +</button>
  <div id="abs1" class="abstract">
    Political debates often invoke “rights” to justify public transfers (e.g., the right to health care), whereas economists use welfarist frameworks which evaluate transfers’ impacts based on how they affect people’s utility. We conduct real-stakes online experiments that isolate non-welfarist from welfarist motives, and find sizable non-welfarist preferences to provide health care and legal aid to the indigent. 73% of participants make choices which are incompatible with welfarism. Non-welfarist concerns are weaker but still pervasive with neutral comparison goods. Additional experiments highlight drivers of non-welfarist motives and a key policy implication: non-welfarist concerns make Social Welfare Functions less progressive.
  </div>
</div>

<div class="paper">
  <p class="paper-title">
    <a href="/files/bcgr_inequality.pdf"><strong>How Does Wage Inequality Affect the Labor Movement?</strong></a>
    (with <a href="https://www.barbarabiasi.com/">Barbara Biasi</a>,
    <a href="https://zcullen.github.io/">Zoë Cullen</a>, and
    <a href="https://ninaroussille.github.io/">Nina Roussille</a>), June 2025
  </p>

  <p class="paper-meta">
    Reject &amp; Resubmit, <strong><em>Quarterly Journal of Economics</em></strong>
  </p>

  <p class="paper-id">
    <a href="https://www.nber.org/papers/w33978">NBER Working Paper No. 33978</a>
  </p>

  <button id="btn-abs2" class="abs-btn"
          onclick="toggleAbstract('abs2','btn-abs2')">Abstract +</button>
  <div id="abs2" class="abstract">
      This paper provides the first causal evidence on how occupational wage inequality affects the labor movement, using three complementary research designs: a vignette experiment with union organizers, an information intervention during the 2023 Writers Guild of America strike, and a natural experiment following a Wisconsin reform that increased wage inequality among public school teachers. Across all studies, we find that occupational inequality undermines union strength, through multiple channels. First, workers with high individual bargaining power are more likely to withdraw support in unequal environments, preferring individual over collective bargaining. Second, union organizers strategically respond to inequality in ways that may preserve membership but limit redistribution. For instance, they shift away from campaigning on wages and choose smaller, more homogeneous bargaining units. Taken together, our findings highlight the potential for “inequality traps”, where rising inequality erodes the very institutions designed to counteract it.
  </div>
</div>

<script>
function toggleAbstract(divId, btnId) {
  var x = document.getElementById(divId);
  var btn = document.getElementById(btnId);
  if (x.style.display === "none") {
    x.style.display = "block";
    btn.textContent = "Abstract –";
  } else {
    x.style.display = "none";
    btn.textContent = "Abstract +";
  }
}
</script>
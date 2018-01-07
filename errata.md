---
layout: default
active: errata
---

<!-- Errata -->
<section>
  <div class="page-header" id="supplement">
    <h2>Errata</h2>
  </div>
  <div class="row">
    <div class="span10 offset1">
    <!-- Note that all Markdown content but be outdented, including the surrounding div -->
<div markdown="1">

<script type="text/x-mathjax-config">
MathJax.Hub.Config({
  TeX: { equationNumbers: { autoNumber: "AMS" } }
});
</script>


* Page 209: ...conditioning event G, *then* enumerating... should read: conditioning event G, *than* enumerating  

* Page 244: Problem 54 - Given the following cumulative *density* function should read Given the following cumulative *distribution* function

* Page 340: R Code 5.15 - `facet_grid(. ~ r)` should read `facet_grid(. ~ r, labeller = label_parsed)`

* Page 485: `lep <- (15 - 1) + 5.2449/uchi` should be `lep <- (15 - 1) + 5.2429/uchi`, and
`uep <- (15 - 1) + 5.2449/lchi` should be `uep <- (15 - 1) + 5.2429/lchi`

* Page 545: Exampe 9.11 - `STCHOOL` should be `STSCHOOL`

* Page 551: $T=\frac{\bar{D}-\mu_{D}}{S_D/\sqrt{n_D}} \sim t_{n - 1}$ should be $T=\frac{\bar{D}-\mu_{D}}{S_D/\sqrt{n_D}} \sim t_{n_D - 1}$

* With update in `ggplot2`, everywhere `ggplot_hline(y = value)` appears now needs to be `ggplot_hline(yintercept = value)`


* If you find typos or errors, please report them at [https://github.com/alanarnholt/PASWR2E-Book/issues](https://github.com/alanarnholt/PASWR2E-Book/issues) so we can fix them.


</div>
    </div>
  </div>
</section>

---
layout: page
title: Promo 3
permalink: /promo3/
---

## Free helicopter

{% include snippet_include.html %}

What reward do you want to give this promo?

Suggest between 1 & 10: 
<form>
<input type="text" value="5" id="promovalue"/>
<input type="button" value="Reward me" onClick="rewardExperiment(parseFloat($(promovalue).val()))"/>
</form>
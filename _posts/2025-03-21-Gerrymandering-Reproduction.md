---
title: "Gerrymandering Reproduction Study"
categories:
 - Blog
tags:
 - Reproducability
 - GIScience
 - Gerrymandering
 - Research Planning
---
Our updated spatial analysis of Alabama’s 2023 congressional redistricting reveals meaningful improvements over the 2021 district configuration, yet persistent signs of racial packing remain. Notably, the new map introduces a second majority-Black district (District 2), which partially remedies the long-standing concentration of Black voters in District 7 and the fragmentation ("cracking") of Black communities elsewhere. This is evident in the map overlay of districts and percent Black by census block group: Districts 2 and 7 now together encompass much of the Alabama Black Belt, a region where many tracts have over 40% Black residents.

Despite this progress, our convex hull analysis indicates that District 7 remains racially packed. The absolute difference in percent Black between the district boundary and its convex hull (absdiffPct) is among the highest in the state, suggesting that even with two majority-Black districts, one is still disproportionately concentrated. Compactness metrics support this concern: both the shape-based (compact_shp) and convex hull (compact_hull) scores place Districts 6 and 7 in the middle range, implying moderate gerrymandering. However, in contrast to our 2021 baseline case, the 2023 data show weaker correlations between racial packing and these compactness scores—evident in greater residuals from the linear model fits. This suggests that compactness alone may be less predictive of racial gerrymandering in the new map.

Taken together, our findings emphasize that no single compactness measure can definitively diagnose gerrymandering. Instead, a multi-metric approach—coupled with close attention to racial and political demographics—is essential for evaluating how redistricting shapes representational equity. The case of Alabama underscores the importance of spatial justice: even when legal challenges succeed in altering district lines, structural inequities can persist in more subtle geographic forms


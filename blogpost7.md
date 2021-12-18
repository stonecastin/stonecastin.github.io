---
layout: page
title: Reproducing and Replicating Kang et al.
---

The study Kang et al. attempted to portray the ratio between available hospital bed and ventalator capacity for both the state of Illinois and the city of Chicago.
For our reproduction we expanded the road network generated in Kang to include those living 15 mile outside the city in the Chicago analysis.
We hoped that this change would reflect the reality that non residents would utilize Chicago resources, as those within the city would be nearest.
This fix would improve accuracy as many outside of large metropolitan areas choose to go to hospitals outside of their "region" for one reason or another.

Our analysis showed that whole the Chicago area had the most accessibility to resources (as in the original study), it had less availability than the study originally concluded. 

Data from sources like the census often looks at individuals as fixed points or aggregated into fixed polygons.
This is necessary for geographic analysis, though that assumption becomes an issue when humans are assumed to occupy only fixed  points.
In a previous project, I had to account for those working in Addison county VT, but living eslewhere.
Excluding New York state, for example, would have hampered my analysis.

[Here](https://ij-healthgeographics.biomedcentral.com/articles/10.1186/s12942-020-00229-x) is the Kang et al. study, and [here](https://github.com/cybergis/COVID-19AccessibilityNotebook) is the Kang et al repository on GitHub.

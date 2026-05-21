---
# title: Predicting 2026 Wildfires
# subject: Wildfire
# short_title: Interrogating fire history and probability to predict upcomding fires
# date: 2026-01-20
# authors:
#   - name: Vance Russell
#     affiliations:
#       - 3point.xyz
#     email: vance@3point.xyz
# license: CC-BY-4.0
# keywords: forest health, climate, predict, utilization
abstract: |
   Predicting where wildfires might occur is next to impossible due to multiple factors of weather, biotic, and abiotic conditions on the ground. We're going to do it anyway or at least examine what places might be vulnerable during 2026. We'll examine fire history and the chance of severe fires through fire perimeters since 2010 and the probability of crown fire. Surprisingly there are some places in the Sierra-Cascade region of California that may be more vulnerable than others.
exports: 
  - format: docx
    template: curvenote
    output: exports/predict.docx 
  - format: typst
    template: lapreprint-typst
    output: exports/predict.pdf     
---


## Take-aways
- **Enabling condition**. Climate, wildfire, and forest service restructuring are combining to make 2026 a potentially bad year for wildfires.
- **Pockets of infrequently burned and high crown fire probability** may point to where especially damaging fires may occur.
- **Continuing to increase the pace and scale of forest health restoration** will increase forest resilience and resistance to disturbance, especially wildfire.

# Background
> "Wildfire season is fast approaching, and with low snowpack, dry conditions, and soaring temperatures across the U.S., experts are warning that 2026 may be one of the worst on record. Combine those extreme conditions with massive restructuring at the U.S. Forest Service (USFS), and the result is a powder keg for federal wildland firefighters." @clarke

The 2026 wildfire season is shaping up to be one of the most severe in recent U.S. history, driven by a convergence of extreme climatic and institutional factors. A record-low snowpack across the West — California's measuring just 14–18% of average — combined with early-season heat and drought across 61% of the continental U.S. has created abundant, desiccated fuels primed to burn [@becker2026; @spanger]. Already through April, over 1.8 million acres have burned (194% above the 10-year average), and AccuWeather projects 5.5 to 8 million acres could burn by year's end [@clarke; @lada2026]. 

Compounding the environmental conditions, the U.S. Forest Service lost 16% of its workforce in 2025 and is undergoing a major restructuring that critics warn erodes firefighting support capacity [@simlot2026; @clarke]. Meanwhile, the newly formed U.S. Wildland Fire Service is racing to bring on aircraft and crews early, though experts caution that the administration's focus on suppression over prevention may leave the country underprepared [@larson2026]. Together, these factors point to a "fire year" rather than a seasonal threat, demanding urgent policy and operational responses [@kpbs2026].

But then again every year seems to get a dire wildfire prediction. Is this media hype, climate reality, or does the data help sort out science from fiction? Let's take a closer look.

# Predictive mapping
Generally, examining wildfire probability or history datasets of California, it can be hard to decipher the dominant oranges or reds from anything else. {numref}`perimeters` shows all wildfires greater than 5,000 acres (2,023 hectares) since 2010 [@frap]. Again, the map mostly looks orange, but if we zoom into key areas where forest occur, there are some spot where there haven't been large fires since 2010 such as northwestern Shasta County or Nevada and Sierra Counties. 

There is an especially large donut hole where there have not been large fires in the Sierra/Nevada and NE corner of Yuba county region for some time, really the only spot in the Sierra like this, except for Yosemite National Park where there's been a strong forest health and prescribed fire program for some time.

:::{figure} perims.png
:label: perimeters
:height: 650
Fire perimeters >5,000 acres since 2010 showing insets for Shasta County (above) and Sierra/Nevada Counties (below) where fewer large wildfires have occurred [@frap; @evt]. Map by 3point.xyz.
:::


We then looked at the probability of fires occurring in these areas. {numref}`probability` shows the mean crown fire probability [@pyrologix]. The values represent the likelihood of experiencing group torching (mid- to high-grade passive crown fire) or sustained canopy spread or active crown fire if a wildfire occurs. The data was joined to transverse hexagons 4,000 hectares (9,884 acres) in size and calculating the mean probability within each hexagon.

:::{figure} prob.png
:label: probability
:height: 650
Mean crown fire probability showing inset closeups in the Shasta and Sierra/Nevada County areas where high concentrations of wildfire probablity exist [@pyrologix]. Map by 3point.xyz.
:::
:::

Although there are areas of high probability for severe wildfire scattered throughout California, the two areas that lit up were in the Shasta and Sierra/Nevada County regions where multiple polygons of high probability conncted. This doesn't mean that wildfires will take place in these areas, but it does mean the likelihood is higher. In the Nevada County area, there have been concerted efforts to thin forest and create fuel breaks throughout the County. However, there are pockets, particularly in private land holdings where thinning has not taken place and many houses in the wildland urban interface have not created defensible space nor cleared pine leaves from roofs and yards.

# Biodiversity & Old-growth
Biodiversity not as high as old growth but looks like there is some in lower elevation NV County

For old-growth there does look like more of a relationship. Zonal stats or a regression to sum this and see if it is more than anecdotal.

As with climate change, misinformation about wildfire, forests, and logging has increasingly shaped public understanding and policy debates [@jones]. In California, this misinformation is often reinforced by deeply ingrained visual and cultural assumptions about what a healthy forest looks like. Many people implicitly picture dense, closed-canopy forests modeled on the eastern United States, northern Europe, or England, landscapes that evolved under very different climatic and ecological conditions. 

California’s forests exist largely within a Mediterranean climate, characterized by wet winters and long, hot, dry summers. These conditions favor fire-adapted ecosystems rather than the dense, moisture-rich forests common in temperate eastern regions. When forest health is judged using the wrong ecological reference point, fire-adapted landscapes can be misdiagnosed as degraded or overmanaged, while overly dense stands are mistakenly viewed as natural or desirable. 

What happens when we examine old-growth and species diversity with fire?

# Solutions
Returning to the mantra burn, bury, build, we recommend that all biomass utilization solutions incorporate the highest and best uses of forest product pathways. Moving forward, several integrated pathways can support forest health and biomass utilization:

1. **Treat more forested acres**. Through thinning and prescribed projects. California has been ramping up acres treated for some time now, but the pace and scale still needs to be accelerated. An element that is currently missing is infrastructure to treat biomass responsibly and sustainably.
2. **Climate adaptation and biomass integration**. Rapid scaling of forest health treatments, including thinning and prescribed fire, is critical to maintaining forest resilience in a warming climate [@delyser]. Policies that align forest treatments, biomass utilization, climate goals, and greenhouse gas reduction can reduce wildfire risk while ensuring that utilization infrastructure supports, rather than distorts, restoration outcomes [@biomass]. 
3. **Biomass aggregation**. A major hurdle for treating more forest acres is long-term feedstock supply agreements. Creating joint powers authoritiies to manage agreements between public landowners and wood product businesses, could greatly increase forest acres treated, but also utilize the wood in a manner that sequesters carbon and increases biodiversity [@jpa].

# Conclusion REWRITE THIS AND INTRO
While predicting the precise location of any given wildfire remains inherently uncertain, the convergence of historical fire patterns, crown fire probability modeling, and this year's extreme climatic conditions points to areas like Shasta and Nevada/Sierra Counties as particularly vulnerable. The data-driven approach underscores that it is not alarmism but empirical analysis that should guide preparedness, even as wildfire misinformation continues to muddy public debate. Addressing this crisis requires moving beyond suppression toward a sustained, landscape-scale program of thinning and prescribed fire, paired with infrastructure that can responsibly utilize the resulting biomass. Success will depend on policies that align forest restoration with climate goals, carbon sequestration, and economic viability through mechanisms like joint powers authorities for long-term feedstock agreements. Ultimately, the question is not whether severe fires will come, but whether we will have done enough to make our forests and communities resilient when they do.
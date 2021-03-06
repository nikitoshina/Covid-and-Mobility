**COVID Analysis Report**

Nikita Tkachenko

5/31/2021

# Introduction

In this analysis report, there will be a focus on the population mobility changes in different regime types.

## History of Pandemics

The world has undergone several pandemics in the course of its history. _Homo sapiens_ have been affected by many different viruses through evolutionary history. A pandemic can be described as a disease that spreads widely through a population in multiple areas at a specific time.

## Quarantine

One of the most effective methods of slowing the spread is quarantine, which is a restriction on the movement of people which is intended to prevent the spread of disease. Limiting travel is a cornerstone of this approach, so we will examine how different regimes managed population mobility in the pandemic.

## Biology of SARS-CoV-2 and Connections to Ecology

SARS-CoV-2 is the name of the virus that causes the disease called COVID-19. The factors that lead to spreading of the disease are sharing airspace indoors with infected people, although a person does not have to be symptomatic to spread the disease. Two important events that affected the current pandemic&#39;s mobility are the World Health Organization&#39;s initial recommendations to put lockdowns in place on 2020-04-16 and the discovery of new SARS-CoV-2 variants on 2020-12-31.

## Regimes

When the pandemic started blooming, the panic settled in, and countries tried reacting to their best ability: lockdowns were set in place, transit transport halted, and many stores closed. Each country had a unique response; however, there were generally observable patterns. It is worth noting that the government&#39;s authority is crucial for its citizens&#39; compliance. Only a respected leadership can persuade people to follow the guidelines that they might disapprove of. Presidential and parliamentary democracies and dictatorships have many differences in their ideologies, which will surely show up in the government&#39;s response and citizen&#39;s compliance.

The mobility data is crucial to understanding the government-citizens dynamic during the pandemic and evaluating the effectiveness or ineffectiveness of measures. There have been numerous incidents of people breaking the quarantine and traveling more than ever with jobs going online. Let us see how individual negligence translated into data!

# Methods

I used data in the covdata package in R to analyze the mobility scores&#39; fluctuations over time around the world. I also used poliscidata, a data set with variables about countries in the world, to group the countries by regime type. That data was current as of May 31, 2021.

# Results

![](assets/image001.png)

**Figure 1:** Driving mobility bottoms out in April 2020 and January 2021 and peaks in August 2020, with a mobility score of over 220 on some days. Peaks and troughs coincide for the three regimes; however, the presidential democracy has a generally higher level of mobility, and dictatorship holds a steady score level after the initial low point.

![](assets/image003.png)

**Figure 2:** Transit mobility also bottoms out in April 2020 and January 2021 and peaks in September 2020. The initial trough coincides for the three regimes. However, the latter dynamic is unique for each of the three. Parliamentary democracy peaks in September 2020 and bottoms out in January 2021. Dictatorship grows steadily since the initial decrease. And presidential democracy fluctuates around the score of 60 with slight deviations, following the general trend.

![](assets/image005.png) 

**Figure 3:** Walking mobility bottoms out in April 2020 and January 2021 and peaks in September 2020. The initial trough coincides for the three regimes. However, dictatorship recovers from the initial trough and proceeds to maintain the pre-pandemic level of mobility.

# Discussion

I analyzed the apple mobility score of driving, transit, and walking transportation types for the presidential, parliamentary democracies, and dictatorships through the COVID-19 pandemic. There was a general pattern of 2 troughs in April 2020 and January 2021 and one peak in August/September 2020. Pattern coincides with World Health Organization&#39;s initial recommendations to put lockdowns in place (2020-04-16) and the discovery of new SARS-CoV-2 variants (2020-12-31).

## Presidential democracies

The driving and walking mobility plots suggest that people from the presidential democracies started walking and driving much more often, almost twice as often on some days after the lockdown! Nonetheless, transit mobility stayed low for the entire time. I hypothesize that this behavior can be explained by the mentality, customs and restrictions. To me, it occurs that transit mobility was affected mainly by the authorities limiting the transportation and widespread car culture. On the other hand, the government did not control walking and driving mobilities, so the population used these methods to travel. It must be noted that the governments&#39; announcements and restrictions have hit the score downwards, but the population overcame the initial fear and drove the score up within months.

## Parliamentary democracies

Parliamentary democracies match presidential democracies but have lower scores in walking and driving. As for the transit score, it appears that transit plays a vital role in these countries and adheres to the general pattern of troughs and peaks yet stays below the pre-pandemic level most of the time. It might be because the population trusted the authorities more and was more willing to follow their recommendations than the population of presidential democracies.

## Dictatorships

Dictatorship has shown a pattern different from the two democracies. Its mobility score fell lower than in democracies for all mobility types, but it recovered to the pre-pandemic level within few months. I suspect that the dictatorship government&#39;s population quickly recovered from the initial shock of the lockdown and proceeded to go to their jobs and travel for other needs as usual while following the hygiene recommendations and distancing.

## What is Next?

The regime has some influence on how countries reacted to the threat. However, it is hard to tell which reaction was better because mobility is only a part of the response.

The data gives a fascinating insight into how mobility changed in different regimes during the pandemic. But it also opens many questions. Why did mobility scores increase so much after the initial lockdown in democracies, and what effect did it have? Would it have been better to follow the dictatorships&#39; example and return to the pre-pandemic levels or experience an increase similar to democracies? What is the correlation between mobility scores and COViD-19 cases?

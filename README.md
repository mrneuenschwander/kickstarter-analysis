# Kickstarting with Excel
Week 1 Project

## Overview of Project
This analysis is intended to proide a window into the marketing and completion rates of various kickstarter campaigns across a range of years. Primarily, it is focused on the success of theater outcomes based on their launch dates, and funding success rates of an overseas campaign concerning Great Britain in particular. ![GB Theater BOXPLOT](https://user-images.githubusercontent.com/116296092/200143943-a6625c69-cd08-4f2d-9fcc-59f60e8069ad.png)

### Purpose
To show the launch dates and costs of camapigns that are likely to garner the most success in their given sphere. It does no one any good to launch a campaign in a market that doesn't want it, and this report will help the Client to avoid certain pitfalls that could otherwise be a problem if not accounted for.

## Analysis and Challenges
The full analysis is wide-ranging, but does primarily consider the Theater category, as that is what the Client requested. It drills into a few favorites: <img width="837" alt="Top_Plays_Edinburgh" src="https://user-images.githubusercontent.com/116296092/200142262-9bbcbb4b-f588-422d-be6d-b77c33cc02a6.png"> 

as well as a full list of successful US Campaigns that could provide further insight into the following section's report, and more: <img width="1243" alt="Successful US Theater Campaigns" src="https://user-images.githubusercontent.com/116296092/200142325-1010c369-adab-4f84-a277-928e24e53235.png"> 
Difficulties encountered were primarily with the new functions, but in-system diagnostics and documentation, in addition to online sources, greatly lessened time lost to them. Other difficulties that are likely to be encountered include loss of data organization to incorrect formatting (as the dataset is large and does not integrate radical changes well), and occasionally crashing due to volume. Issues from both of these can be mitigated with manual saving on completion of a section, and confirmation of data placement when creating a new formula or PivotTable to be used in reporting.

### Analysis of Outcomes Based on Launch Date
The first conclusion we can draw regarding launch dates is that late spring into the early part of summer is the best time to launch a fundrasing campaign for a theater production. ![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/116296092/200142743-a05e5580-e76d-4c13-a632-f5f21bb8a3e3.png)
It could be inferred that this is due to summer approaching, and the availibility and/or popularity of outdoor venues (such as the one is Tuacahn, UT, US) goes up significantly. The second is that theater campaigns as a whole are more successful than campaigns across other media: ![Campaign_Success_Rates](https://user-images.githubusercontent.com/116296092/200143110-2ffe0011-0071-4b4c-856c-9029ecb9ec1a.png)
and that is already a more positive outlook than if an attempt was being made to launch a technology campaign, for example. Currently, there are no live campaigns in the tech section, whereas the Theater and others have not only live campaigns, but better success rates as a whole.

### Analysis of Outcomes Based on Goals
Interestingly, there is an exact inverse relationship of the outcomes as the dollar value for the goal goes up:
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/116296092/200143760-a41e311c-00c5-425b-ac5c-a17a50a4df58.png)
There weren't any canceled campaigns, so it's considered a pass/fail engagement in this respect. The smaller productions tend to see better success, and productions created for around $35,000 are also more than 50% successful.

### Challenges and Difficulties Encountered
The challenge that presents itself here isn't concerning the sorting of the data, it's making it look good. The sets get much smaller when working with specifically theater camapigns, and thus they're easier to manipulate than the primary Kickstarter sheet. The trick with the smaller sets is to not allow smaller details to slip by, and to present the data that will still be relevant to the Client request without getting too granular. Limitations could exist in the data, as it is a public scrape of one fundrasing site, and other campaign's fundraisers may be more popular on other platforms (GoFundMe, for example). With that in mind, a few thousand points of data to play with shows that if you're going to launch a theater campaign, Kickstarter in the months of May and June are the way to go.

## Results

- The best time to launch a Theater Campaign is in late Spring/Early summer.
- Theater campaigns will be statistically more successful than other media.
- Lower-cost productions tend to fund better, with the exception of $35-40,000 campaigns. Go big or go home, I suppose.
- This dataset is publically-acquired, and thus is subject to the wiles of the internet and/or pipe dreams. For instance, a $100M campaign for "The Time Jumper", with a description that reads "My ambition for this knows no bounds.  Seeing Sephoria in a live-action is a dream of mine."
- Other tables and graphs could be created regarding the Duration of Campaigns by Goal, the success rates of campaigns by year as it relates to goal, and similar graphs that were created for the Theater but based in other mediums such as EDM campaigns or Video Games.

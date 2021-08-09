# Citizen Browser: How The Daily Wire Uses Targeted Advertising on Facebook
This repository contains data from the story ["How The Daily Wire Uses Facebook's Targeted Advertising to Build Its Brand"](https://themarkup.org/citizen-browser/2021/08/10/how-the-daily-wire-uses-facebooks-targeted-advertising-to-build-its-brand) from from our series, [Citizen Browser](https://themarkup.org/citizen-browser/). Citizen Browser construction and methodology is described in "[How We Built a Facebook Inspector](https://themarkup.org/citizen-browser/2021/01/05/how-we-built-a-facebook-inspector)."

## Data
The `data/` directory contains three csv files with data from the story.

1. `daily-wire-50-ad-interests.csv` contains the top 50 interest categories used by the Daily Wire in Facebook ads targeted by interest.
2. `nyt-50-ad-interests.csv` contains the top 50 interest categories used by the New York Times in Facebook ads targeted by interest.
3. `nyt-dw-targeting-types.csv` shows the type of targeting used across all posts from the Daily Wire and the New York Times for which Citizen Browser could obtain targeting information during the time of this investigation.

-----

Data in csv 3 is arranged as follows:
| column           | decription                                                                                |
|:-----------------|:------------------------------------------------------------------------------------------|
| targeting_type   | The type of ad targeting used. Facebook provides more information about ad targeting options [here](https://www.facebook.com/business/help/633474486707199)                                      |
| count       | The absolute number of ads using this type of targeting  |
| percent      | The number of ads using this targeting type, as a percentage of all ads from the publication in our dataset  |
| name       | Name of the publication  |

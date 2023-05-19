# League Of Legends 2022 Professional Match Action

by Luis Martinez-Chun (lmartinezchun@ucsd.edu)

---

## Introduction

In this project, I studied which league has the most “action-packed” games? Is the amount of “action” in this league significantly different than in other leagues?
The data set used was collected from 2022 League of Legends professional match data.
The raw data contained 149400 rows, and 123 columns. However, for my research purposes only data from the columns:
```py
['kills', 'deaths', 'assists', 'doublekills', 'triplekills', 'quadrakills', 'pentakills', 'damagetochampions', 'damagetakenperminute', 'damagemitigatedperminute']
```




---

## Cleaning and EDA

<iframe src="assets/matchesCountsAndAction.html" width=800 height=600 frameBorder=0></iframe>

---

## Assessment of Missingness

Here's what a Markdown table looks like. Note that the code for this table was generated _automatically_ from a DataFrame, using

```py
print(counts[['Quarter', 'Count']].head().to_markdown(index=False))
```

| Quarter     |   Count |
|:------------|--------:|
| Fall 2020   |       3 |
| Winter 2021 |       2 |
| Spring 2021 |       6 |
| Summer 2021 |       4 |
| Fall 2021   |      55 |

---

## Hypothesis Testing


---

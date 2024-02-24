---
layout: features
title: Features
---

### Minimum Viable Product Features
- [**Big Number**](#big-number)
- [**Big Number Chart**](#big-number-chart)
- [**Private Ranking**](#private-ranking)
- [**Public Ranking**](#public-ranking)
- [**Peer Competition**](#peer-competition)
- [**Income Percentile Calculator**](#income-percentile-calculator)
- [**Spending Breakdown Chart**](#spending-breakdown-chart)
- [**Levels & Achievments**](#levels-&-achievments)
- [**Transaction Level Data**](#transaction-level-data)
- [**Localized Data**](#localized-data)


{% for feature in site.features %}
## [{{ feature.name }}]({{ feature.url }})
### {{ feature.description }}

**Problem:** {{ feature.problem }}

**Solution:** {{ feature.solution }}

**Stretch Feature:** {{ feature.stretch_feature }}


{% endfor %} 

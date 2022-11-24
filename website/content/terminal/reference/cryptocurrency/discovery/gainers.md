---
title: gainers
description: OpenBB Terminal Function
---

# gainers

Shows Largest Gainers - coins which gain the most in given period. You can use parameter --interval to set which timeframe are you interested in: {14d,1h,1y,200d,24h,30d,7d} You can look on only N number of records with --limit, You can sort by {Symbol,Name,Price [$],Market Cap,Market Cap Rank,Volume [$]} with --sort.

### Usage

```python
usage: gainers [-i {14d,1h,1y,200d,24h,30d,7d}] [-l LIMIT] [-s SORTBY [SORTBY ...]]
```

---

## Parameters

| Name | Description | Default | Optional | Choices |
| ---- | ----------- | ------- | -------- | ------- |
| interval | time period, one from {14d,1h,1y,200d,24h,30d,7d} | 1h | True | 14d, 1h, 1y, 200d, 24h, 30d, 7d |
| limit | Number of records to display | 15 | True | None |
| sortby | Sort by given column. Default: Market Cap Rank | market_cap | True | Symbol, Name, Price [$], Market Cap, Market Cap Rank, Volume [$] |
---

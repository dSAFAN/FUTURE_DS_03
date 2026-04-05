# Funnel Analysis Report — November 2019

## Executive Summary
- Data source: `data/processed/01_overall_funnel_NOV.csv`, `02_brand_comparison_NOV.csv`, `03_price_funnel_NOV.csv`
- Total unique users by stage:
  - `01_View`: 176,624
  - `02_Intent`: 17,159
  - `03_Purchase`: 13,635
- Funnel conversion rates:
  - View → Intent: **9.71%**
  - Intent → Purchase: **79.46%**
  - View → Purchase: **7.72%**

## Overall Statistical Numbers
- Total funnel drop-off at early stage: **90.29%** of views do not convert into intent.
- Final purchase conversion from intent is strong at **79.46%**.
- Overall conversion from view to purchase is **7.72%**.

## Brand Funnel Metrics (Full Top 10)
| Brand   | Views     | Intent     | Purchases | Intent conv. | Purchase conv. |
|--------|-----------|------------|-----------|--------------|----------------|
| Samsung | 38,028 | 4,403 | 3,366 | 11.58% | 76.45% |
| Apple   | 32,023 | 3,626 | 2,667 | 11.32% | 73.55% |
| Xiaomi  | 19,638 | 1,676 | 1,109 | 8.53%  | 66.17% |
| Huawei  | 7,993 | 590 | 415 | 7.38%  | 70.34% |
| Lucente | 5,410 | 226 | 226 | 4.18% | 100.00% |
| Oppo    | 4,587 | 348 | 263 | 7.59% | 75.57% |
| LG      | 4,922 | 226 | 174 | 4.59% | 76.99% |
| Bosch   | 4,307 | 125 | 103 | 2.90% | 82.40% |
| Cordiant | 5,075 | 439 | 328 | 8.65% | 74.72% |
| Sony    | 4,323 | 188 | 137 | 4.35% | 72.87% |

### Brand insights
- `Samsung` and `Apple` lead with the highest volume and strong intent conversion rates of **11.58%** and **11.32%** respectively.
- `Lucente` maintains perfect purchase conversion at **100%**, though with much lower overall volume compared to October.
- `Bosch` shows the weakest intent conversion at only **2.90%**, indicating significant product positioning challenges in November.
- `Oppo` improved in November volume and maintains a solid **75.57%** purchase conversion rate.

## Price Tier Performance
| Price Tier | Views      | Intent     | Purchases | Intent conv. | Purchase conv. |
|------------|------------|------------|-----------|--------------|----------------|
| Low        | 77,681  | 5,236    | 4,368   | 6.74%       | 83.42%         |
| Medium     | 86,568  | 7,001    | 5,502   | 8.09%        | 78.59%         |
| High       | 84,325  | 5,931    | 4,601   | 7.03%        | 77.58%         |

### Price tier insights
- `Medium` tier shows the best intent conversion at **8.09%**, outperforming low and high tiers.
- `Low` tier has strong purchase conversion at **83.42%**, the highest among all price tiers in November.
- `High` tier, while still strong, shows the weakest purchase conversion at **77.58%**, suggesting potential resistance at premium price points.
- Overall, the medium-to-low price strategy appears to drive better funnel performance in November.

## Additional Statistical Observations
- The primary business challenge in November is the **View → Intent** conversion at only **9.71%**, significantly lower than October's **15.93%**, indicating a notable decline in user engagement.
- However, given the lower view volume, the **Intent → Purchase** conversion is unexpectedly strong at **79.46%**, suggesting that users who show intent are highly likely to complete purchases.
- `Lucente` continues to show perfect purchase retention but with significantly lower volume (226 intent users vs. 6,928 in October).
- `Bosch` deteriorated significantly with only **2.90%** intent conversion in November compared to **4.37%** in October, requiring immediate investigation.

## Recommendations
1. **Urgent**: Investigate the **39% drop** in View → Intent conversion from October (**15.93%**) to November (**9.71%**). This suggests a potential issue with product discovery, search visibility, or user engagement tactics.
2. Capitalize on the strong **Intent → Purchase** conversion (**79.46%**). Focus on driving more qualified traffic to the intent stage rather than optimizing the purchase stage.
3. Prioritize `Samsung` and `Apple` investment and marketing, as they maintain the highest volume and strongest conversion rates.
4. **Critical**: Address `Bosch`'s dramatic performance drop (intent conversion from **4.37%** to **2.90%**). This brand needs immediate repositioning or inventory review.
5. Analyze the shift from extreme medium-tier performance in October (**99.55%** purchase conversion) to more balanced November metrics (**78.59%**). Consider if campaign changes or inventory shifts affected this tier.
6. Continue leveraging the low-to-medium price tiers, which now show balanced and healthy funnel performance.

## Data Notes
- These values are taken directly from the November 2019 processed funnel data outputs.
- All numbers are unique-user funnel counts per stage.
- **Key Finding**: November shows significantly lower overall traffic (176,624 views vs. ~3M in October) and lower View → Intent conversion, suggesting a seasonal or campaign-related change that warrants investigation.

# Funnel Analysis Report — November 2019

## Executive Summary
- Data source: `data/processed/01_overall_funnel_NOV.csv`, `02_brand_comparison_NOV.csv`, `03_price_funnel_NOV.csv`
- Total unique users by stage:
  - `01_View`: 3,022,130
  - `02_Intent`: 481,458
  - `03_Purchase`: 347,118
- Funnel conversion rates:
  - View → Intent: **15.93%**
  - Intent → Purchase: **72.10%**
  - View → Purchase: **11.49%**

## Overall Statistical Numbers
- Total funnel drop-off at early stage: **84.07%** of views do not convert into intent.
- Final purchase conversion from intent is strong at **72.10%**.
- Overall conversion from view to purchase is **11.49%**.

## Brand Funnel Metrics (Full Top 10)
| Brand   | Views     | Intent     | Purchases | Intent conv. | Purchase conv. |
|--------|-----------|------------|-----------|--------------|----------------|
| Samsung | 935,464 | 119,555 | 94,073 | 12.78% | 78.69% |
| Apple   | 729,319 | 82,063 | 65,593 | 11.25% | 79.93% |
| Xiaomi  | 470,832 | 43,409 | 35,063 | 9.22%  | 80.77% |
| Huawei  | 234,061 | 19,042 | 15,378 | 8.14%  | 80.76% |
| Lucente | 145,492 | 6,928 | 6,928 | 4.76% | 100.00% |
| LG      | 145,762 | 6,992 | 5,970 | 4.80% | 85.38% |
| Bosch   | 142,152 | 6,209 | 4,175 | 4.37% | 67.24% |
| Oppo    | 114,818 | 9,106 | 7,086 | 7.93% | 77.82% |
| Sony    | 122,111 | 5,143 | 4,406 | 4.21% | 85.67% |
| Acer    | 87,586 | 4,755 | 4,352 | 5.43% | 91.52% |

### Brand insights
- `Samsung` and `Apple` are the highest-volume brands and also convert the best at the intent stage among the top brands.
- `Lucente` is the only brand with **100% purchase conversion** from intent.
- `Bosch` has the weakest final-stage purchase conversion at **67.24%**, indicating a potential product- or pricing-specific drop-off.
- `Acer` has the highest final purchase conversion among the top brands at **91.52%**.

## Price Tier Performance
| Price Tier | Views      | Intent     | Purchases | Intent conv. | Purchase conv. |
|------------|------------|------------|-----------|--------------|----------------|
| Low        | 1,602,364  | 162,272    | 125,258   | 10.13%       | 77.19%         |
| Medium     | 1,797,777  | 158,336    | 157,626   | 8.81%        | 99.55%         |
| High       | 1,736,716  | 141,186    | 125,548   | 8.13%        | 88.92%         |

### Price tier insights
- `Medium` tier is the strongest funnel performer with an almost perfect purchase conversion of **99.55%**.
- `High` tier also converts well at **88.92%**.
- `Low` tier shows the weakest final purchase conversion at **77.19%**, suggesting room to strengthen offers or messaging in the low-price portfolio.

## Additional Statistical Observations
- The main business opportunity is improving the **View → Intent** stage, where the funnel loses **84.07%** of users.
- `Lucente` stands out with perfect purchase retention, but its low intent volume means it is more of a niche success case.
- `Bosch` and `LG` show lower intent-stage performance; these brands may benefit from stronger product positioning or targeted incentives.

## Recommendations
1. Report the early-stage conversion gap clearly: only **15.93%** of views become intent.
2. Highlight `Medium` tier performance as the strongest price segment.
3. Prioritize top-performing brands `Samsung`, `Apple`, and `Xiaomi` in marketing and inventory.
4. Investigate underperforming brands like `Bosch` and `LG` to understand why intent and purchase conversion are lower.
5. Use this report as the accurate reference for November 2019 processed funnel metrics.

## Data Notes
- These values are taken directly from the November 2019 processed outputs.
- All numbers are unique-user funnel counts per stage.

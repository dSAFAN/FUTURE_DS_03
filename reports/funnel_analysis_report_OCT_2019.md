# Funnel Analysis Report — October 2019

## Executive Summary
- Data source: `data/processed/01_overall_funnel_OCT.csv`, `02_brand_comparison_OCT.csv`, `03_price_funnel_OCT.csv`
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

## Brand Funnel Metrics (Top 10)
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
| Acer    | 87,586  | 4,755 | 4,352 | 5.43% | 91.52% |

### Brand insights
- `Samsung` and `Apple` are the top-volume brands and also lead in intent-stage conversion among the top 10.
- `Lucente` shows perfect purchase retention, converting all intent users into purchases.
- `Bosch` is the weakest performer at the final stage, with only **67.24%** of intent converting to purchase.
- `Acer` has the strongest final purchase conversion among the top brands at **91.52%**.

## Price Tier Performance
| Price Tier | Views      | Intent     | Purchases | Intent conv. | Purchase conv. |
|------------|------------|------------|-----------|--------------|----------------|
| Low        | 1,602,364  | 162,272    | 125,258   | 10.13%       | 77.19%         |
| Medium     | 1,797,777  | 158,336    | 157,626   | 8.81%        | 99.55%         |
| High       | 1,736,716  | 141,186    | 125,548   | 8.13%        | 88.92%         |

### Price tier insights
- `Medium` tier is the strongest performer, with nearly full purchase conversion at **99.55%**.
- `High` tier converts well at **88.92%**, indicating premium demand.
- `Low` tier has the weakest purchase conversion at **77.19%**, suggesting room for improvement in value or promotion.

## Additional Statistical Observations
- The biggest business opportunity remains the early funnel: only **15.93%** of views become intent.
- `Lucente`’s perfect purchase conversion highlights a highly efficient niche funnel.
- `Bosch` and `LG` need attention for improving both intent and purchase conversion rates.

## Recommendations
1. Report the View → Intent gap clearly as the main funnel issue.
2. Highlight the strong performance of the medium-price tier.
3. Prioritize marketing and inventory for `Samsung`, `Apple`, and `Xiaomi`.
4. Investigate underperforming brands like `Bosch` and `LG` for product or pricing issues.
5. Use this October report for month-over-month comparison with November.

## Data Notes
- Values are taken directly from the October 2019 processed funnel outputs.
- All counts reflect unique users per funnel stage.

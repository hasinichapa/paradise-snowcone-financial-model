# Paradise SnowCone Shack: Seasonal Financial Model

An Excel financial model built through FLY's Corporate Strategy Fellowship to test whether Paradise SnowCone Shack, a family-run seasonal drink business, should buy ingredients direct from the manufacturer instead of a distributor. The model compares both options across base, weak-summer, and strong-summer scenarios.

## Key results (base case, estimated)

| Metric | Value |
|---|---|
| Total revenue | $27,139 |
| Gross profit | $19,514 (71.9% margin) |
| Net profit (cash left over) | $14,528 |
| Busiest month | August, about 36 drinks per day |
| Top product by gross profit | Piña Colada |
| Yearly savings from buying direct | about $915 (about $790 in a weak summer, $1,040 in a strong one) |

All figures are estimates. See "Where the information comes from" below.

## What the model does

- Projects monthly sales, costs, profit, and cash flow across the April-to-September season, with demand driven by average temperature and rain days
- Analyzes profitability by menu item, including margins and each flavor's share of gross profit
- Models Tajín rim and straw add-ons on mango drinks, Mother's and Father's Day bundles (3 drinks for $5), and vending at Prestonwood Polo Club
- Compares base, weak-summer, and strong-summer scenarios, each with distributor vs. direct-from-manufacturer sourcing

## Workbook tabs

| Tab | What it shows |
|---|---|
| Cover | Project overview, sources, and color guide |
| Dashboard | Year-at-a-glance summary, highlights, and two charts |
| Assumptions | Every input the model uses, with a Basis column marking each as Observed or Estimate |
| Model | Month-by-month sales, costs, net profit, and cash |
| Products | Profitability by menu item |
| Scenarios | Three summers x two sourcing options, side by side |

## How to use it

1. **[Download the Excel model](https://github.com/hasinichapa/paradise-snowcone-financial-model/raw/main/Paradise_Snow_Cones_Financial_Model%20%281%29.xlsx)** and open it in Excel.
2. Go to the **Assumptions** tab and find the two yellow cells.
3. Change the **scenario** (1 = Base, 2 = Weak summer, 3 = Strong summer) or set **Buy direct from manufacturer** to 1 to see how revenue, profit, and cash change.

Color guide: blue text is an input, black is a formula, green is a link to another tab, and yellow marks an adjustable setting.

## Where the information comes from

- **Observed (May-Sept 2026):** operating hours (open every day from April to September, closed October to March), unpaid family labor, menu flavors, Tajín add-ons on mango drinks, Mother's and Father's Day bundles, and occasional vending at Prestonwood Polo Club.
- **Estimated:** ingredient costs, daily sales volumes, and expense amounts, which are not from the business's financial records. Daily sales are anchored to roughly 30-50 drinks on a hot, busy August evening.
- **Weather:** rounded, approximate average highs and rain days for the Aubrey / North Texas area, not pulled from a weather database.

Because the dollar figures are estimates, this is a modeling exercise, not the business's actual financial statements.

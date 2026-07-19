# Retail Sales & Shipping Performance Analysis (Superstore Dataset)

Analyzed 9800 orders across 1861 products, 4 regions, and 3 customer segments 
to identify sales drivers, regional performance gaps, and shipping efficiency 
patterns — directly mirroring returns/fulfillment analytics work.

## Key Findings
- Phones and Chairs sub-categories together drove ~28% of total revenue — 
  the clearest "hero" sub-categories in the catalog.
- West region generated the highest total sales, with New York City the 
  single strongest market by revenue.
- Consumer segment contributed roughly half of total sales, ahead of 
  Corporate and Home Office combined.
- November 2018 was the strongest month overall, driven primarily by 
  the Technology category — a clear seasonal spike worth flagging for 
  inventory planning.
- Shipping duration varied meaningfully by Ship Mode but stayed fairly 
  consistent across regions — suggesting shipping delays are a carrier/mode 
  issue, not a regional logistics gap.
- Identified top 10 "hero SKUs" by total sales for inventory prioritization, 
  and flagged the weakest-performing Region × Category combinations as 
  candidates for business attention.

## Limitations & Next Steps
- Dataset has no Profit or Discount columns, so "profitability" couldn't be 
  directly assessed — analysis focused on Sales volume and shipping efficiency 
  instead.
- Seasonal spike (November) is based on a single year snapshot in places — 
  a multi-year trend would strengthen the seasonality claim.
- Next step: layer in a Profit-inclusive dataset to test whether high-Sales 
  categories are also high-margin, since Sales alone can be misleading 
  (Phones may sell a lot but carry thin margins).

## Tools
Python (Pandas, Pivot Tables, Matplotlib),VS Code

Blinkit Sales & Operations Analysis

Excel . SQL . Power BI

Why I built this:

Quick-commerce is an interesting space to analyze things move fast, margins are tight, and the difference between a good and a bad day often comes down to operational decisions made in real time. I wanted to dig into Blinkit's sales data and figure out not just what was happening, but why it was happening and what could be done about it.

About the data:

The dataset covers 8,523 sales records across 10 outlets spanning Tier 1, 2, and 3 cities — with a total sales figure of $18.59M. It includes item-level details like MRP, fat content, and visibility score, plus outlet metadata like size, type, and establishment year.

Questions I started with:
Before touching the data, I wrote down the things I genuinely wanted to know:
1. What's actually driving revenue is it a few categories or spread across the board?
2. Which outlet types and locations are performing above expectations?
3. Does item visibility actually translate into higher sales?
4. Where are the gaps and what's the simplest fix?
5. What the data revealed?

A few things genuinely surprised me:
- Tier 3 cities outperform Tier 1-$7.6M vs $4.5M in total sales. Not what you'd expect going in, and worth investigating from a market investment angle.
- Two categories carry almost 30% of revenue -Fruits & Vegetables ($2.82M) and Snack Foods ($2.73M) together account for 29.3% of all sales across 16 item types. Classic 80/20 in action.
- Supermarket Type1 drives 69.5% of total sales despite being one of four outlet types. It clearly leads, with Type 3 far behind at 18.6%.
- High visibility ≠ high sales Grocery Stores have the highest average item visibility (0.10) but contribute less than 2% of total revenue. Visibility alone isn't moving product.
- Medium-sized outlets lead on volume generating $11.88M vs $4.57M for small and $2.14M for high-sized outlets.
  Note: This dataset does not include timestamp or delivery time data, so order-timing and reorder analysis would require a richer data source.

How I approached it:
1. I used SQL to do the heavy lifting on aggregations before building any visuals,things like sales contribution % by outlet size (which needed a subquery), fat content comparisons, and ranking outlet identifiers by total revenue. Power BI came in after the analysis was done, not before.
2. Excel was used upfront for data cleaning, handling null Item_Weight values, standardizing the fat content labels (the raw data had "low fat", "Low Fat", and "LF" as separate entries), and doing a first-pass sanity check on the numbers.

What I'd recommend (if I were consulting here):
Focus more on Tier 3 cities the data shows there is demand, even if the assumption was the opposite Understand why Grocery Stores have high visibility but low sales before investing more in that channel Protect and grow the top two categories (Fruits & Vegetables, Snack Foods),they are doing more work than expected, Look into medium vs large outlet sizes  medium outlets are performing much better in total sales. If I were extending this project, I'd want to bring in timestamp data to look at order timing patterns, and transaction-level data to track repeat purchase behavior both would unlock a much richer picture.


I'm currently looking for data or business analyst roles. If this kind of work is relevant to what your team does, I'd love to connect.

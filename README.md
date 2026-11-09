# Kalshi 2026 midterm prices against the results

Kalshi's election day price for every 2026 House, Senate and governor race it listed, next to how Kalshi settled the race. One CSV, 475 races.

The prices were read from Kalshi's public order book at Nov 3, 2026, 12:17 PM ET, before polls closed. Results are Kalshi's own settlements, last checked on November 9, 2026 at 5:02 PM ET. The live page, which keeps checking Kalshi until every race settles: https://evdesk.ai/markets/midterms-2026

## The count

Of the 457 races settled so far, the side the prices favored won 440. 18 races had not settled at the last check.

| Favorite's price | Races | Favorite won | Share |
|---|---:|---:|---:|
| 50% to 59% | 10 | 5 | 50% |
| 60% to 69% | 17 | 10 | 59% |
| 70% to 79% | 19 | 15 | 79% |
| 80% to 89% | 34 | 33 | 97% |
| 90% and up | 377 | 377 | 100% |

## By the party the prices favored

| Favorite | Races | Favorite won | Favorite lost |
|---|---:|---:|---:|
| Democratic favorites, all prices | 263 | 262 | 1 |
| Republican favorites, all prices | 194 | 178 | 16 |
| Democratic favorites, priced under 80% | 21 | 20 | 1 |
| Republican favorites, priced under 80% | 25 | 10 | 15 |

16 of the 17 upsets were Democratic wins over a Republican favorite.

## What the prices implied

Read each favorite's election day price as its chance of winning and add up the chances of losing. That sum is the number of misses the prices implied. Races move together in a national swing, so the real count can land well away from it.

| Races | Settled | Misses implied | Misses |
|---|---:|---:|---:|
| All settled races | 457 | 30.6 | 17 |
| Democratic favorites | 263 | 14.4 | 1 |
| Republican favorites | 194 | 16.2 | 16 |
| Favorites priced at 90% and up | 377 | 10.0 | 0 |

## The 17 races the favorite lost

Longest shot first. The winner's price is the chance Kalshi's market gave it on election day.

| Race | Democratic | Republican | Winner |
|---|---:|---:|---|
| NC-06 House | 14% | 87% | Democratic |
| NC-14 House | 22% | 79% | Democratic |
| IN-05 House | 26% | 75% | Democratic |
| OH-10 House | 30% | 71% | Democratic |
| South Carolina Senate | 30% | 71% | Democratic |
| NV-02 House | 34% | 65% | Democratic |
| Texas governor | 34% | 66% | Democratic |
| NC-09 House | 35% | 65% | Democratic |
| NC-13 House | 35% | 66% | Democratic |
| TX-23 House | 37% | 64% | Democratic |
| MO-02 House | 40% | 61% | Democratic |
| OH-15 House | 40% | 62% | Democratic |
| NJ-02 House | 44% | 56% | Democratic |
| CO-05 House | 46% | 55% | Democratic |
| SC-01 House | 48% | 53% | Democratic |
| Iowa Senate | 50% | 51% | Democratic |
| VA-05 House | 51% | 50% | Republican |

## Columns

| Column | Meaning |
|---|---|
| `chamber` | Senate, Governor or House |
| `race` | The state, or the House district |
| `kalshi_event` | Kalshi's event ticker for the race |
| `democratic_price_pct` | The Democratic side's price on election day, as a percent |
| `republican_price_pct` | The Republican side's price on election day, as a percent |
| `favored` | D or R, the side with the higher price |
| `winner` | D or R as Kalshi settled it, or `not settled` |
| `upset` | `yes` if the favored side lost, `no` if it won, empty if not settled |

## Notes on method

- The prices are from midday on election day, not poll close, so they are a few hours earlier than the figures Kalshi has published.
- The two prices do not always add to exactly 100%. Where Kalshi also listed a candidate from neither party, they add to well under it.
- A market priced at 70% should see its favorite lose about three times in ten. A miss is not an error by itself; the price bands above are the fair test.
- Nothing here is a forecast or a recommendation. It is a record of Kalshi's prices and Kalshi's settlements.

## Use

The data is free to use under CC BY 4.0. Please credit EVDESK and link to https://evdesk.ai/markets/midterms-2026

Published by [EVDESK](https://evdesk.ai), an independent trading desk for Kalshi traders. Questions and corrections: support@evdesk.ai

The count is updated as the last races settle. Updates go out on X at [@EVDESK1](https://x.com/EVDESK1).

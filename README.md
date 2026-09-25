# AFL Manager V14 — Attribute-Driven Match Engine

V14 builds on V13 and changes the match engine so player-level attributes directly influence match performance instead of Overall being the primary match input.

## Match engine changes
- Simulates both the manager's team and the opponent's actual 22-player roster.
- Uses individual kicking, marking, tackling, clearance, decision-making, contested-ball, fitness, defence and goal-kicking attributes.
- Role affects expected statistical production: DEF, MID, FWD and RUC players behave differently.
- Team strength is derived from the selected players' attributes, but player-level variance remains important.
- Match player ratings are generated from actual match production plus individual attributes.
- Opponent players now accumulate their own simulated match performance as well.
- Fitness affects performance and declines through the match.
- Tactical settings modify the balance of attack, possession, pressure and clearance play rather than simply changing a team-wide Overall score.

## 2026 ratings
V13's 2026 statistical rating model is retained. It uses the 2026 AFL Tables player statistics and role-adjusted percentiles. AFL Tables currently marks the 2026 dataset complete through Finals Week 4.

The game's ratings remain custom game ratings, not official Champion Data ratings. AFL's published player-rating methodology also emphasises impact, context and positional comparison rather than raw possession totals alone.

## Browser cache
If GitHub Pages still shows the previous build, use a cache-busting query such as `?v=14` after deployment.

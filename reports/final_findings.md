# Final Project Findings — Decoding Barça

## Scope

- Competition: La Liga
- Season: 2020/2021
- Matches analyzed: 35
- Results: 22 wins, 6 draws, 7 losses
- Available data source: StatsBomb Open Data

## Investigation 1 — Match Analysis

The notebook compares Barcelona and Villarreal in one selected fixture.
It examines shooting volume, xG, shot locations, and the match's context
relative to Barcelona's other available matches.

## Investigation 2 — How Attacks Develop

The analysis compares shot rates across possession patterns and
possessions with and without selected attacking actions.

These comparisons are descriptive and do not establish causation.

## Investigation 3 — Player Contributions

The player table examines goals, shots, xG, key passes, shot assists,
passes, progressive passes, and defensive events.

The linked-shot xA figure is a custom estimate based on the xG of linked
shots, not an official StatsBomb xA metric. Totals are not adjusted for
minutes played.

## Investigation 4 — Season Outcomes

- Wins: 22
- Draws: 6
- Losses: 7
- Average goals scored per analyzed match: 2.31
- Average xG difference per analyzed match: 1.046

## Limitations

The results cover the matches represented in the downloaded dataset,
not necessarily the complete league season. Match-event statistics,
metric definitions, missing data, and playing time all influence the
interpretation of results.

The project is exploratory and educational. It is not a professional
club performance report.

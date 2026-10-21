PTCG-Arena downloads

Latest round-three build: submission_round3.tar.gz (competition upload), or submission_round3.zip (backup).

Both archives contain only root main.py and deck.csv. This build keeps the tested baseline deck after native-engine deck comparisons: Battle Cage, Hero’s Cape, Lively Stadium, and DeepSeek fixed4 variants did not beat the control in confirmation runs. The agent includes scoped immunity, coloured Energy saturation, projected attack legality, actual effect attachment sources, Spiky retaliation endgame handling, and the current minCount/maxCount range contract.

Validation: 25 regression checks, 20,000 generated legal-menu checks, archive extraction/import checks, and 800 fresh native-engine deck comparison games completed without candidate runtime errors. Tournament leaderboard APIs expose aggregate scores only, so no tournament win-rate claim is made from local matches.

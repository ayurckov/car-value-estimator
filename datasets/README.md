# Dataset provenance

`automobile.csv` is the UCI Machine Learning Repository's Automobile dataset:

- Source: https://archive.ics.uci.edu/dataset/10/automobile
- Original data file: `imports-85.data`
- Records: 201 vehicles with a recorded price (rows with a missing price are excluded)
- Target: `price`

This is historical data for 1985-era automobiles, not a representation of current
used-car listings or current currency values. Some predictor values are missing;
the training notebook imputes them inside the model pipeline to avoid data leakage.

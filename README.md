# Video-Game-Sales
## Analysis and Prediction of Video Games Sales across Regions

This project aims to predict video game sales across different regions
and examine key factors that affect sales in each region. This was done
by extracting common game names and selecting important features
by implementing an ensemble of feature selections. XGBoost models
were then fitted to predict both sales and log of sales in each region.
One additional stacked model was then built by averaging the 2 model
predictions. Theresult shows that in all four regions, the stacked models
perform the best in terms of MSE and Adjusted R2.

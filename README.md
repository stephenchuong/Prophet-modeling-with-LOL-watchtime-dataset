This forecasting project aims to highlght the importance of having domain knowledge in the field of forecasting, espcially when using the Prophet framework

The dataset was gather from https://www.statista.com/statistics/1109350/league-of-legends-hours-watched-twitch/

Two models were created, both using the Prophet framework. The first model (or the baseline model) has no holiday component modeled while the second model( or the refined model) has two holiday components,
Regional tournaments beginning in January and World championship series taking place in October.

The evaluation metrics indicate that the second model performed better than the first model because it was able to better capture the cyclical surge that occur every year around January and October.
Using the interactive comparision chart, as we drag along the different time points, we can see that the refined model was much closer to the actual data than the baseline model.

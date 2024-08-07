# MultiPatchFormer
Official Implementation of the MultiPatchFormer for time series forecasting.
Multi-Patch embedding used prior to giving the series to the Transformer layers. First a temporal encoder is used to capture the dependencies along the temporal dimension and then another cross-channel encdoer is utilized to capture correlations along the variate dimensions. A multi-step liner decoder is devised to decrease overfitting effect.

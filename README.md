# MultiPatchFormer
Official Implementation of the MultiPatchFormer for time series forecasting.
Multi-Patch embedding is applied prior to feeding time series to the Transformer blocks. First a temporal encoder is used to capture the dependencies along the temporal dimension and then another cross-channel encdoer is utilized to capture correlations along the variate dimensions. A multi-step liner decoder is devised to decrease overfitting effect.
The main MultiPatchFormer model is implemented in MultiPatchFormer.py

# In this project, we reuse and adapt relevant functions from related research to our specific research context 
Original source is available at https://github.com/zshicode/attention-clx-stock-prediction
## Citation
```
@article{shi2022attclx,
    author={Zhuangwei Shi and Yang Hu and Guangliang Mo and Jian Wu},
    title={Attention-based CNN-LSTM and XGBoost hybrid model for stock prediction},
    journal={arXiv preprint arXiv:2204.02623},
    year={2022},
}
```

## Requirements

The code has been tested running under Python 3.7.4, with the following packages and their dependencies installed:
```
numpy==1.16.5
sklearn==0.21.3
statsmodels==0.10.1
pandas==0.25.1
tensorflow==2.1.0
keras==2.3.1
xgboost==1.5.0
```

The stock data we used are organized in data folder
The models for stock prediction are contained in scr folder

## Usage

- Run 'ARIMA.ipynb' for ARIMA predictions, and obtaining residuals feature
- Run 'LSTM.ipynb' for the single-layer LSTM, multi-layer LSTM, and bidirectional LSTM models.
- Run 'ARIMA-XGBoost.ipynb' for the hybrid ARIMA-XGBoost model.
- Run 'Att_CNN_LSTM.ipynb' for the hybrid Attention-based CNN-LSTM.


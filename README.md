# Master thesis - Sales forecasting and interpretability analysis
## Comparing LSTM and Transformer models for sales forecasting with interpretability analysis
This repository contains code used to transform the M5 competition Walmart dataset, develop and train LSTM and Transformer model architectures for sales forecasting, and perform interpretability analysis using Saliency, SmoothGrad, DeepLIFT, Integrated Gradients, GradientSHAP and DeepLiftSHAP.

The M5 dataset has been enriched with additional features and economic data retrieved and derived from FRED, including CPI, gas prices, unemployment rate and consumer sentiment.

### Requirements
To run this project you need to install appropriate packages found in requirements.txt. Using Conda environment is recommended.

### Repository structure
1. data - contains external data retrieved from FRED
2. interpretability_results - contains results saved while doing the interpretability analysis
3. misc - miscellaneous, notebooks used for exploring the data and some testing
4. model training - main notebooks containing the notebooks used for training
4. models - the trained models
5. notebooks - notebooks used for plotting, data exploration and analysis
6. thesis_paper - contains the main thesis document written for submission

### M5 Walmart dataset
The M5 Walmart dataset can be found here:
[M5 Forecasting Accuracy](https://www.kaggle.com/competitions/m5-forecasting-accuracy)

### FRED series codes
The FRED series data was selectively downloaded for the period of 2011-2016

| GAS | CPI | UR | CS |
|---|---|---|---|
| GASREGCOVGCW | CPIAUCSL | CAUR | UMCSENT |
| GASREGMWW | CUURA421SA0 | TXUR | |
| GASREGWCW | CUUSA424SA0 | WIUR | |
| APU000074714 | CUURA422SA0 | UNRATE | |
| | CUURA316SA0 | | |
| | CUURA318SA0 | | |
| | CUURA207SA0 | | |
| | CUUSA212SA0 | | |
| | CUUSA211SA0 | | |

### Thesis paper
The link to the thesis paper, or the paper itself, will be provided here after it has been graded.

## License
This project is licensed under the MIT License - see the [LICENSE](https://github.com/BudJulius/masterthesis-m5-interpretability/blob/main/LICENSE) file for details.
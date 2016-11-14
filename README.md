# TimeFlow
Tensorflow for Time Series Applications

**TimeFlow** is a library for building tensorflow models for time series problems. It can be used for time series prediction as well as time series classification. The key features of this library are

* Allows stacking of pre built layers. The layers currently available are
    * LSTM(Long Short Term Memory)
    * Regression
    * Deep Neural networks
* Automated training monitor
* Feature generation for irregular time series
* Other utility functions to facilitate building models

### Installation
Preinstall Tensorflow before installing TimeFlow. To install the package via github,
```{bash}
git clone https://github.com/abhishekmalali/TimeFlow.git
cd TimeFlow
python setup.py install
```

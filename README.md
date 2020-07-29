# MNE_ML

This is the example of the experiment using preprocessing methods from the `MNE` library and classification methods from the `Keras` and the `scikit-learn` libraries for EEG data stored in the `BrainVision` format.

The used dataset in the `BrainVision` format, which is located in the _PROJECT_DAYS_P3_NUMBERS_ folder, is described in the https://www.nature.com/articles/sdata2016121

## Used preprocessing methods:
- low-pass and high-pass filtering
- epoch extraction
- baseline correction
- artifact removal with the peak-to-peak amplitude rejection
- windowed means feature extraction

## Used classifiers:
- Convolutional neural network
- LSTM neural network
- Linear discriminant analysis
- Support vector machines

Detailed description of the whole experiment with an explanation of the code is located in the Wiki.

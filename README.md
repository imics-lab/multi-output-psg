# Multi-Output PSG (Polysomnography)

This is code for our work to build a multi-output model that predicts both Cardiac and Respiratory abnormal events in the [PSG-Audio Dataset](https://www.nature.com/articles/s41597-021-00977-w)

We are using a processed version of the dataset with shared google drive links.   Please see our [load data time-series repository](https://github.com/imics-lab/load_data_time_series) for code and details on the raw data conversion.

A paper outlining some of the challenges with two differently and highly imbalanced classes is under review.

Currently, we are working to integrate and tune sample_weights individually for the cardiac and respiratory events within the model.


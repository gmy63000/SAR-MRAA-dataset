# SAR-MRAA-dataset
To address the problem of missing SAR data for the MRAA task, we constructs a SAR-MRAA dataset encompassing training, validating, testing sets and predictive data. The data source was Sentinel-1 SAR imagery of raft aquaculture areas with a large aquaculture scale in Chinese coastal cities. To verify the generalization ability of the model, the test data were divided into two main categories: one included the test data and the training data be-longing to the same province (TTSP) (e.g., Liaoning Province), and the other included the test data and the training data belonging to different provinces (TTDP). Specifically, raft aquaculture areas in 2020 in the coastal cities of Liaoning and Fujian provinces in China were used for training, validation, and test datasets in the same region, respectively, while raft aquaculture areas in 2020 in the coastal cities of Zhejiang and Guangdong provinces were used for test datasets in the non-same region. In addition to the training, validation, and test sets, the SAR-MRAA datasets also included predictive data used to test the inference time of the model and integral MRAA extraction for coastal provinces.

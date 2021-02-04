# data_preprocessing_public

This repo serves the purpose of reading, preprocessing and queue data from local database for future tensorflow training.

## Structure
Preprocessor.py - preprocess data
db_manager.py - database specific reading and extracting
stock_data_reader.py - main function

Run:
python stock_data_reader.py

## release
**May 2020. This is a stable release version.**

After two years beta version since first release in 2018, this is the first version available as stable release. 

New features:
* Support to Tensorflow 2.1+
* New batch transformation
* Adding log return feature
* Optimize time series data flow at non-GPU end
* New deque operations





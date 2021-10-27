#Direct elution data processing code

This folder includes the two data processing codes utilized in the processing of the direct injection data.

DataAnalyzerWorker.py includes calling functions and sets up the constants necessary to process the data.

DataAnalyzerWithPeakInteg.py includes functions that process RAW files (fron .txt format exported by FT Statistic) to extract out intensities and convert to counts. 
Other functions central to data analysis are also included in this file, such as the computation of standard deviation for each acuqisition.
CSV files with processed statistics are output to the folder where the code is stored.


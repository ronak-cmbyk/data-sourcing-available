## README

- This program uses .json-formatted data from NASA's Coronal Mass Ejection (CME) and Geomagnetic Storm (GST) APIs to create dataframes using the Pandas library.

- The program looks between two specific dates in order to create a common, merged dataframe from the two data sets.

- The data can be used to interpret linked events between the two research bases as well as the time difference between two occurrences (between the specified dates), amongst much other information.

- rows with missing IDs for both/either GST and CME have been removed since they cannot be merged into a common dataframe.

- The retrieve_data.ipynb may have trouble rendering on Github since it is a larger file. However, it should be able to load after giving it some time to refresh. If not the downloaded file, will give the full code that is not able to be rendered on Github.

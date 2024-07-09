# BachelorsThesis

This GitHub project provides the accompanying datasets and catalogs to the Bachelor Thesis by Nicolas Krieger with the title **"On the Classification of Blazars"**.

In the directory **InitialCatalog**, a list of the 6747 blazars with an identifier, type, right ascension, declination, and redshift is provided as an Excel sheet or CSV file.

In the directory **Dataset**, you can find a corresponding folder to each of those blazars. These are named "right ascension of the blazar," underscore "declination of the blazar," and contain all the information used for the analysis. This includes:
1. The SED data as text and CSV files
2. A text file with the hydrogen column density $n_h$ given in the unit 1 / $cm^{-2}$
3. A text file with the BlaST and W-peak synchrotron peak prediction, including W-peak warning and angular distance to the closest source of confusion
4. A PNG plot of the NEOWISE infrared flux and slope
5. A PNG plot displaying the SED data together with the BlaST and W-peak synchrotron peak predictions

In the directory **FinalCatalog**, all the information given in the dataset is summarized in an Excel sheet or CSV file, together with the revised classification of the blazar if one could be provided.

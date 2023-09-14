# Rapid-identification-and-quality-grading-of-Radix-Bupleuri
Original Data and Code for the Paper _Machine Learning-Assisted Raman Spectroscopy for Rapid Classification and Regression Prediction of Radix Bupleuri_.
Taking Bupleuri Radix as an example, a research method integrating machine learning and chemical analysis has been developed for rapid identification of types and origins, as well as quality grading, of Chinese herbal materials.In this study, a total of 119 Radix Bupleuri samples were collected, including samples from different origins and different Variety.

The project structure is as follows:
* code.ipynb
* data
    * HPLC datasets.xlsx
    * computed and computed spectrum.xlsx
    * Raman datasets(black vs. others).xlsx
    * Raman datasets(wild vs cultivated).xlsx
    * Raman datasets(different region).xlsx
    * Raman datasets(with major component content).xlsx

## 1.HPLC datasets.xlsx
_HPLC datasets.xlsx_ contains HPLC data of 119 Radix Bupleuri samples

## 2.computed and computed spectrum.xlsx
_computed and computed spectrum.xlsx_ cansis

## 3.Raman datasets(black vs. others).xlsx
_Raman datasets (black vs. others).xlsx_ contains information about the Variety of 119 Chaihu samples. The samples have been divided into "black Radix Bupleuri" () and "other Radix Bupleuri" ().The "type" column represents the labels for the data, where 1 stand for black Radix Bupleuri and 0 stand for other Radix Bupleuri.

## 4.Raman datasets(wild vs cultivated).xlsx
Similarly, _Raman datasets (black vs. others).xlsx_ also contains information about the Variety of 119 Chaihu samples. The samples have been divided into "wild Radix Bupleuri" () and "cultivated Radix Bupleuri" ().The "type" column represents the labels for the data, where 1 stand for cultivated Radix Bupleuri and 0 stand for wild Radix Bupleuri.

## 5.Raman datasets(different region).xlsx
_Raman datasets(different region).xlsx_ contains information about the origins of 119 samples. A total of three regions, Inner Mongolia, Gansu, and Shaanxi, were included in the collection of Radix Bupleuri samples. Specifically, there is one sample from Inner Mongolia, two samples from Gansu, and three samples from Shaanxi. The "type" column represents the labels for the data, with 0 indicating Inner Mongolia, 1 indicating Gansu, and 2 indicating Shaanxi.

## 6.Raman datasets(with major component content).xlsx
_Raman datasets (with major component content).xlsx_ contains the content of the major components (SSa, SSc, SSd) measured in 119 samples.

## 7.code.ipynb
In the file _code.ipynb_, you will find all the code for this manuscript, which is primarily divided into four main parts.
>(1).Generation of Spectra and Chromatographic Images<br\>
>(2)Region Discrimination and Variety Discrimination of Radix Bupleuri<br\>
>(3)Feature Extraction Based on XGBoost<br\>
>(4)Regression Analysis for the Determination of Major Component Content

# Use of econometrics and machine learning models to predict the number of new cases per day of COVID-19 - Code and datasets
## Description
This repository contains the code and datasets for the paper Use of econometrics and machine learning models to predict the number of new cases per day of COVID-19, accepted at the SBCAS 2020 (20º Simpósio Brasileiro de Computação Aplicada à Saúde) scientific event. Descriptions of the implementation and the dataset are contained in the paper (link: XXX, the link will be inserted once it is available).

The code was developed by Bruna Lobato Barreira and Roberto Fray da Silva.

Reference of the paper: XXX (reference of the paper).
To cite this repository: XXX (reference of the paper)

## To Do (further research, out of the scope of this paper):
- optimize code for deployment in production (there are several parts of the code that can be improved)
- deploy code for daily evaluation
- incorporate new variables (socioeconomic, population density, etc) and more recent data
- automate data collection
- automate model choice and hyperparameters (AutoML with Optuna?)
- optimize gridsearch for arima and sarima (Optuna?)
- evaluate other models, both unsupervised and supervised
- evaluate other options of feature engineering

## Credits for the code:
The code was implemented using Google Colab to improve replicability (https://colab.research.google.com/) and was based on the following:
- Decision Tree Regression with AdaBoost from the scikit-learn library tutorial: https://scikit-learn.org/stable/auto_examples/ensemble/plot_adaboost_regression.html#sphx-glr-auto-examples-ensemble-plot-adaboost-regression-py
- SARIMAX: Introduction from the statsmodels library tutorial: https://www.statsmodels.org/dev/examples/notebooks/generated/statespace_sarimax_stata.html
- SARIMAX: Model selection, missing data from the statsmodels library tutorial: https://www.statsmodels.org/dev/examples/notebooks/generated/statespace_sarimax_internet.html

The authors would like to thank the authors of the codes for providing them as examples for the use of the libraries and model implementation. 

The authors would also like to thank all the developers that were and are involved on the development of the following Python libraries: 
- Statsmodels: https://www.statsmodels.org/stable/index.html
- Pandas: https://pandas.pydata.org/
- Scikit-Learn: https://scikit-learn.org/
- Matplotlib: https://matplotlib.org/
- NumPy: https://numpy.org/
- Seaborn: https://seaborn.pydata.org/

## Credits for the dataset:
The authors would like to thank the following institutions/researchers for providing the data collected:
- World Bank: total population: http://wdi.worldbank.org/table/2.1#
- Coronavirus (COVID-19) - Brazil Dataset by Raphael Fontes: original data minus number of recovered patients: https://www.kaggle.com/unanimad/corona-virus-brazil
- Data Science for COVID-19 (DS4C) - South Korea dataset by datartist et al.: original data: https://www.kaggle.com/kimjihoo/coronavirusdataset#Case.csv
- Novel Corona Virus 2019 Dataset - China dataset by SRK: original data: https://www.kaggle.com/sudalairajkumar/novel-corona-virus-2019-dataset
- COVID-19 in Italy - Italy Dataset by SRK: original data: https://www.kaggle.com/sudalairajkumar/covid19-in-italy#covid19_italy_region.csv
- Johns Hopkins University CSSE [Dong, Du, Gardner, 2019]: number of recovered patients for Brazil: https://github.com/CSSEGISandData/COVID-19  and  Dong, E., Du, H., Gardner, L. (2020) "An interactive web-based dashboard to track COVID-19 in real time". The Lancet Infectious Diseases, Correspondence, p.1-2.

## Acknowledgements:
This work was supported by the Coordenação de Aperfeiçoamento de Pessoal de Nível Superior - Brazil (CAPES) - Finance Code 001, Itaú Unibanco S.A. through the Itaú Scholarship Program, at the Centro de Ciência de Dados (C2D), Universidade de São Paulo, Brazil, and also by the National Council for Scientific and Technological Development (CNPq).

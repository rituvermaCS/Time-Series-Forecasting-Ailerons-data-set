FROM jupyter/scipy-notebook

COPY Weather_data.csv ./Weather_data.csv
COPY ailerons_train.csv ./ailerons_train.csv

COPY Time_Series_ForeCasting.ipynb ./Time_Series_ForeCasting.ipynb
COPY Ailerons_data_set.ipynb ./Ailerons_data_set.ipynb


RUN python3 Time_Series_ForeCasting.ipynb
RUN python3 Ailerons_data_set.ipynb

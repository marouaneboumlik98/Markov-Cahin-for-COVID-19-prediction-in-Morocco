# Markov_Chain for COVID-19 prediction : Morocco

Coronavirus disease, also known as Covid-19, is a new illness that was discovered at the end of 2019. It is caused by a virus called SARS-CoV-2 (Severe Acute Respiratory Syndrome Coronavirus 2). The first case of this disease was reported on December 31, 2019, in Wuhan, China, and has since spread to all countries. It has some common symptoms such as fever, cough, and in severe cases, it can cause pneumonia, severe acute respiratory syndrome, kidney failure, or even death.

The disease quickly spread to all countries. On January 30, 2020, the WHO declared it a Public Health Emergency of International Concern (PHEIC). As of September 2023, there are more than 770 million confirmed cases, causing nearly 7 million deaths. It is predicted that the number of confirmed cases will continue to rise. In Morocco, the number of confirmed cases is 1,276,635 with 16,279 deaths.

There is extensive research discussing the spread of the pandemic caused by the virus using mathematical modeling. In this report, a discussion on the long-term prediction of the spread of Covid-19 is presented using stationary distribution Markov chains. The objective of this study is to analyze the prediction of long-term infected individuals.

## Methods

In this study, the discrete-time Markov chain is used to analyze the dataset. The dataset must be checked to determine if it is recurrent positive, aperiodic, and irreducible or not. This study aims to obtain the stationary distribution of the given data, which can only be achieved if the dataset meets all the above conditions.

## Dataset

In this study, the daily Covid-19 case data in Morocco from December 31, 2021, to September 14, 2023, are analyzed [Covid_Data](https://github.com/owid/covid-19-data/tree/master/public/data). The data on daily Covid-19 cases in Morocco during the given period are presented in  [Figure 1](img/Distribustion_Covid.png).


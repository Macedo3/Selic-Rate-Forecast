# Selic Rate Forecast

## 👨‍🎓 Developers: 
- <a href="https://www.linkedin.com/in/gabriel-demacedosantos/">Gabriel de Macedo Santos</a>
- <a href="https://www.linkedin.com/in/sophianobrega/">Sophia Nóbrega</a>
- <a href="https://www.linkedin.com/in/henrique-cox-4644bb270/">Henrique Cox</a>


## 📜 Description

### Project Description

This project aims to predict the next Brazilian interest rate (Selic rate) considering various influential factors such as the American interest rate, oil price fluctuations, BRL/USD exchange rate variations, unemployment rate, IPCA (Consumer Price Index for Broad Consumer Market) changes, and economic activity. 

The development of this predictive model heavily relied on both economic expertise and machine learning techniques. Utilizing a wealth of domain knowledge in economics, several business rules were incorporated into the modeling process. The model was crafted using the ExtraTreesRegressor algorithm, which demonstrated superior performance compared to other models.

### Key Variables Considered:
- **American Interest Rate**: Influence from the US interest rate on the Brazilian interest rate.
- **Oil Price Fluctuations**: Impact of variations in oil prices on the Selic rate.
- **BRL/USD Exchange Rate**: Effects of currency exchange rate changes on interest rates.
- **Unemployment Rate**: Relationship between unemployment levels and the Selic rate.
- **IPCA Changes**: Influence of Consumer Price Index fluctuations on the interest rate.
- **Economic Activity**: Impact of overall economic activity on determining the Selic rate.

### Model Development Approach:
The development process integrated economic theories and principles into the machine learning framework. The utilization of the ExtraTreesRegressor model was informed by rigorous testing and evaluation, demonstrating its superior performance in accurately predicting the Selic rate based on the provided variables.

This project stands as an amalgamation of economic domain expertise and machine learning methodologies, combining the best of both worlds to forecast the critical Brazilian interest rate, the Selic rate, with enhanced accuracy and efficiency.

## 📁 Folder structure

### Project Documentation

1. **Data**: Stores the datasets used in the project.
   - `df_mensal.xlsx`: Relevant monthly dataset.
   - `taxas_de_juros.xlsx`: Interest rates data used in the model.
   - `USD_BRL Dados Históricos.xlsx`: USD/BRL historical data.

2. **model**: Contains the `model.ipynb` file where training and configuration of the Selic rate prediction model are performed.

3. **Analysis**: Directory housing the `exploratory-analysis.ipynb` file for conducting exploratory data analysis.

4. **README.md**: Explanatory document detailing the project's structure and how to execute the code.

5. **LICENSE**: License file defining the terms of use for the project.

### Directory Structure

```
├── data
│   ├── df_mensal.xlsx
│   ├── taxas_de_juros.xlsx
│   └── USD_BRL Dados Históricos.xlsx
├── model
│   └── model.ipynb
├── analysis
│   └── exploratory-analysis.ipynb
├── README.md
└── LICENSE
```

## 🔧 Installation

### Installation Guide

To run the project successfully, follow these steps to set up the required libraries:

1. **Python Installation**: Ensure Python is installed on your system. You can download it from [Python's official website](https://www.python.org/downloads/).

2. **Library Installation**:
    - Install required libraries using `pip` command:
        ```bash
        pip install pandas numpy seaborn matplotlib pycaret scikit-learn
        ```

3. **Jupyter Notebook Installation (Optional)**: If you prefer using Jupyter Notebook:
    - Install Jupyter Notebook using `pip`:
        ```bash
        pip install jupyterlab
        ```

### Additional Libraries Used in the Project

The project utilizes the following libraries:
- `pandas` and `numpy` for data manipulation and computation.
- `seaborn` and `matplotlib` for data visualization.
- `pycaret` for streamlining machine learning workflows.
- `scikit-learn` for various machine learning algorithms and tools.

### Usage Instructions

1. **Data Collection**:
    - Place the necessary datasets (`df_mensal.xlsx`, `taxas_de_juros.xlsx`, `USD_BRL Dados Históricos.xlsx`) in the `Data` directory of the project.

2. **Exploratory Analysis**:
    - Open and execute the `exploratory-analysis.ipynb` file located in the `Analysis` directory using Jupyter Notebook or any compatible platform.

3. **Model Training**:
    - Utilize the `model.ipynb` file inside the `model` directory for training and configuring the Selic rate prediction model.


## 🗃 Release history

* 0.5.0 - XX/XX/2023
    * 
* 0.4.0 - XX/XX/2023
    * 
* 0.3.0 - XX/XX/2023
    * 
* 0.2.0 - 07/12/2023
    * Model Finished.
    * README.md Finished.
* 0.1.0 - 06/12/2023
    * Starting develop the model.

## 📜 References

Bibliografia
Banco Central do Brasil. Disponível em: <https://www.bcb.gov.br/estatisticas/detalhamentoGrafico/graficosestatisticas/taxadesocupacao>. Acesso em: 7 dez. 2023a.


Banco Central do Brasil. Disponível em: <https://www.bcb.gov.br/estatisticas/detalhamentoGrafico/graficosestatisticas/precos>. Acesso em: 7 dez. 2023b.


Banco Central do Brasil. Disponível em: <https://www.bcb.gov.br/estatisticas/detalhamentoGrafico/graficosestatisticas/metaselic>. Acesso em: 7 dez. 2023c.


Banco Central do Brasil. Disponível em: <https://www.bcb.gov.br/estatisticas/detalhamentoGrafico/graficosestatisticas/ibcbr>. Acesso em: 7 dez. 2023d.


Banco Central do Brasil. Disponível em: <https://www.bcb.gov.br/estatisticas/detalhamentoGrafico/graficosestatisticas/cambio>. Acesso em: 7 dez. 2023e.


DE GEOGRAFIA E ESTATÍSTICA, I. B. Inflação. Disponível em: <https://www.ibge.gov.br/explica/inflacao.php>. Acesso em: 7 dez. 2023.


Preços Históricos USD/BRL - Investing.com. Disponível em: <https://br.investing.com/currencies/usd-brl-historical-data>. Acesso em: 7 dez. 2023.


RAMIREZ, P. Petróleo Brent Futuros Preços Hoje - Investing.com. Disponível em: <https://br.investing.com/commodities/brent-oil>. Acesso em: 7 dez. 2023.



## 📋 License

Copyright 2023 <a href="https://www.linkedin.com/in/gabriel-demacedosantos/">Gabriel de Macedo Santos</a>, <a href="https://www.linkedin.com/in/sophianobrega/">Sophia Nóbrega</a> and <a href="https://www.linkedin.com/in/henrique-cox-4644bb270/">Henrique Cox</a>

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the “Software”), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
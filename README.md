Soluções em Energias Renováveis e Sustentáveis
Instruções da Entrega

Este repositório contém um notebook Jupyter (CP2-Sers.ipynb) com a resolução dos exercícios propostos sobre regressão e classificação aplicadas a dados de energia solar, eólica e elétrica.

Como visualizar:

Abra o notebook diretamente no Google Colab

Caso deseje executar localmente:

pip install pandas numpy scikit-learn matplotlib seaborn jupyter
jupyter notebook


Em seguida, abra o arquivo CP2-Sers.ipynb.

Dataset 1 – Appliances Energy Prediction

Fonte: UCI Machine Learning Repository

Descrição: Contém dados ambientais de uma residência (temperatura, umidade, hora, etc.) e o consumo de energia dos eletrodomésticos (Wh).
Objetivo: Prever o consumo de energia usando modelos de regressão (Regressão Linear, Árvore de Regressão e Random Forest).
Principais variáveis: T1, RH_1, T_out, Windspeed, Appliances.

Dataset 2 – Smart Grid Stability

Fonte: Kaggle – Smart Grid Stability Dataset

Descrição: Dados simulados de uma rede elétrica inteligente com variáveis como potência ativa, reativa, tensão e corrente.
Objetivo: Classificar se a rede está Estável ou Instável, usando modelos como Árvore de Decisão, KNN e Regressão Logística.
Principais variáveis: tau1, tau2, p1, p2, stabf.

Dataset 3 – Solar Radiation Prediction

Fonte: Kaggle – Solar Radiation Prediction Dataset

Descrição: Dados meteorológicos (temperatura, pressão, vento, umidade) usados para prever radiação solar.
Objetivo: Classificar períodos em Alta Radiação ou Baixa Radiação com base na mediana.
Principais variáveis: Temperature, Pressure, Humidity, Speed, Radiation.

Dataset 4 – Wind Turbine SCADA

Fonte: Kaggle – Wind Turbine SCADA Dataset

Descrição: Dados de operação de turbinas eólicas (velocidade do vento, direção, potência).
Objetivo: Prever a potência gerada (kW) a partir das condições do vento.
Principais variáveis: Wind Speed (m/s), Wind Direction (°), Theoretical_Power_Curve (KWh), LV ActivePower (kW).

Modelos Utilizados

Classificação: Árvore de Decisão, Random Forest, SVM, KNN, Regressão Logística

Regressão: Regressão Linear, Árvore de Regressão, Random Forest Regressor

Métricas de Avaliação:

Classificação → Acurácia, Matriz de Confusão, F1-score

Regressão → RMSE, R², MAE

Objetivos de Aprendizagem

Diferenciar tarefas de classificação e regressão.

Aplicar bibliotecas de análise e aprendizado de máquina em Python.

Compreender como dados de energia podem apoiar decisões sustentáveis.

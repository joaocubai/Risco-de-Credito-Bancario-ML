# Risco-de-Credito-Bancario


Este repositório contém o código, em python,  da monografia apresentada ao Instituto de Ciências Matemáticas e Computacionais da 
Universidade de São Paulo, como requisito parcial para obtenção do título de Especialista (MBA) em Ciência de Dados.


TEMA: **Análise de Crédito Bancário: Aplicação de Algoritmos de Machine Learnig**

OBJECTIVOS

Desenvolver modelo de análise de crédito bancário através da aplicação de algoritmos de Machine Learning, nomeadamente: 
- Regressão Logística;
- Naive Bayes;
- Random Forest;
- Redes Neurais Artificiais;
- Support Vector Machines (SVM); e
- Extreme Gradient Boosting (XGBoost)

METODOLOGIA
- Foi utilizada a  técnica de validação cruzada estratificada (visto que o _dataset_ era desbalanceado), com 10 dobras (folds) em 30 repetições;
- Métricas de avaliação de desemenho dos modelos adoptadas: Acurácia, Precisão, Recall, F1-Score, AUC-ROC e teste KS (Kolmogorov-Smirnov);
- Foram conduzidos testes estatísticos para comparação do desempenho entre os modelos;
- A AUC-ROC foi a métrica escolhida para efeito de comparação entre modelos.
- Os testes realizados são: Shapiro-Wilk (normalidade), Levene (homocedasticidade), Friedman e, como post-hoc, o teste de Nemeny.
- Realizou-se a análise SHAP, que fornece uma visão de como o modelo seleccionado toma decisão sobre o risco de inadimplência.


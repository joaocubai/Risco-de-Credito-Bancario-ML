# Risco-de-Credito-Bancario

**Análise de Crédito Bancário: Aplicação de Algoritmos de Machine Learnig**

**Objectivo**

Desenvolver modelo de análise de crédito bancário através da aplicação de algoritmos de Machine Learning, nomeadamente: 
- Regressão Logística;
- Naive Bayes;
- Random Forest;
- Redes Neurais Articiais;
- Support Vector Machines (SVM); e
- Extreme Gradient Boosting (XGBoost)

**Metodologia**
- Foi utilizada a  técnica de validação cruzada estratificada (visto que o _dataset_ era desbalanceado), com 10 dobras (folds) em 30 repetições;
- Métricas de avaliação de desemenho dos modelos: Acurácia, Precisão, Recall, F1-Score, AUC-ROC e teste KS (Kolmogorov-Smirnov);
- Foram conduzidos testes estatísticos para comparação do desempenho entre os modelos.
- A AUC-ROC foi a métrica escolhida para efeito de comparação.
- Os testes realizados são: Shpapiro-Wilk (normalidade), Levene (homocedasticidade), Friedman e, como post-hoc, o teste de Nemeny.
- Realizou-se a análise SHAP, que fornece uma visão de como os modelos tomam decisão sobre o risco de inadimplência.


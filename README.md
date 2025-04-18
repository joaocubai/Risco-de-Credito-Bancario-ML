# Risco-de-Credito-Bancario


Este repositório contém o código, em python,  da monografia apresentada ao Instituto de Ciências Matemáticas e de Computação da 
Universidade de São Paulo (USP), como requisito parcial para obtenção do título de Especialista (MBA) em Ciência de Dados.


TEMA: **Análise de Risco de Crédito Bancário: Aplicação de Algoritmos de Machine Learning**

OBJECTIVO

Desenvolver modelo de análise de risco de crédito bancário através da aplicação de algoritmos de Machine Learning, nomeadamente: 
- Regressão Logística;
- Naive Bayes;
- Random Forest;
- Redes Neurais Artificiais;
- Support Vector Machines (SVM); e
- Extreme Gradient Boosting (XGBoost)

METODOLOGIA
- Foi utilizada a  técnica de validação cruzada estratificada (visto que o _dataset_ era desbalanceado), com 10 dobras (folds) em 30 repetições;
- As métricas de avaliação de desemenho dos modelos adoptadas são: Acurácia, Precisão, Recall, F1-Score, AUC-ROC e teste KS (Kolmogorov-Smirnov);
- Foram conduzidos testes estatísticos para comparação do desempenho entre os modelos;
- A AUC-ROC foi a métrica escolhida para estabelecer a comparação entre os modelos;
- Foram feitos testes estatísticos pévios para verificar a normalidade (teste de Shapiro-Wilk) e homocedasticidade (teste de Levene);
- Tendo-se verificado a violação dos pressupostos da normalidade e da homocedasticidade, foi aplicado o bootstrap, um método não paramétrico;
- A partir das reamostras obtidas pelo método bootstrap, foram construídos intervalos de confiança, com nível de significância de 5%;
- Os intervalos de confiança serviram como base para comparação emparelhada do desemepnho entre modelos;
- Finalmente, foi realizada a análise SHAP (SHapley Additive exPlanations), que fornece uma visão sobre a forma como o modelo seleccionado toma decisão sobre o risco de crédito, garantido transparência no processo decisório.


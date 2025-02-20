# Trabalho de conclusão de disciplina de Fundamentos de Ciências de Dados e Inteligência de negócios 📚
### Consultoria de uma empresa fictícia para compradores de aeronaves ✈️

Aplicação para técnicas de governança de dados e construção de modelo de Machine Learning, incluindo **EDA**, apresentação de tendências, tratamentos de dados, outliers e gráficos para futuro Storytelling pra stakeholders e escolha de um framework metodológico (CRISP-DM, SEMMA ou DAMA-DMBOK).

Aplicação de justificativa de escolha de modelo, explicação de dados de entrada, variáveis preditoras e avaliação de desempenho do modelo escolhido, após comparado com outros modelos.

### Fonte de dados utilizada para dataset: https://www.kaggle.com/code/h4hemant/airplane-price-analysis-prediction

### Etapas concluídas 🚀
- **Leitura e análise de dados:** Exploração dos dados
- **Tratamento de dados:** Verificação de valores ausentes, mudança de nomes de colunas, uso de *binning* para transformação de variáveis, seleção de colunas relevantes.
- **Normalização**
- **Utilização de métricas para previsões**
-- MAE (Erro Absoluto Médio)
-- MSE (Erro Quadrático Médio)
-- R² (Coeficiente de Determinação)
- **SHAP:** Indentificação de importância de variáveis
- **Comparação entre modelos:**
-- Linear Regression
-- Random Forest Regression
-- Decision Tree Regressor
- **Simulação de casos de uso**
-- Predição com diferentes compras e perfis de clientes
- **Avaliação da qualidade de previsões do melhor modelo**
-- Análise do gráfico de dispersão
-- Análise da distribuição de resíduos
  
<br></br>
|⚔️ COMPARAÇÃO ENTRE OS MODELOS|MAE                          |MSE                         |R²                           |
|----------------|-------------------------------|-----------------------------|--------------------------|
|Regressão Linear               |54146162.19785749       |5211601017802536.0           |0.9025020764084212|
|Random Forest                  |18296753.233630717      |1248099633801526.5           |0.9766507216658792|
|Decision Tree Regressor        |22406421.397854738      |1867159739298715.5           |0.9650694293416618|

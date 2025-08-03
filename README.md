# challenge-telecom-x-2

# Previsão de Evasão de Clientes - TelecomX

Este projeto utiliza técnicas de Machine Learning para prever a evasão de clientes (churn) em uma empresa de telecomunicações, identificando os principais fatores que influenciam a saída dos clientes e propondo estratégias de retenção.

## Estrutura do Projeto

- `notebook.ipynb`: Notebook principal com todo o fluxo de análise, modelagem e avaliação.
- `TelecomX_Data_Tratado.csv`: Base de dados tratada utilizada para os experimentos.

## Etapas Realizadas

1. **Análise Exploratória**  
   - Visualização das distribuições e correlações das variáveis.
   - Identificação de desequilíbrio entre as classes.

2. **Pré-processamento**  
   - Codificação de variáveis categóricas.
   - Balanceamento das classes com SMOTE.
   - Normalização dos dados para modelos sensíveis à escala.

3. **Modelagem**  
   - Regressão Logística (com normalização).
   - Random Forest (sem normalização).
   - Avaliação dos modelos com métricas: acurácia, precisão, recall, F1-score e matriz de confusão.

4. **Análise de Importância das Variáveis**  
   - Coeficientes da Regressão Logística.
   - Importância das variáveis no Random Forest.

5. **Relatório e Estratégias de Retenção**  
   - Identificação dos principais fatores de evasão.
   - Propostas de ações para retenção de clientes.

## Principais Fatores de Evasão

- Tempo de contrato (`tenure`)
- Total gasto (`TotalCharges`)
- Serviços adicionais contratados
- Tipo de contrato
- Método de pagamento

## Como Executar

1. Instale as dependências:

2. Execute o notebook `notebook.ipynb` no Jupyter ou no PyCharm.

## Resultados

- Random Forest apresentou melhor desempenho geral.
- Estratégias de retenção sugeridas com base nos fatores identificados.

## Licença

Projeto acadêmico para fins de estudo.
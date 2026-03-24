# 🛡️ Detecção de Anomalias em Transações de Cartão de Crédito

Este projeto aplica técnicas de **Ciência de Dados** e **Machine Learning** para identificar transações fraudulentas em cartões de crédito. O foco principal é lidar com o desafio de dados altamente desbalanceados, onde as fraudes representam uma fração mínima do total.

## 📌 Contexto do Problema
Identificar fraudes é essencial para instituições financeiras evitarem prejuízos bilionários e garantirem a segurança do cliente. Tecnicamente, o maior desafio é o **desequilíbrio de classe**: em datasets reais, menos de 0,2% das transações costumam ser fraudulentas.

## 🛠️ Ferramentas e Bibliotecas
- **Linguagem:** Python
- **Bibliotecas:** Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib.
- **Técnicas:** SMOTE (Synthetic Minority Over-sampling Technique) para balanceamento e StandardScaler para normalização.

## 📊 Pipeline do Projeto
1. **Análise Exploratória:** Verificação de outliers, distribuição das classes e correlação das variáveis.
2. **Pré-processamento:** Escalonamento das variáveis `Amount` e `Time`.
3. **Tratamento de Dados:** Aplicação de [SMOTE ou Under-sampling] para equilibrar o treinamento do modelo.
4. **Modelagem:** Implementação de algoritmos como [Random Forest / XGBoost / Logistic Regression].
5. **Avaliação:** Uso de métricas como **Precision-Recall Curve**, **F1-Score** e **Matriz de Confusão**.

## 📈 Principais Resultados
- **Recall:** [Insira a % de recall aqui]% - Priorizamos o Recall para garantir que o maior número possível de fraudes fosse detectado.
- **AUPRC:** [Insira o valor]% - Métrica robusta para avaliar o desempenho em classes raras.

## 📂 Estrutura do Repositório
- `notebook.ipynb`: Arquivo original do Google Colab com análises e gráficos.
- `main.py`: Código Python estruturado para execução.

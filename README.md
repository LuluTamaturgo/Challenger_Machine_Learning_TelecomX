# 📊 Previsão de Evasão de Clientes (Churn Prediction)

Este projeto tem como objetivo prever a evasão de clientes com base em dados históricos de comportamento e serviço. Através de técnicas de análise exploratória e modelagem preditiva, identificamos os principais fatores que levam um cliente a cancelar o serviço, propondo estratégias para retenção.

---

## 🧠 Objetivos

- Identificar os fatores que influenciam a evasão de clientes.
- Construir modelos preditivos capazes de classificar clientes propensos a evadir.
- Avaliar e comparar o desempenho dos modelos.
- Propor ações com base nos insights obtidos.

---

## 📁 Estrutura do Projeto

## 📁 Estrutura do Projeto

```plaintext
├── dados/
│   └── copia_dados_encoded.csv         # Base de dados tratada
├── notebooks/
│   ├── 01_analise_exploratoria.ipynb   # Análise exploratória (EDA)
│   ├── 02_modelagem_preditiva.ipynb    # Modelos de classificação
│   ├── 03_avaliacao_modelos.ipynb      # Avaliação dos modelos
│   └── 04_importancia_variaveis.ipynb  # Análise das variáveis
├── imagens/
│   ├── boxplot_tempo_contrato.png
│   └── matriz_confusao_rf.png
├── README.md                           # Este arquivo
```

---

## 🛠️ Tecnologias Utilizadas

- Python (Pandas, Numpy, Scikit-learn, Matplotlib, Seaborn)
- Jupyter Notebook
- Git e GitHub

---

## 🔍 Etapas Realizadas

### 📌 Análise Exploratória
- Tratamento de dados nulos e codificação de variáveis.
- Avaliação da correlação entre variáveis e evasão.
- Visualizações com boxplots e scatterplots.

### 🤖 Modelagem Preditiva
Modelos aplicados:
- Regressão Logística (com normalização)
- Random Forest (sem normalização)

### 📈 Avaliação dos Modelos
Métricas utilizadas:
- Acurácia, Precisão, Recall, F1-score
- Matriz de Confusão
- Análise de overfitting/underfitting

### 🌟 Importância das Variáveis
- Regressão Logística: coeficientes das variáveis
- Random Forest: importância baseada na impureza
- Análise dos fatores mais impactantes na evasão

---

## 📊 Principais Resultados

- Clientes com **contratos mensais**, **serviço de fibra óptica** e **pagamento via débito eletrônico** apresentam maior risco de evasão.
- O modelo **Random Forest** teve o melhor desempenho geral, com acurácia superior a 84%.
- Variáveis como `Monthly`, `tenure` e `Contract_Two year` foram altamente relevantes para a previsão de evasão.

---

## 💡 Estratégias de Retenção Propostas

- Oferecer **contratos de longo prazo** com benefícios.
- Criar planos promocionais para **clientes de risco**.
- Melhorar a experiência com **serviços de internet** e **cobrança eletrônica**.
- Programas de fidelização nos primeiros meses.

---

## 📌 Como Executar

1. Clone este repositório:
   ```bash
   git clone https://github.com/seuusuario/nome-do-repositorio.git
   cd nome-do-repositorio
2. Instale as dependências (recomenda-se o uso de ambiente virtual):
```bash
   pip install -r requirements.txt
```
3. Execute os notebooks na pasta notebooks.

Autora
Luana Tamaturgo
GitHub

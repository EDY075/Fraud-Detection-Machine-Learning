# Detecção de Fraudes em Transações Financeiras

Este repositório contém um projeto prático de ciência de dados focado na detecção de transações financeiras fraudulentas. O foco principal foi lidar com o desafio do **desbalanceamento de classes**, garantindo que o modelo seja capaz de identificar fraudes raras em um grande volume de dados legítimos.

## 🚀 Sobre o Projeto
O conjunto de dados utilizado reflete transações reais, onde a classe minoritária (fraude) representa apenas ~0,17% do total. O projeto aborda:
- **Análise Exploratória:** Investigação estatística da distribuição das transações.
- **Engenharia de Recursos (Feature Engineering):** Normalização e escalonamento de dados (`StandardScaler`, log transformation) para otimizar o desempenho do modelo.
- **Modelagem Preditiva:** Utilização de Regressão Logística com técnicas de estratificação para mitigar o viés do desbalanceamento.

## 🛠 Tecnologias Utilizadas
- **Linguagem:** Python
- **Bibliotecas:** `Pandas`, `NumPy`, `Scikit-learn`
- **Ferramentas:** Google Colab, Git

## 📈 Resultados Esperados
O objetivo central é maximizar o **Recall** para garantir que as fraudes não passem despercebidas, equilibrando-o com uma **Precision** aceitável para minimizar falsos positivos.

## 📂 Estrutura do Repositório
```text
├── data/               # (Pasta ignorada - dados brutos)
├── notebook/           # Notebook principal com a análise e treino
├── .gitignore          # Arquivos ignorados pelo Git
└── README.md           # Documentação do projeto

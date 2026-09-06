![Fraud Detection — Machine Learning Study](docs/assets/fraud-detection-banner.png)

# Fraud Detection with Machine Learning

Estudo de detecção de fraudes em transações financeiras com foco em desbalanceamento de classes, preparação de atributos e avaliação orientada a recall e precision.

![Python](https://img.shields.io/badge/Python-study-3776AB?style=flat-square&logo=python&logoColor=white) ![Pandas](https://img.shields.io/badge/Pandas-planned-150458?style=flat-square&logo=pandas) ![scikit-learn](https://img.shields.io/badge/scikit--learn-planned-F7931E?style=flat-square&logo=scikitlearn&logoColor=white) ![Status](https://img.shields.io/badge/Status-Documentation-6B7280?style=flat-square)

## Objetivo

O cenário documentado considera uma classe de fraude rara, próxima de 0,17% das transações. O objetivo é estudar como detectar o maior número possível de fraudes sem aceitar uma quantidade impraticável de falsos positivos.

## Abordagem planejada

1. inspecionar distribuição, valores ausentes e possíveis vazamentos de alvo;
2. separar treino e teste com estratificação;
3. ajustar escalas e transformações somente a partir do treino;
4. criar um baseline com regressão logística;
5. comparar precision, recall, F1, PR-AUC e matriz de confusão;
6. escolher o limiar de decisão conforme o custo operacional dos falsos negativos e falsos positivos.

## Estado atual

Este repositório contém a documentação inicial do estudo. O notebook executável, o dataset e métricas reproduzíveis ainda não foram publicados; por isso, o README não apresenta resultados como se já tivessem sido medidos.

Leia as [notas originais do projeto](docs/project-notes.md).

## Estrutura

```text
docs/
├── assets/fraud-detection-banner.png
└── project-notes.md
README.md
```

## Próximas entregas

- [ ] notebook com pipeline reproduzível;
- [ ] dataset público referenciado por origem e licença, sem redistribuição indevida;
- [ ] comparação com baseline ingênuo;
- [ ] curvas precision-recall e análise de limiar;
- [ ] requirements ou ambiente reproduzível;
- [ ] relatório de resultados e limitações.

## Segurança dos dados

Datasets financeiros, credenciais, `.env`, modelos derivados de dados privados e informações pessoais não devem ser versionados. O repositório público inclui apenas documentação e artefatos próprios de apresentação.

## Autor

**Edmilson Gomes** — [GitHub @EDY075](https://github.com/EDY075)

Este repositório ainda não possui uma licença de código aberto definida.

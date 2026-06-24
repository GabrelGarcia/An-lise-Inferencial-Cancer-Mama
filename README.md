# Analise-Inferencial-Cancer-Mama
O objetivo deste trabalho é aplicar os principais conceitos estudados na disciplina de Análise Inferencial em um problema real. 

# 📊 Inferência Estatística Aplicada ao Diagnóstico de Cancro da Mama

Este repositório contém o trabalho prático desenvolvido para a disciplina de **Análise Inferencial (Inferência Estatística e Ciência de Dados)**. O objetivo principal do estudo é aplicar conceitos de estimação e testes de hipóteses a um problema real da área da saúde, utilizando uma abordagem estatística comparativa simples e rigorosa.

---

## 🎯 Objetivo do Estudo

Investigar se é possível diferenciar estatisticamente tumores malignos de benignos analisando apenas uma característica física geométrica das células: o **raio médio do tumor** (`radius_mean`). 

A premissa baseia-se no facto de que as células malignas, devido ao seu crescimento descontrolado e agressivo, tendem a formar estruturas significativamente maiores do que as benignas.

### 🔬 Formulação das Hipóteses
* **Hipótese Alternativa ($H_1$):** O raio médio dos tumores malignos é estatisticamente superior ao dos tumores benignos ($\mu_M > \mu_B$).

---

## 📂 Base de Dados

O estudo utiliza o clássico conjunto de dados **Breast Cancer Wisconsin (Diagnostic)**.
* **Fonte oficial:** [Kaggle - Breast Cancer Wisconsin Data](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data)
* **Variável Qualitativa (Agrupamento):** `diagnosis` (M = Maligno, B = Benigno)
* **Variável Quantitativa (Teste):** `radius_mean` (Média do raio do tumor)

---

## 💻 Como Executar o Projeto

### Pré-requisitos
Certifica-te de que tens as seguintes bibliotecas instaladas no teu ambiente de execução:

#### Em Python:
```bash
pip install pandas numpy scipy matplotlib seaborn

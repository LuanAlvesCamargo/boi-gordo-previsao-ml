# Previsão do Preço da Arroba do Boi Gordo (2015–2025)

Este repositório contém o projeto desenvolvido como Trabalho Final da disciplina de **Aprendizagem de Máquina**, com foco na análise e previsão do preço da arroba do boi gordo utilizando diferentes técnicas de Machine Learning e Séries Temporais.

O estudo compara o desempenho de três modelos:

- **Regressão Linear**
- **ARIMA**
- **LSTM (Long Short-Term Memory)**

Os resultados demonstram que modelos baseados em séries temporais, especialmente o **ARIMA**, apresentam o melhor desempenho para prever o comportamento futuro da arroba.

---

## 📊 Objetivo do Projeto

O objetivo principal é **comparar o desempenho de diferentes modelos de previsão** aplicados à série histórica do preço da arroba do boi gordo entre **2015 e 2025**, avaliando sua capacidade de previsão por meio das métricas:

- **MAE — Mean Absolute Error**
- **RMSE — Root Mean Squared Error**
- **MAPE — Mean Absolute Percentage Error**

---

## 📁 Estrutura do Repositório

📦 Projeto

```
├── analise_estatistica_arroba.ipynb # Análise exploratória e estatística da série histórica
├── modelagem_previsao_precos_arroba.ipynb # Modelagem com ARIMA, LSTM e Regressão Linear
├── cepea-consulta-2025-2015.xls # Base de dados original (CEPEA)
├── referencias.txt # Referências utilizadas
├── README.md #
└── artigo.pdf #
```

---

## 🧠 Metodologia

### **1) Coleta de dados**

Os dados foram obtidos no portal do **CEPEA (Centro de Estudos Avançados em Economia Aplicada)**, contendo a cotação diária nominal da arroba entre 2015 e 2025.

### **2) Análise Exploratória**

Inclui:

- comportamento da série ao longo do tempo
- tendência
- sazonalidade
- identificação de padrões e ruídos

### **3) Modelos Aplicados**

#### 🔹 **Regressão Linear**

Modelo base, simples e transparente, bom para capturar tendências gerais.

#### 🔹 **ARIMA**

Modelo clássico e forte para séries temporais estacionárias.

- Melhor desempenho entre os três
- Captura bem padrões lineares e autocorrelações

#### 🔹 **LSTM**

Rede neural recorrente capaz de aprender dependências de longo prazo.

- Necessita mais dados e poder computacional
- Obteve bom desempenho, mas inferior ao ARIMA na série estudada

---

## 📈 Resultados

A comparação das métricas indicou:

- **ARIMA apresentou a menor taxa de erro geral (MAE, RMSE e MAPE)**
- LSTM teve desempenho sólido, mas menor estabilidade
- Regressão Linear funcionou como baseline, porém com erros mais altos

---

## 🧾 Conclusão

O estudo mostra que **modelos baseados em séries temporais tradicionais ainda podem superar redes neurais** em cenários com:

- séries mais curtas
- padrões lineares
- dependências simples
- nível moderado de ruído

O modelo **ARIMA** se provou a melhor opção para previsão do preço da arroba nesse contexto.

---

## 📚 Referências

As referências completas encontram-se no arquivo:  
📄 `referencias.txt`

---

## Autor

**Luan Alves Camargo Marques**  
Aluno de Ciência da Computação — FIB  
Contato: *luancamargo.fib@gmail.com*

---

## 📢 Observações

Este repositório serve como base para estudos de:

- Machine Learning aplicado ao agronegócio
- Previsão de preços
- Séries temporais
- Comparação de modelos preditivos

Sinta-se à vontade para contribuir ou utilizar os notebooks como referência.

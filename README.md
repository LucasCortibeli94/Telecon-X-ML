# 🤖 Telecom X — Parte 2: Modelagem de Churn

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](
https://colab.research.google.com/github/LucasCortibeli94/Telecon-X-ML/blob/main/TelecomX_P2_Modelagem.ipynb)

- Base tratada: [`telecomx_tratado.csv`](https://raw.githubusercontent.com/LucasCortibeli94/Telecon-X-ML/main/telecomx_tratado.csv)  
- Lista de risco: [`outputs/clientes_risco_churn.csv`](https://raw.githubusercontent.com/LucasCortibeli94/Telecon-X-ML/main/clientes_risco_churn.csv)  
- Lista detalhada: [`outputs/clientes_risco_churn_detalhado.csv`](https://raw.githubusercontent.com/LucasCortibeli94/Telecon-X-ML/main/outputs/clientes_risco_churn_detalhado.csv)

**Resumo:** LogReg (AUC ≈ 0.84, Recall ≈ 0.79) priorizada para retenção; threshold ajustado para aumentar Recall.  
Principais fatores → `Month-to-month`, `Fiber optic`, `Electronic check`, baixo `tenure`, ausência de `TechSupport/OnlineSecurity`.

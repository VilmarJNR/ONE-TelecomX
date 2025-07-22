# 📊 Análise de Churn — TelecomX BR

Este projeto tem como objetivo realizar uma análise exploratória de dados (EDA) sobre o cancelamento de clientes (churn) da empresa **TelecomX**. A análise é baseada em dados públicos disponibilizados como parte de um desafio de Data Science.

## 🔍 Objetivos

- Entender os fatores que contribuem para o cancelamento de clientes.
- Identificar padrões de comportamento e perfis com maior propensão ao churn.
- Explorar insights úteis para tomada de decisão e retenção de clientes.

## 📁 Fonte dos Dados

Os dados foram obtidos diretamente de um repositório do GitHub:

```
https://raw.githubusercontent.com/alura-cursos/challenge2-data-science/refs/heads/main/TelecomX_Data.json
```

## 🛠️ Tecnologias Utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- JSON / Requests

## 📌 Etapas do Projeto

### 1. Extração e Leitura dos Dados
- Os dados foram carregados diretamente do link externo em formato JSON.
- A estrutura foi normalizada para um DataFrame do Pandas.

### 2. Exploração Inicial
- Verificação das colunas, tipos de dados e presença de valores nulos.
- Análise descritiva das variáveis mais relevantes.

### 3. Análise de Cancelamentos
- Análise de proporções de cancelamento por gênero, tempo de contrato, idade, tipo de serviço, entre outros.
- Visualizações com gráficos de barras e boxplots para facilitar a interpretação.

## ✅ Conclusão

A análise dos dados da TelecomX revelou uma taxa de churn considerável, em torno de **26,6%**, o que representa aproximadamente **1 em cada 4 clientes**. Este índice elevado exige atenção especial na formulação de estratégias de retenção.

Dentre os principais fatores associados ao cancelamento, destacam-se:

- **Idosos** apresentam uma taxa de churn superior a **40%**, sugerindo maior vulnerabilidade desse grupo ao desligamento do serviço.
- **Contratos mensais** concentram a maior parte dos cancelamentos, enquanto contratos de longa duração podem reduzir o churn em até **93%**.
- O uso de **Internet via Fibra Óptica** está correlacionado com uma maior propensão ao churn, assim como serviços de **streaming**, o que pode indicar problemas de qualidade percebida.
- A forma de pagamento **"Electronic check"** tem forte associação com cancelamentos, sugerindo uma experiência de pagamento possivelmente insatisfatória.
- Clientes com **maior tempo de relacionamento** com a empresa e **gastos acumulados mais altos** demonstram maior fidelidade e menor tendência ao churn.


## 💡 Recomendações

- Implementar estratégias de retenção direcionadas a clientes com **menor tempo de contrato**, oferecendo suporte proativo e benefícios exclusivos.
- Realizar **pesquisas de satisfação** com clientes que cancelaram recentemente para entender suas motivações.
- Desenvolver **programas de fidelidade** e incentivos à renovação para clientes com contratos mensais.
- Avaliar a **qualidade da Internet Fibra Óptica** e investigar eventuais falhas ou insatisfações.
- Reavaliar o processo de pagamento via **"Electronic check"** e oferecer alternativas mais amigáveis.
- Destacar os **benefícios de serviços opcionais** como suporte técnico e proteção de dispositivos para agregar valor.


## ✍️ Autor

Projeto desenvolvido por Vilmar Vasconcelos como parte de um desafio de análise de dados no setor de telecomunicações.

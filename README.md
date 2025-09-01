# 📊 Checkpoint 01 – Análise de Dados de Consumidores de Energia

Este repositório contém o desenvolvimento do **Checkpoint 01** da disciplina de **Análise de Dados**, cujo objetivo foi realizar uma **análise exploratória de dados (EDA)** utilizando Python, Pandas, Matplotlib e Seaborn, a partir de um dataset real de consumo energético.

---

## 📁 Estrutura do Repositório

- `notebooks/` → Contém o Jupyter Notebook com todos os exercícios resolvidos.
- `README.md` → Este arquivo de documentação.
- `requirements.txt` → Lista de dependências necessárias para execução.
- `data/` (opcional, se usado) → Dataset utilizado na análise.

---

## 🎯 Objetivo

O trabalho teve como propósito aplicar técnicas de análise exploratória em um dataset de **consumo de energia elétrica residencial**, compreendendo:
- Limpeza e preparação dos dados.
- Análise estatística descritiva.
- Visualizações gráficas para extração de insights.
- Exercícios práticos de manipulação de dados com **Pandas**.

---

## 📊 Dataset

O dataset utilizado é o **Individual household electric power consumption** do **UCI Machine Learning Repository**.  
🔗 [Link do dataset](https://archive.ics.uci.edu/ml/datasets/individual+household+electric+power+consumption)

- Período: **2006 a 2010**
- Granularidade: **minuto a minuto**
- Atributos principais:
  - `Date` → Data
  - `Time` → Hora
  - `Global_active_power` → Potência ativa global
  - `Global_reactive_power` → Potência reativa global
  - `Voltage` → Voltagem
  - `Global_intensity` → Intensidade global
  - `Sub_metering_1`, `Sub_metering_2`, `Sub_metering_3` → Sub-medidores de consumo

---

## ✅ Entregáveis

O notebook foi dividido em **40 exercícios**, contemplando:

### 🔹 Parte 1 – Preparação dos Dados
- Importação e carregamento do dataset.
- Conversão de tipos e tratamento de datas.
- Verificação de valores ausentes e duplicados.
- Criação de colunas derivadas.

### 🔹 Parte 2 – Estatísticas Descritivas
- Medidas de tendência central e dispersão.
- Distribuições de consumo.
- Agrupamentos por períodos (dia, mês, ano).
- Comparações entre variáveis.

### 🔹 Parte 3 – Visualizações
- Histogramas e boxplots.
- Séries temporais.
- Gráficos de dispersão.
- Consumo por horário/dia da semana.

### 🔹 Parte 4 – Análises Avançadas
- Correlação entre variáveis.
- Agrupamento por sub-medidores.
- Identificação de padrões de consumo.
- Insights a partir de períodos de pico.

- 36-)

Número de variáveis (colunas): 9
Número de registros (linhas): 2.075.259

37-) 

A distribuição do Global_active_power é semelhante à base completa. Pequenas flutuações podem ocorrer, mas os picos e padrões principais permanecem.

38-)

A maioria dos registros está concentrada em valores baixos de consumo (próximo de 0–2 kW).

39-)

Existe uma correlação positiva leve: quando a tensão aumenta, a intensidade tende a aumentar um pouco, mas o padrão pode não ser muito forte.

40-)

Cada cluster geralmente representa um padrão distinto de consumo:

Cluster 1: consumo baixo em todos os submedidores.

Cluster 2: consumo alto em alguns submedidores específicos.

Cluster 3: picos isolados ou mistura de consumos médios.

---

## ⚙️ Como Executar o Projeto

### 1️⃣ Clone o repositório
```bash
git clone https://github.com/LuisNeves27/Checkpoint-01-An-lise-de-Dados-de-Consumidores-de-Energia.git
2️⃣ Acesse o diretório
bash
Copiar código
cd Checkpoint-01-An-lise-de-Dados-de-Consumidores-de-Energia
3️⃣ Crie um ambiente virtual (opcional, mas recomendado)
bash
Copiar código
python -m venv .venv
source .venv/bin/activate  # Linux/Mac
.venv\Scripts\activate     # Windows
4️⃣ Instale as dependências
bash
Copiar código
pip install -r requirements.txt
5️⃣ Execute o Jupyter Notebook
bash
Copiar código
jupyter notebook notebooks/CP01_UCI_Electric_Power_Consumption.ipynb
🛠️ Tecnologias Utilizadas
Python 3

Pandas

Matplotlib

Seaborn

Jupyter Notebook

👨‍🎓 Autores
Luis Felippe Morais das Neves
Gustavo Rangel de Lima Siqueira

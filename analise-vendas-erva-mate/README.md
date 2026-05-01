# 📊 Análise de Vendas — Erva Mate & Acessórios

Análise exploratória de dados de vendas B2B no setor de erva mate e acessórios, cobrindo o período de janeiro a março de 2024.

O dataset é simulado com base em contexto real de atuação comercial no setor — criado para praticar análise exploratória com pandas e matplotlib em um cenário de negócio familiar e coerente.

---

## 🎯 Perguntas respondidas

- Qual vendedor gerou mais faturamento no período?
- Qual produto tem maior receita total?
- Quais estados concentram maior volume de pedidos?
- Como o faturamento se distribui ao longo dos meses?
- Qual vendedor tem o maior ticket médio por venda?

---

## 🛠️ Ferramentas utilizadas

- **Python 3** — linguagem principal
- **Pandas** — manipulação e análise de dados
- **Matplotlib** — visualização gráfica
- **Google Colab** — ambiente de execução
- **Excel (.xlsx)** — fonte dos dados

---

## 📁 Arquivos

```
analise-vendas-erva-mate/
│
├── README.md
├── Atividade_pratica_dataframe.ipynb   
└── datasetteste.xlsx                   
```

---

## 🔍 Etapas da análise

**1. Carregamento e inspeção dos dados**
Leitura do arquivo Excel com pandas, seguida de EDA inicial: shape, tipos de dados, valores nulos e estatísticas descritivas gerais.

**2. Análise por vendedor**
Agrupamento por vendedor para calcular faturamento total e ticket médio, permitindo comparação de desempenho individual.

**3. Análise por produto**
Ranking de produtos por receita total, identificando os itens de maior contribuição para o faturamento.

**4. Análise por estado**
Distribuição do volume de pedidos por estado, revelando concentração geográfica da demanda.

**5. Análise temporal**
Agrupamento por mês para visualizar evolução do faturamento ao longo do período.

**6. Visualização**
Gráfico de barras horizontais com faturamento por vendedor, gerado com matplotlib.

---

## 📈 Principais insights

- **Bruno** liderou em faturamento total (R$ 1.141,50) e também em ticket médio (R$ 285,37)
- Há uma diferença expressiva entre o primeiro e o último colocado em ticket médio — de R$ 285,37 para R$ 193,50 — sugerindo investigar mix de produtos ou padrão de venda por vendedor
- O **Paraná** concentra o maior volume de pedidos em quantidade
- A **Bomba Inox** é o produto com maior faturamento total, puxado pelo alto valor unitário — não pelo volume

---

## 🚀 Como executar

1. Abra o notebook no Google Colab clicando no badge abaixo
2. Faça upload do arquivo `datasetteste.xlsx` no ambiente do Colab
3. Execute as células em ordem

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/SoullMk/analytics-lab/blob/main/Atividade_pratica_dataframe.ipynb)

---

## 👤 Autor

**Kaike Martins**
Estudante de Ciência de Dados — FMU São Paulo
[LinkedIn](https://linkedin.com/in/kaikemarttins) · [GitHub](https://github.com/SoullMk)

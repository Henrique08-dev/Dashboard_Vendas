# 📊 Dashboard de Vendas – Relatório Analítico

Este repositório contém a análise completa de um **Dashboard de Vendas** desenvolvido para acompanhar o desempenho comercial, métricas de faturamento, descontos, performance de vendedores e comportamento de produtos.

---

## 🎯 Objetivo

Responder a perguntas estratégicas de negócio com base em dados reais de vendas, utilizando visualizações interativas e métricas atualizadas.

---

## ❓ Perguntas Respondidas

### 1. Como estamos no trimestre atual?
- **Faturamento**: R$ 139 mil  
- **Descontos**: R$ 4,56 mil  
- **Produtos Vendidos**: 3 mil unidades  
- **Quantidade de Vendas**: 580 transações

> O trimestre atual apresenta **crescimento em faturamento, volume de vendas e produtos vendidos**, com redução nos descontos.

---

### 2. Comparação com trimestre anterior e mesmo trimestre do ano anterior

| Métrica | Trimestre Atual | vs. Trim. Anterior | vs. Trim. Ano Anterior |
|---------|-----------------|---------------------|-------------------------|
| Faturamento | R$ 139 mil | ✅ +34% | ✅ +5,4% |
| Descontos | R$ 4,56 mil | 🔻 -8,3% | 🔺 +86,3% |
| Produtos Vendidos | 3 mil | ✅ +122,8% | ✅ +83,9% |
| Quantidade de Vendas | 580 | ✅ +94% | ✅ +84% |

---

### 3. Estou no caminho certo para superar trimestres anteriores?
Sim, o trimestre atual apresenta **crescimento consistente**.  
⚠️ **Alerta**: Na semana 8, houve uma leve inflexão negativa. Se a linha do trimestre atual cruzar com a do ano anterior, pode indicar perda de performance.

---

### 4. Como está o desempenho dos meus vendedores?

| Vendedor | Participação | Faturamento |
|----------|--------------|-------------|
| Isabella Sousa | 21,7% | R$ 255,816 |
| Gustavo Gomes | 21,0% | R$ 246,765 |
| Leonardo Cardoso | 19,3% | R$ 227,321 |
| Carla Ferreira | 19,1% | R$ 225,186 |
| Julio Lima | 18,9% | R$ 222,467 |

---

### 5. Quais produtos trazem maior retorno?

**Top 3 Marcas por Faturamento**:
1. Marca 7 – R$ 157,087  
2. Marca 8 – R$ 147,297  
3. Marca 1 – R$ 144,937

**Categoria com Maior Faturamento**: Acessórios (R$ 439,746)

---

### 6. O que causou a queda no faturamento no trimestre anterior?
- **Carla Ferreira** teve queda brusca no faturamento.
- **Julio Lima** aplicou descontos elevados que **não resultaram em aumento de faturamento**.

---

## 🛠️ Recursos Técnicos do Dashboard

### Visualizações e Storytelling
- **Princípios de Gestalt**: Proximidade, similaridade e continuidade.
- **Pré-atentivos**: Cores (verde/vermelho), espessura de linhas, formatação condicional.
- **Contexto dinâmico**: Títulos, textos e rótulos atualizados conforme seleção.

### Funções DAX Utilizadas
- `FORMAT`, `CALCULATE`, `DIVIDE`, `ALL`, `DISTINCTCOUNT`, `SWITCH`, `SUMX`, `AVERAGE`, `AVERAGEX`, `CALCULATETABLE`, funções de inteligência de tempo e entre outras.

### Interatividade
- Parâmetros de campo
- Filtros dinâmicos por categoria, produto, vendedor e período
- Gráficos interativos com tooltips e detalhamento

---

## 📈 Insights Gerais

- **Ticket Médio**: R$ 235,51
- **Média de Produtos por Venda**: 5
- **Clientes**: 70,22% feminino | 56% na faixa de 21–40 anos
- **Relação Desconto × Faturamento**: Correlação positiva, com exceção de outliers (ex.: Julio Lima)

---

## 📁 Estrutura do Relatório

- **Página 1**: Visão Geral e KPIs
- **Página 2**: Análise Detalhada por Vendedor
- **Página 3**: Análise de Produtos e Clientes

---

## 👨‍💻 Como Utilizar

1. Acesse o dashboard via Power BI ou ferramenta similar.
2. Utilize os filtros para segmentar por período, vendedor, categoria ou marca.
3. Interaja com os gráficos para detalhamento e insights contextuais.

---

## ✅ Conclusão

O dashboard oferece uma **visão clara e acionável** do desempenho de vendas, permitindo identificar pontos de melhoria, otimizar estratégias de desconto e acompanhar a performance da equipe.

---

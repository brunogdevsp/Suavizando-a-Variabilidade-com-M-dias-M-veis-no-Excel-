# 📈 Análise de Séries Temporais: Cálculo e Visualização de Médias Móveis no Excel

Este repositório contém os materiais e a documentação de um exercício prático de **Análise de Séries Temporais** focado no cálculo e interpretação de **Médias Móveis (MM)**. O exercício foi realizado como parte do aprofundamento em Ciência de Dados, utilizando conceitos aprendidos na UNINTER e no curso "Ciência de Dados para Negócios com Excel" do Professor Fernando Amaral (Udemy).

O objetivo principal é demonstrar como as Médias Móveis agem como um filtro para **suavizar a variabilidade** de curto prazo, revelando a tendência subjacente dos dados.

## 📁 Estrutura do Projeto

* `Dados_Vendas_MM.xlsx`: Arquivo Excel contendo os dados brutos, os cálculos das Médias Móveis e os gráficos de visualização.

## 🎯 Objetivo do Exercício

O exercício visa comparar o efeito do período (intervalo) no cálculo da Média Móvel Aritmética (MMA) e sua representação gráfica.

**Foco:** Entender como o aumento do período de cálculo reduz a sensibilidade à variabilidade (ruído) e reforça a visualização da tendência.

## 🔢 Dados Utilizados

| Linha | Conteúdo | Observação |
| :--- | :--- | :--- |
| **Linha 1** | Dias (1 a 30) | Representa um mês completo de observação. |
| **Linha 2** | Vendas (em Milhares) | Os dados originais com alta variabilidade diária (ruído). |

## ⚙️ Metodologia de Cálculo

Foram calculadas duas Médias Móveis simples com diferentes janelas de tempo, utilizando a função `SOMA` (ou `MÉDIA`) do Excel.

### 1. Média Móvel de 7 dias (MM7)

* **Localização no Excel:** Linha 4
* **Fórmula (Dia 7):** `=SOMA(Vendas_Dia1:Vendas_Dia7) / 7` (ou `=MÉDIA(Célula_Dia1:Célula_Dia7)`)
* **Propósito:** Filtrar a variabilidade semanal e identificar a tendência de **curto prazo**.

### 2. Média Móvel de 14 dias (MM14)

* **Localização no Excel:** Linha 5
* **Fórmula (Dia 14):** `=SOMA(Vendas_Dia1:Vendas_Dia14) / 14` (ou `=MÉDIA(Célula_Dia1:Célula_Dia14)`)
* **Propósito:** Suavizar ainda mais os dados e identificar a tendência de **médio prazo**.

## 📊 Visualização e Conclusão

A etapa crucial do exercício foi a criação dos gráficos de linha:

1.  **Gráfico MM7:** Vendas vs. MM7.
2.  **Gráfico MM14:** Vendas vs. MM14.
3.  **Gráfico Comparativo:** Vendas vs. MM7 vs. MM14.

**Conclusão Observada:**

Ao comparar as linhas, é evidente que a **MM14 é mais suave** que a MM7, e ambas são significativamente mais suaves que a linha das Vendas originais. Isso demonstra que **quanto maior o período (intervalo) da Média Móvel, mais efetiva ela é para remover a variabilidade (ruído)**, fornecendo uma visão mais estável e confiável da direção da tendência.

## 📚 Créditos e Referências

* **Curso Base:** Ciência de Dados para Negócios com Excel, por Fernando Amaral (Udemy).
* **Instituição:** UNINTER - [Seu Curso/Faculdade]

---
_Desenvolvido por [Seu Nome] | Aluno de Ciência de Dados_

<div align="center">

# 🧾 Análise de Desempenho das Lojas do Senhor João  

📊 *Projeto de Análise Exploratória de Dados (EDA) com Python*  
💡 *Identificação da loja com pior desempenho para decisão estratégica de venda*  

---

📧 **E-mail:** [johnlenon@gmail.com](mailto:johnlenon8919@gmail.com)  
🔗 **LinkedIn:** [linkedin.com/in/johnlenon](https://www.linkedin.com/in/analistafinanceiro-powerbi/)  
🐙 **GitHub:** [github.com/johnlenon](https://github.com/johnlenon)  

---

![Python](https://img.shields.io/badge/Python-3.10%2B-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-yellow)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Data%20Viz-brightgreen)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

</div>

---

## 🧠 **Objetivo do Projeto**  

O Senhor João possui **quatro lojas** e deseja vender aquela com **pior desempenho geral**.  
A análise tem como propósito identificar **qual loja apresenta o menor retorno financeiro e operacional**, considerando:  

- 💰 **Faturamento total**  
- 🛒 **Produtos mais e menos vendidos**  
- ⭐ **Avaliações dos clientes**  
- 🚚 **Custos médios de frete**  
- 📈 **Correlação entre vendas e satisfação**

---

## 🧩 **Etapas da Análise**

### 🔹 1. Coleta e Consolidação dos Dados  
Os dados das quatro lojas foram importados de arquivos CSV hospedados no GitHub (projeto Alura Challenge).

### 🔹 2. Faturamento Total  
Cálculo do somatório da coluna `Preço` para identificar o desempenho financeiro de cada loja.  
Gráfico de barras criado com **Matplotlib** para comparação visual.

### 🔹 3. Produtos e Categorias  
Análise de agrupamento (`groupby`) para encontrar:
- Categorias mais vendidas;  
- Produto com **maior número de vendas**;  
- Produto com **menor número de vendas**.

### 🔹 4. Avaliação dos Clientes  
Cálculo da **média de avaliação de compra** de cada loja.  
Visualização em **gráfico de pizza**, destacando a participação percentual na média geral.

### 🔹 5. Custo Médio de Frete  
Determinação do **frete médio** por loja e comparação entre unidades.

### 🔹 6. Relação entre Vendas e Avaliação  
Criação de um **gráfico de dupla escala (twinx)** para mostrar a correlação entre quantidade vendida e satisfação dos clientes.

### 🔹 7. Distribuição Geográfica  
Mapa de dispersão (**scatter plot**) mostrando a localização geográfica das vendas por loja.

### 🔹 8. Relatório Final Automático  
Geração automática de um relatório em **Markdown**, resumindo:
- Melhor e pior loja  
- Melhor avaliação  
- Recomendação final de qual loja vender  

---

## 📊 **Principais Resultados**

| Indicador | Descrição |
|------------|------------|
| 💰 **Faturamento Total** | Identificou a loja mais lucrativa e a menos rentável |
| ⭐ **Média de Avaliações** | Avaliações giraram em torno de 4.0, destacando consistência |
| 🚚 **Frete Médio** | Custos variaram entre R$ 31 e R$ 35 |
| 📈 **Correlação** | Lojas com melhor faturamento também apresentaram boas avaliações |
| ⚠️ **Recomendação** | Vender a loja com menor faturamento e volume de vendas |

---

## 🎯 **Conclusão**

A análise possibilita uma decisão **estratégica e fundamentada**, garantindo que o Senhor João mantenha apenas as operações com:  
✅ Maior rentabilidade  
✅ Melhor percepção dos clientes  
✅ Potencial de crescimento  

> 📉 **Recomendação final:** vender a loja com **pior desempenho financeiro e operacional**.  
> 💹 **Manter** as lojas com **melhor equilíbrio entre faturamento e satisfação**.  

---

## 🧰 **Tecnologias Utilizadas**

| Ferramenta | Função |
|-------------|--------|
| 🐍 **Python 3** | Linguagem principal |
| 📦 **Pandas** | Manipulação e análise dos dados |
| 📈 **Matplotlib** | Criação dos gráficos e visualizações |
| 🧮 **Jupyter Notebook** | Ambiente interativo de desenvolvimento |
| 🧾 **IPython.display** | Geração automática do relatório final |

---

## 📂 **Estrutura do Projeto**

```bash
├── loja_1.csv
├── loja_2.csv
├── loja_3.csv
├── loja_4.csv
├── analise_lojas.ipynb
└── README.md

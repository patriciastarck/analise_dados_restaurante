# 📊 Análise Exploratória de Vendas e Consumo — Restaurante

Projeto de análise de dados desenvolvido em Python utilizando Google Colab e Pandas, com foco na limpeza, filtragem e extração de insights sobre o consumo de itens e bebidas por estabelecimento.

## 🎯 Objetivo
Investigar o desempenho de vendas e volume de saída de produtos, segmentando categorias específicas (como *Drinks* e *Soft Drinks*) para identificar padrões de consumo e oportunidades de negócio.

## 🛠️ Tecnologias Utilizadas
* **Linguagem:** Python 3
* **Bibliotecas:** Pandas, [Matplotlib / Seaborn — *adicione se usou gráficos*]
* **Ambiente:** Google Colaboratory

## 🔍 Etapas da Análise
1. **Carregamento e Inspeção Inicial:** Leitura da base de dados e verificação de tipos de dados, valores nulos e estrutura das colunas (`Estabelecimento`, `Categoria`, `Descrição`, `Quant.`, `T. Categoria`).
2. **Tratamento e Limpeza:** Padronização de strings, remoção de espaços extras e tratamento de inconsistências.
3. **Filtragem e Segmentação:** Isolamento de categorias estratégicas (`DRINKS` e `SOFT DRINKS`) para análise direcionada.
4. **Agregação e Métricas:** Cálculo de volumes totais por produto, categoria e unidade.

## 💡 Principais Insights
* **[Insight 1]:** [Ex: A categoria X representou Y% do volume total de bebidas analisadas.]
* **[Insight 2]:** [Ex: O produto Z liderou as vendas na unidade Anália Franco.]
* **[Insight 3]:** [Ex: Foram identificados itens cadastrados com quantidade zerada que demandam revisão de estoque/cardápio.]

## 🚀 Como Executar
1. Clone este repositório ou abra o arquivo `.ipynb` diretamente no **Google Colab** clicando no botão *Open in Colab* (ou fazendo o upload do notebook).
2. Certifique-se de carregar a base de dados na pasta raiz do ambiente antes de executar as células.

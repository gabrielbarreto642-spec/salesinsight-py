# SalesInsight PY — Análise e Visualização de Dados de Vendas com Python

## 📌 Sobre o Projeto
O **SalesInsight PY** é um projeto de análise e visualização de dados de vendas desenvolvido em Python. Ele realiza o ciclo completo de pipeline de dados: carrega, limpa, transforma, agrega e visualiza um dataset de vendas, gerando métricas por período, produto, categoria e região, além de uma segmentação de clientes por nível de gasto.

---

## 🔍 O que o Projeto Analisa
- **Faturamento e Volume:** Receita total e quantidade de produtos vendidos por mês e por trimestre.
- **Produtos e Categorias:** Identificação dos top produtos e categorias por receita.
- **Desempenho Regional:** Distribuição do faturamento por regiões.
- **Segmentação de Clientes:** Agrupamento por nível de gasto (Bronze, Prata e Ouro).
- **Relação Quantidade vs. Receita:** Comportamento e padrões de compra por transação.
- **Exportação Automatizada:** Geração de relatórios consolidados em CSV e JSON, além de gráficos em PNG.

---

## 🛠️ Conceitos e Tecnologias Aplicadas (Módulo 01 - Semanas 01 a 08)
- **Lógica e Estrutura de Dados:** Variáveis, listas, dicionários, estruturas condicionais e laços de repetição.
- **Funções:** Modularização, docstrings, lambdas e funções de ordem superior.
- **Expressões Regulares & Datetime:** Tratamento de textos corrompidos com `re` e padronização de datas.
- **Pandas:** Leitura, limpeza, criação de colunas derivadas, agregação com `groupby` e exportação.
- **NumPy:** Operações vetorizadas, cálculo estatístico (média, mediana, desvio padrão) e normalização.
- **Matplotlib & Seaborn:** Criação de gráficos (linha, barra, dispersão, subplots) e estilização visual.
- **Orientação a Objetos (POO):** Encapsulamento do pipeline na classe `AnalisadorDeVendas`.
- **Git & GitHub:** Versionamento de código com branches e commits semânticos.

---

## ⚙️ Como Executar o Projeto

### Pré-requisitos
- Python 3.x ou ambiente Google Colab.
- Gerenciador de pacotes `pip`.

### 1. Clonar o Repositório
```bash
git clone [https://github.com/gabrielbarreto642-spec/salesinsight-py.git](https://github.com/gabrielbarreto642-spec/salesinsight-py.git)
cd salesinsight-py

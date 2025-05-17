#  Desafio de Data Science - Alura Store (Stone)

Este projeto foi desenvolvido como parte do **Challenge de Data Science da Alura em parceria com a Stone**. O objetivo foi realizar uma análise exploratória de dados de 4 lojas, utilizando métricas comerciais relevantes para embasar uma **decisão de negócio**: **qual loja deve ser descontinuada/vendida**.

---

##  Objetivo do Projeto

Analisar o desempenho de 4 lojas com base nas seguintes métricas:

- ✅ Faturamento total
- ✅ Categorias mais populares
- ✅ Média de avaliação dos clientes
- ✅ Produtos mais e menos vendidos
- ✅ Custo médio de frete

A partir dessas informações, foi feita uma recomendação baseada em dados.

---

##  Estrutura dos Dados

Cada loja possui um arquivo `.csv` com as seguintes colunas:

- `Produto`
- `Categoria do Produto`
- `Preço`
- `Frete`
- `Data da Compra`
- `Vendedor`
- `Local da compra`
- `Avaliação da compra`
- `Tipo de pagamento`
- `Quantidade de parcelas`
- `lat`, `lon`
- `loja`

---

## 📈Análises Realizadas

### 1. Faturamento Total por Loja
- A **Loja 4** apresentou o **menor faturamento**
- A **Loja 1** foi a mais lucrativa

### 2. Categorias Mais Vendidas
- Destaque para:
  - `móveis`
  - `eletrônicos`
  - `brinquedos`

### 3. Média de Avaliação dos Clientes
- Loja 3: **4.05**
- Loja 2: **4.03**
- Loja 4: **3.99**
- Loja 1: **3.97**

### 4. Produtos Mais e Menos Vendidos
- Mais vendidos: `Cômoda`, `Carrinho controle remoto`, `Micro-ondas`
- Menos vendidos: `Panela de pressão`, `Smartwatch`, `Celular ABXY`

### 5. Frete Médio por Loja
- Loja 1: R$34,69
- Loja 2: R$33,62
- Loja 3: R$33,07
- Loja 4: **R$31,27** (menor)

---

##  Conclusão e Recomendação

Mesmo com um frete mais barato e boa avaliação média, a **Loja 4** teve o **pior desempenho em faturamento**, o que impacta diretamente nos resultados financeiros.

###  Recomendação:
> **A Loja 4 deve ser descontinuada ou vendida.**  
Ela apresentou o pior desempenho financeiro no comparativo com as demais lojas.

---

## Tecnologias Utilizadas

- Python
- Pandas
- Matplotlib
- Google Colab (para execução do notebook)

---

## Como Executar

1. Clone este repositório
2. Abra o arquivo `AluraStoreBr.ipynb` no Google Colab
3. Execute os blocos de código sequencialmente
4. Analise os gráficos e as saídas no notebook

---

## Contato

Desenvolvido por Luiz Oliveira 
LinkedIn: @luizoliveira  
E-mail: sesmicom@gmail.com


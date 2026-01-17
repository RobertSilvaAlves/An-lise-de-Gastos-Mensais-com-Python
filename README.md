# 📊 Análise de Gastos Mensais com Python

## 📌 Descrição do Projeto
Este projeto tem como objetivo realizar uma **análise simples de gastos mensais**, utilizando Python, com foco na **organização dos dados, extração de insights e visualização gráfica**.

Os dados representam gastos divididos por **categorias** em dois meses diferentes (Janeiro e Fevereiro), permitindo comparar totais mensais e entender como os gastos se distribuem em cada categoria.

---

## 🎯 Objetivos da Análise
- Calcular o **total de gastos por mês**
- Identificar a **categoria com maior gasto** em cada mês
- Comparar os gastos entre os meses
- Visualizar os dados de forma clara utilizando **gráficos de barras**

---

## 🧩 Estrutura dos Dados
Os dados foram organizados em um **dicionário**, onde:
- Cada chave principal representa um **mês**
- Cada mês contém um conjunto de **categorias de gastos** associadas aos seus valores

Estrutura conceitual:

```
Mês
 └── Categoria → Valor
```

Essa abordagem facilita o acesso, a análise e a visualização dos dados.

---

## 🛠️ Tecnologias Utilizadas
- **Python**
- **Matplotlib**
- **Google Colab**

---

## 📈 Análises Realizadas

### 🔹 Total de Gastos por Mês
Foi calculado o total de gastos para cada mês, permitindo identificar qual mês teve maior despesa total.

**Insight:**  
Janeiro apresentou um gasto total maior em comparação com Fevereiro.

---

### 🔹 Gastos por Categoria
Foram criados gráficos de barras para cada mês, mostrando a distribuição dos gastos por categoria.

Os valores foram:
- Ordenados em **ordem crescente**
- Anotados diretamente nas barras para facilitar a leitura

**Insight:**  
A categoria **Moradia** foi a que apresentou maior peso nos gastos em ambos os meses.

---

## 📊 Visualizações
O projeto inclui:
- Gráfico de barras com **total de gastos por mês**
- Gráficos de barras com **gastos por categoria** para Janeiro e Fevereiro

Essas visualizações ajudam a compreender rapidamente o comportamento dos gastos.

---

## 🚀 Aprendizados
Durante o desenvolvimento deste projeto, foram trabalhados conceitos importantes como:
- Estruturação de dados com dicionários
- Separação entre **dados brutos** e **resultados de análise**
- Uso de funções como `sum()` e `max()`
- Boas práticas de visualização de dados
- Escrita de código mais legível e organizado

---

## 🔜 Próximos Passos
- Expandir a análise para mais meses
- Comparar a variação de gastos por categoria entre os meses
- Refatorar o código para reduzir repetições
- Aplicar novas visualizações

---

## 👤 Autor
**Robert Alves**  
Em transição para a área de **Dados**, desenvolvendo projetos práticos em Python para fortalecer o portfólio.

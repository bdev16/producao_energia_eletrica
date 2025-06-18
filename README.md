# Produção de Energia Elétrica

## Sobre o projeto

Esse repositorio conisiste em testar os conhecimentos obtidos no tópico ETL sobre o NumPy, fornecido pelo bootcamp de Data Science da Oracle + Alura. 
## Objetivo

Capturar algumas informações da base de dados de produção enérgetica(Gerada por IA), utilizando a linguagem Python e a lib do NumPy.

## Tópicos

- **Ler os dados com np.loadtxt, entender a estrutura da base e responder as seguintes perguntas**
  - Quantos anos de dados temos?
  - Quantos tipos de energia são monitorados?
  - Quantos meses de produção por tipo existem?    

- **Calcular estatísticas simples de produção e responder as seguintes perguntas:**
  - Qual a média geral de produção de energia?
  - Houve algum valor muito fora do comum (outlier)?
    
- **Reorganizar os dados para análise por mês e responder as seguintes perguntas:**
  - Quais meses apresentaram maior média de produção?
    
- **Identificar valores altos de produção e responder as seguintes perguntas:**
  - Quantas vezes a produção foi superior a 900 GWh?
 
- **Descobrir qual fonte teve maior produção total por ano. e responder as seguintes perguntas:**
  - Em cada ano, qual foi a fonte com maior produção?

## Tecnologias Utilizadas

- **Python**

- **Numpy**

- **Matplotlib**

- **Google Colab**

- **GitHub**

## Conclusão do Desafio

A base de dados contem 5 anos de dados sobre os valores de energias gerados pelas seguintes fontes [ Solar | Eolica | Hidroeletrica | Termoeletrica | Nuclear ], que tem seus valores divididos em 12 meses de energia gerada por cada fonte.

Por meio da análise conseguimos identifcar que a média geral de produção de energia foi de 615.93 e um dos valores muito fora da curva encontrado foi de 997.0 sendo o maior valor energetico gerado e 201.0 sendo o menor valor energitico gerado. Também conseguimos identifcar que os meses que apresentaram a maior média de produção energética foram AGOSTO, OUTUBRO e NOVEMBRO com as seguintes médias de energia gerada 709.439, 633, 674.28.

Além disso a descobrimos que as maiores fontes com maior produção energitica em cada ano foram 7021 gw gerados pela Hidroeletrica em 2019; 5893 gw gerados pela Hidroeletrica em 2020; 8065 gw gerados pela Solar em 2021; 8270 gw gerados pela Hidroeletrica; 6505 gw gerados pela Hidroeletrica.

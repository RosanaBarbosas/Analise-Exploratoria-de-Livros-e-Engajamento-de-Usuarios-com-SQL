# Análise Exploratória de Livros e Engajamento de Usuários com SQL

## Descrição do projeto
Este projeto consiste em uma análise exploratória de dados de uma plataforma digital de leitura, utilizando um banco de dados relacional contendo informações sobre livros, autores, editoras, avaliações e resenhas de usuários. O estudo foi desenvolvido com foco no uso de SQL para responder a perguntas analíticas e gerar insights relevantes sobre o catálogo de livros e o engajamento dos usuários.

---

## Objetivo do projeto
O objetivo principal do projeto é explorar e analisar os dados disponíveis para:
- Compreender a estrutura e o relacionamento entre as tabelas do banco de dados;
- Avaliar características do catálogo de livros;
- Identificar padrões de avaliação e engajamento dos usuários;
- Gerar insights que possam apoiar a criação de uma proposta de valor para um novo produto no mercado de leitura digital.

---

## Metodologia
A metodologia adotada seguiu as seguintes etapas:
1. Conexão com o banco de dados relacional utilizando Python.
2. Exploração inicial das tabelas para compreensão da estrutura dos dados e seus relacionamentos.
3. Elaboração de consultas SQL para responder às perguntas propostas no estudo.
4. Utilização de agregações, filtros, junções (JOINs) e CTEs (Common Table Expressions) para garantir resultados corretos e consistentes.
5. Interpretação dos resultados e elaboração de conclusões analíticas.
6. Criação de visualizações gráficas para reforçar os principais achados.

---

## Resultados
Os principais resultados obtidos foram:
- A maior parte dos livros do banco de dados foi publicada após o ano 2000, indicando um catálogo predominantemente contemporâneo.
- Todos os livros analisados apresentam algum tipo de interação dos usuários, seja por avaliações ou resenhas.
- A editora **Penguin Books** é a que publicou o maior número de livros com mais de 50 páginas.
- Considerando apenas livros com pelo menos 50 avaliações, o autor com a maior nota média é **J.K. Rowling/Mary GrandPré**.
- Usuários que avaliaram mais de 50 livros escreveram, em média, aproximadamente **24 resenhas com texto**, indicando alto nível de engajamento.

---

## Ferramentas utilizadas
- **SQL**: para exploração, agregação e análise dos dados.
- **Python**: para conexão com o banco de dados e execução das consultas.
- **Pandas**: utilizado exclusivamente para exibição dos resultados das consultas SQL.
- **Matplotlib**: para criação de gráficos e visualização dos principais insights.
- **Jupyter Notebook**: como ambiente de desenvolvimento e apresentação da análise.

---

## O que eu aprendi (habilidades e competências adquiridas)
- Escrita de consultas SQL complexas utilizando JOINs, GROUP BY, HAVING e CTEs.
- Boas práticas de análise exploratória de dados em bancos relacionais.
- Interpretação de resultados analíticos com foco em negócio.
- Organização de um notebook analítico com explicações claras e conclusões coerentes.
- Comunicação de resultados por meio de visualizações gráficas.
- Pensamento crítico na escolha de métricas e filtros para evitar vieses na análise.

---

## Existem melhorias a serem feitas?
Sim. Algumas possíveis melhorias incluem:
- Criação de mais visualizações para explorar padrões de distribuição de avaliações.
- Análise temporal das publicações e do comportamento dos usuários ao longo do tempo.
- Inclusão de métricas adicionais de engajamento, como frequência de avaliações por período.
- Otimização das consultas para cenários com volumes de dados maiores.

---

## Como executar o projeto
1. Abrir o Jupyter Notebook fornecido.
2. Garantir que a string de conexão com o banco de dados esteja corretamente configurada.
3. Executar as células na ordem apresentada, começando pela conexão com o banco.
4. Rodar as consultas SQL para visualizar os resultados.
5. Executar as células de visualização para gerar os gráficos.
6. Ler as conclusões apresentadas ao longo do notebook para compreender os insights obtidos.

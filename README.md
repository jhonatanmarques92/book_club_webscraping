[![Linkedin](https://img.shields.io/badge/-linkedin-blue?logo=linkedin&link=https://www.linkedin.com/in/jhonatanmarques/)](https://www.linkedin.com/in/jhonatanmarques/)

# Projeto de Data Engineering da livraria Book Store
<img src="https://github.com/jhonatanmarques92/jhonatanmarques92.github.io/blob/main/images/book_store.jpg" width="300" height="300">

### Observação: A livraria Book Store é fictícia e todo o contexto não é real

## Questão de Negócio
A livraria Book Store é um site que oferece um serviço onde os usuário podem vender ou trocar seus livros, onde o modelo de rentabilidade é feita através das avaliações e disponibilidade dos livros no estoque, oporém, a livraria não possui o controle, já que os usuários sobem os livros através de um botão "upload".
Como cientista de dados, o dever é organizar os dados e armazená-los em um banco de dados, para facilitar a consulta.

## Premissa do Negócio
Deverá ser entregue um banco de dados contendo o nome do livro, categoria, avaliação, preço, se está em estoque, data e horário do scraping.

## Processo da Solução
- Webscraping do site https://books.toscrape.com/
- Limpeza dos dados
- Armazenar em um banco SQLite

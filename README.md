API feita para organizar seus livros consulta e detalhamento de livros de forma centralizada, interface padronizada seguindo os princípios REST


Método   Endpoint       Descrição                                                                                                          
GET  `/livros`      Retorna uma lista completa de todos os livros cadastrados no sistema, ideal para listagens gerais.                 
POST `/livros`      Cria um novo registro de livro no banco de dados a partir das informações enviadas no corpo da requisição.         
GET `/livros/{id}` Recupera os detalhes técnicos e bibliográficos de um livro específico utilizando o seu identificador único (UUID). 

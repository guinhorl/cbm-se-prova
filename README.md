Cadastro e busca de CEP

O sistema é simples, no index você tem um campo de busca por cep, ao fazer essa busca com um cep valido ele o sistema mostrara para o usuário as informações, referente aquele CEP. Caso o sistema não encontre em sua base de dados, ele fara uma requisição na API do ViaCEP, mostrara para o usuário as informações daquela busca, e dando a opção de salvar essas informações na base de dados do sistema. O sistema também conta com a opção de editar ou remover os dados já existente no sistema. No projeto foi utilizado o PHP 8, com o framework Laravel 9 e banco de dados mysql.
Como executar

As configurações do banco consta no .env.example.

Para rodar as migrations descomente a linha DB_HOST=127.0.0.1, e comente a linha DB_HOST=db_cbmse_prova do .env.example
depois desfaça esse procedimento. Não sei porquê, mas só é possivel rodar as migrations em localhost.


###Autor do projeto Wagner

A suíte de testes para a lista de exercícios foi criada utilizando o [Postman](https://www.postman.com) e a API [JSONplaceholder](https://jsonplaceholder.typicode.com/guide/), foram realizados 6 testes dos quais apenas um apresentou erro, tendo resposta 200 (OK) ao invés do 404 (Not Found) esperado.
Já existe um relatório pronto na pasta newman com o nome de ListaDeExercicios-2024-06-09-15-01-20-199-0, mas caso seja desejado um novo relatório, recomenda-se o uso do [newman](https://www.npmjs.com/package/newman) com adição do pacote [HTMLextra](https://www.npmjs.com/package/newman-reporter-htmlextra) sendo o comando final para geração algo similar a :
'''console
newman run "Endereço do arquivo no seu sistema" -r htmlextra
'''

# API de Cadastro

Essa é API de Cadastro, uma aplicação Java desenvolvida com o poderoso framework Spring Boot. Esta API permite o registro do nome e endereço de usuários e se integra perfeitamente com o serviço ViaCep para obter informações de endereços com base no CEP.

## Funcionalidades

- **Cadastro de Usuário**: Permite o registro de usuários com seus nomes e endereços.
- **Consulta de Endereço por CEP**: Oferece a capacidade de consultar informações detalhadas de endereços usando o CEP como referência.

## Principais Tecnologias Utilizadas

- **Java**: Linguagem de programação robusta e versátil.
- **Spring Boot**: Framework de desenvolvimento que facilita a criação de aplicativos Java.
- **ViaCep**: Serviço externo para a obtenção de informações de endereço com base no CEP.
- **Swagger**: Documentação interativa da API..
- **H2 Database**: Banco de dados em memória para armazenamento de dados da aplicação.


## Endpoints

- `GET /clientes​/{id}`: Faz a pesquisa do usuário através do id e fornece os dados da busca em JSON.
- `PUT /clientes​/{id}`: Faz a atualização dos dados cadastrados usuário através do id dele.
- `DELETE /clientes​/{id}`: Através do id do cliente é possível excluir o mesmo.
- `GET /clientes`: Faz a coleta de todos os usuários e nos fornece em uma estrutura JSON.
- `POST /clientes`: Cria um registro, somente com o nome e o cep em JSON.

## Configuração

O projeto utiliza o H2 Database como banco de dados em memória. As configurações do banco de dados podem ser encontradas no arquivo `application.properties` ou `application.yml` da aplicação. 




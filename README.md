# Ponto  API

API do sistema de ponto com Java e Spring Boot.

## Executando a aplicação

Certifique-se de ter o Git e o Java JDK 11 ou superior instalados em seu sistema.

1.  Clone o repositório:

    **`git clone https://github.com/HilquiasCamelo/ponto-api.git`**

2.  Navegue até o diretório do projeto:

    bashCopy code

    **`cd ponto-api`**

3.  Execute a aplicação usando o Maven:

    `./mvnw spring-boot:run`

    A API será executada em `http://localhost:8080`.


## Endpoints

A API possui os seguintes endpoints principais:

-   `GET /api/funcionarios`: Retorna a lista de funcionários cadastrados.
-   `GET /api/funcionarios/{id}`: Retorna os detalhes de um funcionário específico.
-   `POST /api/funcionarios`: Cria um novo funcionário.
-   `PUT /api/funcionarios/{id}`: Atualiza as informações de um funcionário.
-   `DELETE /api/funcionarios/{id}`: Remove um funcionário.

## Documentação da API

A documentação detalhada da API, incluindo os parâmetros de cada endpoint, pode ser acessada em `http://localhost:8080/swagger-ui.html`. Acesse essa URL em um navegador para explorar a documentação interativa da API.

## Contribuindo

Contribuições são bem-vindas! Se você deseja colaborar com o projeto, siga estas etapas:

1.  Crie um fork do repositório.
2.  Crie uma nova branch com a sua feature ou correção de bug: `git checkout -b minha-feature`.
3.  Faça as alterações desejadas e adicione os devidos testes.
4.  Faça o commit das suas alterações: `git commit -m 'Adiciona nova feature'`.
5.  Envie suas alterações para o repositório remoto: `git push origin minha-feature`.
6.  Envie um Pull Request para o repositório principal.

## Licença

Este projeto está licenciado sob a licença MIT. Consulte o arquivo `LICENSE` para obter mais informações.

----------

Esse é apenas um exemplo de como melhorar um README de um projeto. Sinta-se à vontade para adaptá-lo de acordo com as necessidades e características específicas do seu projeto.
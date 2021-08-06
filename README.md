### GraphQL

"GraphQL é uma linguagem de consulta para APIs e um runtime para atender a essas consultas com seus dados existentes. GraphQL fornece uma descrição completa e compreensível dos dados em sua API, dá aos clientes o poder de pedir exatamente o que eles precisam e nada mais, torna mais fácil evoluir APIs ao longo do tempo e permite poderosas ferramentas para desenvolvedor." (https://graphql.org)

##### Vantanges

- Único endpoint
- Único request
- Server apresenta os recursos disponíveis
- Client solicita somente a informação necessária
- Há possibilidade de realizar alterações / inserções nos dados através de "mutations"
- Trabalha utilizando HTTP
- Retorna json como response


##### Schema

- GraphhQL Schema Language
- Data Types
- Query
- Mutations
- Subscriptions


##### Funcionamento

- Queries realizam consultas e trazem os dados de acordo com o solicitado, executam paralelamente.
- Mutation realiza o processo de create, update e delete, executam em série.

##### 99designs/gqlgen

`sudo apt install build-essential`: requirement

`go run github.com/99designs/gqlgen init`: generate initial stubs 
`go run github.com/99designs/gqlgen generate`: generate stubs 
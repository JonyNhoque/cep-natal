// Proposta //

Crie 2 repositorios:

- Um pro back-end que irá consultar a api do viacep (`https://viacep.com.br/ws/01001000/json/`) para trazer os dados do endereço digitado
- Outro repo para o front que irá consumir seu backend passando o cep digitado pelo usuario

Requisitos:

- Typescript nos 2 repos
- O backend deverá ser em `node` e usar `apollo/graphql` (`https://www.apollographql.com/`)
  - gasta um tempo aqui, faz funcionar um server com essa configuração e faz umas queries de teste utilizando o playgroud
- O front deverá usar react hooks, sem redux (useContext no lugar se precisar) e consumir o seu backend via query do graphql
- Deverá utilizar react-router (`https://reactrouter.com/docs/en/v6`) para lidar com as 2 screens que serão:
  - uma onde tem o input que o cara digita o cep e subimita pra fazer a query
  - outra onde será exibida as informação que a query retornou
- O site deve ser SEO friendly, ou seja ter o html legivel pro robo do google (`https://reactrouter.com/docs/en/v6/examples/ssr`)
- Quanto a estilo, procure utilziar styled-components

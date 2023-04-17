## Prova técnica - Oper


### Introdução
Esse documento te guiará no processo de desenvolvimento do desafio técnico proposto para a vaga de desenvolvedor full-stack estagiário no processo seletivo da Oper. O desafio proposto é a construção de um miniblog que conecta-se com API's para obtenção e persistência de informações.

### Requisitos

- A aplicação deverá ser desenvolvida em Next.js.
- A aplicação obterá as informações utilizando a [News API](https://news-api.lublot.dev/api-docs).
- O miniblog deverá ter pelo menos duas páginas:
  - Home: 
    - É a página inicial da aplicação.
    - Esta página deve listar informações sobre os artigos obtidos da API.
      - Você pode definir quais informações são relevantes exibir na tela inicial e qual será o layout da exibição.
      - Você pode definir quais artigos serão exibidos utilizando os filtros da API. Use a criatividade!
    - Quando o usuário clicar em algum artigo, deverá ser redirecionado para a página *Article* onde será possível ler o artigo completo.
  - Article:
    - A página irá exibir o conteúdo completo do artigo que foi escolhido pelo usuário. 
    - Nesta página haverá uma seção de comentários:
      - Para comentar, o visitante precisa informar o e-mail e um texto com o comentário.
      - Outros visitantes podem responder aos comentários.
      - Outros visitantes podem curtir os comentários e/ou respostas.
      - As informações sobre os comentários devem ser persistidas em um banco de dados.
- Cada página deverá ter sua própria rota no Next.js

### Instruções adicionais
- Você é livre para decidir se usará Javascript ou Typescript.
- Você é livre para determinar o layout das páginas.
- Você é livre para escolher qual banco de dados irá utilizar.
- Você é livre para decidir quais bibliotecas utilizar para te auxiliar no desenvolvimento do projeto.
- Você é livre para adicionar funcionalidades, se achar necessário.
- A [News API](https://news-api.lublot.dev/api-docs) possui duas rotas:
  - /api/posts: retorna uma lista de posts
  - /api/posts/{id}: retorna um post para um determinado id

### Considerações importantes

#### Sobre a News API
- Esta é uma API desenvolvida exclusivamente para esta prova utilizando dados fictícios.
- As instruções para utilização da API podem ser encontradas no seguinte endereço:
  - [https://news-api.lublot.dev/api-docs](https://news-api.lublot.dev/api-docs)

### Critérios de avaliação
- Cumprimento dos requisitos solicitados
- Clareza do código
- Entrega dentro do prazo
- Pensamento crítico sobre as decisões técnicas para resolver problema proposto
- Coerência na estruturação do banco de dados.
- Conhecimento sobre as tecnologias solicitadas.

### Entrega da solução final
- Você deverá enviar o link do repositório git contendo a sua solução para emerson.souza@operdata.com.br e em cópia para: selecao@operdata.com.br.
- Se utilizar variáveis de ambiente no projeto, crie um arquivo nomeado ```.env.example``` e coloque os nomes das variáveis que está utilizando, por exemplo:

```
DB_HOST=<vazio>
DB_USERNAME=<vazio>
DB_PORT=<vazio>
```

### Considerações finais
Se tiver alguma dúvida ou consideração sobre a prova técnica pode entrar em contato via e-mail: emerson.souza@operdata.com.br, tentarei responder na medida do possível.

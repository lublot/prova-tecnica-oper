## Prova técnica - Oper


### Introdução
Esse documento te guiará no processo de desenvolvimento do desafio técnico proposto para a vaga de desenvolvedor full-stack estagiário no processo seletivo da Oper.
Em breve resumo, o desafio proposto é a construção de um miniblog que conecta-se com API's para obtenção e persistência de informações.

### Requisitos

- A aplicação deverá ser desenvolvida em Next.js.
- A aplicação obterá as informações utilizando a [Article Search API](https://developer.nytimes.com/docs/articlesearch-product/1/overview) do New York Times.
- O miniblog deverá ter pelo menos duas páginas:
  - Home: 
    - É a página inicial da aplicação.
    - Esta página deve listar informações sobre os artigos obtidos da API.
      - Você pode definir quais informações são relevantes exibir na tela inicial e qual será o layout da exibição.
    - Quando o usuário clicar em algum artigo, deverá ser redirecionado para a página *Article* onde será possível ler o artigo completo.
  - Article:
    - A página irá exibir o conteúdo completo do artigo que foi escolhida para o usuário.
    - As informações principais que devem aparecer nessa página são: imagem de capa, o título, o conteúdo do artigo e o autor.
    - Os metadados da postagem como data e afins ficam ao seu critério
    - Nesta página haverá uma seção de comentários:
      - Para comentar, o visitante precisa informar o e-mail e um texto com o comentário.
      - Outros visitantes podem responder aos comentários.
      - Outros visitantes podem curtir os comentários.
    
    
- Cada página deverá ter sua própria rota no Next.js

### Instruções adicionais
- Você pode decidir se usará Javascript ou Typescript.
- Você é livre para determinar o layout das páginas.
- Você é livre para escolher qual banco de dados irá utilizar.
- Você é livre para decidir quais bibliotecas utilizar para te auxiliar no desenvolvimento do projeto.

### Considerações importantes

#### Sobre a New York Times: Article Search API
- A New York Times API tem um limite de 500 requisições por dia. Use-as com sabedoria.
- As instruções para utilização da API podem ser encontradas nos seguintes endereços:
  - [New York Times: Article Search API - Por onde começar?](https://developer.nytimes.com/get-started)
  - [New York Times: Article Search API - Documentação](https://developer.nytimes.com/docs/articlesearch-product/1/overview)

### Critérios de avaliação
- Cumprimento dos requisitos solicitados
- Clareza do código
- Pensamento crítico sobre as decisões técnicas para resolver problema proposto
- Coerência na estruturação do banco de dados.
- Conhecimento sobre as tecnologias solicitadas.


### Entrega da solução final

### Considerações finais
Se tiver alguma dúvida ou consideração sobre a prova técnica pode entrar em contato via e-mail emerson.souza@operdata.com.br, tentarei responder na medida do possível.

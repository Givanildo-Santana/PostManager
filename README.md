# PostManage

PostManage é um aplicativo Java desenvolvido para gerenciar e exibir posts e seus comentários. Este projeto faz parte de um conjunto de exercícios de programação em Java, focado no uso de classes e objetos.

## Funcionalidades

- **Gerenciamento de Posts:** Criar e gerenciar posts com título, conteúdo, data e número de curtidas.
- **Gerenciamento de Comentários:** Adicionar comentários aos posts e exibi-los de forma associada.

## Estrutura de Classes

### Classes Principais

- **Post:** Representa um post com os seguintes atributos:
  - `moment`: Data do post
  - `title`: Título do post
  - `content`: Conteúdo do post
  - `likes`: Número de curtidas do post
  - `comments`: Lista de comentários associados ao post

- **Comment:** Representa um comentário com o seguinte atributo:
  - `text`: Texto do comentário

## Exemplo de Uso

Para usar este projeto, você deve criar instâncias das classes `Post` e `Comment`, adicionar comentários aos posts e exibir os detalhes dos posts e seus comentários.

### Exemplo de Saída:

#### Post 1
- **Data:** 21/06/2018 13:05:44
- **Título:** Traveling to New Zealand
- **Conteúdo:** I'm going to visit this wonderful country!
- **Curtidas:** 12
- **Comentários:**
  - "Have a nice trip"
  - "Wow that's awesome!"

#### Post 2
- **Data:** 28/07/2018 23:14:19
- **Título:** Good night guys
- **Conteúdo:** See you tomorrow
- **Curtidas:** 5
- **Comentários:**
  - "Good night"
  - "May the Force be with you"

## Tecnologias Utilizadas

- Java

## Contribuindo

Sinta-se à vontade para contribuir com este projeto fazendo um fork do repositório, fazendo suas alterações e enviando um pull request. Agradecemos qualquer melhoria ou adição à funcionalidade do PostManage.

## Licença

Este projeto está licenciado sob a Licença MIT. Veja o arquivo LICENSE para mais detalhes.

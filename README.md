![Yapoli](https://avatars2.githubusercontent.com/u/23282442?s=200&v=4)

# Teste de Front-end Yapoli
Este teste é apresentado aos candidatos as vagas de desenvolvimento Front-end para avaliar os quesitos técnicos.

### O Desafio

Seu objetivo é criar um simples app que deve conter duas páginas: uma de login e outra de lista de imagens, que contem os seguintes dados:

* Descrição da imagem
* Imagem
* Data de upload

A página de login deve aceitar um par usuário/senha fixos e redirecionar para a lista. Formate a página de login como julgar melhor.

A lista de imagens deve conter cards para organizar as imagens, contendo a imagem, a data e o nome no card.

### Pré-requisitos: 
 - Utilizar react-js (https://pt-br.reactjs.org/) e o Material UI (https://material-ui.com/) para os elementos de tela;

Para ter o estado inicial da lista de arquivos utilizar este recurso abaixo:

> GET https://tf378xyae1.execute-api.sa-east-1.amazonaws.com/prod/images

Response:

```json
[
    {
        "data": "2020-01-27 15:14:40",
        "url": "https://yapoli-dev-test.s3-sa-east-1.amazonaws.com/Arrow_V1_1002.jpg",
        "nome": "Arrow V1"
    },
    {
        "data": "2020-01-27 15:14:47",
        "url": "https://yapoli-dev-test.s3-sa-east-1.amazonaws.com/Brick_and_Concrete_V1_1027.jpg",
        "nome": "Brick and Concrete"
    },
    ...
]
```

### Plus:
 - A página ser responsiva;
 - Possibilitar excluir itens da lista;
 - Persistir a lista no navegador localStorage/IndexedDB;
 - Utilizar Redux
 - Testes End to End;

### O que esperamos:
 - Testes, no mínimo testes unitários;
 - Utilizar ECMAScript 6+;
 - Criar uma breve descrição da solução utilizada.


** Use seus próprios critérios para listar e organizar os itens **

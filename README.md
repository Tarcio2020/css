No css temos uma hierarquia.

    1-CSS inline.
    2-IDs e Classes.
    3-Tags

Para contornar essa hierarquia

  button {
            background-color: blue !important;
        }

Códigos com muitos Seletores tendem a serem menos performático;

EX:

     header nav ul li a 

Esse terá mais performace:

    .nav-link 

______________SMACSS_______________

O SMACSS (Scalable and Modular Architecture for CSS) é
uma arquitetura para utilizada para construção de código
CSS, nesta arquitetura temos a divisão do CSS nas
categorias:
- Base;
- Layout;
- Módulos;
- Estados;
- Temas.


Nos arquivos base estilizamos as regras mais básicas da
página, é essencialmente um reset, onde podemos remover
as margens, espaçamentos e definir outras propriedades
que seguirão um padrão na página.
Exemplo de conteúdo de um arquivo base:


    h1, h2, h3, h4, h5, h6 {
    margin: 0;
    }
    body {
    font-family: Roboto, sans-serif;
    }


_________BEM - Block Element Modifer___________

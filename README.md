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

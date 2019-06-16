# Projeto - To Do List
Repositório que contém documentos, diagramas e wireframes de telas do projeto.


## Índice
- [Documentos](#documentos)
  - [Modelagem de Funcionalidades](#modelagem-de-funcionalidades)
  - [Modelagem de Classes](#modelagem-de-classes)
- [Diagramas](#diagramas)
  - [Caso de Uso](#caso-de-uso)

<a id="documentos"></a>

## Documentos
Novamente, não utilizo muitos documentos, apenas alguns poucos que me ajudam a
visualizar o sistema com mais facilidade. Um documento que sempre está presente
é o de modelagem de funcionalidades, onde descrevo as funcionalidades do
aplicativo e suas depêndencias. Outro documento essêncial é o documento de modelagem 
e classes, onde mapeio e modelo as classes que fazem parte do domínio do aplicativo.

Para escrever os documentos, utilizo apenas a línguagem Markdown.

<a id="modelagem-de-funcionalidades"></a>

- **Modelagem de Funcionalidades**:  
  Documento onde as funcionalidades, e suas dependências, são descritas.

  Nesse documento, as funcionalidades estão ordenadas de cima para baixo, de
  acordo com suas depêndencias, quanto mais depêndencias uma funcionalidade
  tiver, mais para o final do documento a mesma estará.

  [Visualizar Documento](../master/Documentos/Modelagem%20de%20Funcionalidades.md)

  ----

<a id="modelagem-de-classes"></a>

- **Modelagem de Classes**:  
  Documento onde as classes que fazem parte do domínio da aplicação, são 
  modeladas.

  Podemos considerar domínio da aplicação, tudo que faz parte da regra de
  negócio da aplicação, por exemplo: No nosso sistema teremos a classe Tarefa,
  que representa uma tarefa e a classe App, que representa nosso aplicativo,
  porém apenas a classe Tarefa faz parte do domínio do aplicativo, a classe App,
  faz parte do aplicativo, porém não faz parte da regra de negócios.

  [Visualizar Documento](../master/Documentos/Modelagem%20de%20Classes.md)

<a id="diagramas"></a>

## Diagramas
Normalmente não costumo criar muitos diagramas, na realidade, geralmente, o
único que eu preciso é o de Caso de Uso, que com algumas adaptações realizadas
por mim, conseguimos ver o aplicativo como um todo.

A ferramenta que utilizo para criar os diagramas é o app
[Draw.io](https://www.draw.io/)

<a id="caso-de-uso"></a>

- **Caso de Uso**:  
  Semelhante ao diagrama de Caso de Uso UML, possuindo algumas adaptações 
  realizadas por mim. Nesse modelo, tento fortalecer ao máximo as dependencias
  de funcionalidades, através dos extends e includes, de maneira que conseguimos 
  imaginar um fluxo funcional da aplicação.

  [Arquivo Fonte](../master/Diagramas/Arquivos%20Fonte/Caso%20De%20Uso.drawio)
  
  [Arquivo PDF](../master/Diagramas/PDF/Caso%20De%20Uso.pdf)
  
  [Visualizar/Editar Online](https://www.draw.io/?lightbox=1&highlight=0000ff&edit=_blank&layers=1&nav=1&title=Caso%20De%20Uso.drawio#R7VxRl6I2FP41Pu4eIID66DhO%2BzDt2da2O7svPRmJmG4kHggj7q9vkCBg0M04Mgmt8zLkJoHkfvcm370BB2C6zn6K4Wb1Cw0QGThWkA3A%2FcBxbN%2B1%2BL9csiskI3dcCMIYB6JRJZjj70gIRb8wxQFKGg0ZpYThTVO4oFGEFqwhg3FMt81mS0qaT93AEEmC%2BQISWfoZB2wlpLY%2Frip%2BRjhciUePnGFRsYZlYzGTZAUDuq2JwGwApjGlrLhaZ1NEcuWVein6PZyoPQwsRhFT6fDb528Z%2BvVh%2B3eGHyZP2YL8%2FhV%2B8Iq7vECSigmLwbJdqYGYplGA8ptYA3BHY7aiIY0geaR0w4U2F%2F6DGNsJ7GDKKBet2JqIWj6%2BePck%2Bu8LX%2Bo191m96n4nSsU4UCDBU81XiBKaxgt0ZpKl3cA4ROxMOzA%2BwMLtGdE14gPiHWNEIMMvzYFAYVjhoV2le34h1P8KKGwJij%2BTdDAFg4kdYyrBws1pk1%2BmazJZMBpzlb2gmGFuuo%2FwGZFPNMEM04g3eaaM0TVvQPKKO7j4Fu5BnVKS9%2BN3A8v9X%2B0eE4LDvC%2FLQa6jSVNGcISmB3%2BrwMr7ouw8XLJ2RQcHfBTGKFYKZzwqJdvK84DwplXN53yrI0iGLd7hw3WuEcL2026WLJQxFAXJIHdFURU2GpalfYfnmF8JyRG6ud3PRbFyuVklvXuzWwYwWe3729f1NkfR23ydzlZuS9eH9gyQEY2MRg6MFaFzdELnSMjNloilkDuTNYVcNyymKh5GCOcQOR7bFWZovoF73Ww5jWlq%2Bwprm23LixtoWdxst2V1G3a1urnyjtMfH0AZZk%2B16y%2B164pR5IWSULTTkIp4tNMQ7b6mdZksR1kzkckCJcne2SYbwpkCH4RMTvQ6l%2B3qd67RjTq83il8RZ8AWvcfV8Oy%2BR8F8pRrvxOSnfH7%2FyGSWvcp%2FwwnfKQhjgwjhAAMDSSEjrzbd%2BMP17X2y4jdFX3EUXaSkU4ncXVsXF3yfYt7zAWMv%2BilgfMr2wmwtNpJW1K4b3ZS2cZrIsPKNHTGhup2ojUR43UW4%2FQ4h6aMnTfUSn1lxvQXTlJI8HeRSGMopDHmDzadObkGMCdPjiQeMGGx2bqUMycm6LJY1JpknleluKFLw1Qpm6UP2o6v3lmV8inHLMAMmqxJz3fNM8k%2BM6LOdrqRKkvRymaBvNMpYGcGdAcye0nQcwiNNQc9ymail8z2OTjWjp2nNyMvByLiIPh4pzNoXzOBHxSwnVTcPH1eGKm7oWcAJ5CpVT3lTFNmGLGSKart6zdBWwe16tkZjOqrArbW0zTwXjtoJ7RKMUPYJFWaKJXya1pajxu8Pr9epBs6Wy8ZvihmukFXKM%2FTCZ18hFtndH%2FweS9Ny%2FgMKxpi0GG4JxOTI27MTFTmeGSiMm15L6hyuj0xShMSkcW20DRKut4QxPrk3kbEHS3xW5kaN1KNHnANVKNzC99%2BnEVT%2Ff5M6%2Bdnbp85X9%2B%2FBlA2Eb0hvqvjhdlOD1Muifq1HaUoB48nsvFiJ%2BETsEsiUXLEoqRsReLenyjmczjc%2BMNRD7pcJnygx1Z3GNEbyPnt8723LCJaT2s8mcP2B7vW11Av2Gh%2B9PW7fhs5kYAqXd366Nvl9xO7pvtfuop0v2z4t2XjDSbhaeWn5Y1PvbFYBG2JDIXWGM2E5Isn5wSrlxPNVJtrdRna8mL1syvF2lL9eA2Y%2FQs%3D)
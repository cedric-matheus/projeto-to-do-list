# Modelagem de Funcionalidades

## Índice

- [Funcionalidades Sem Depêndencias](#funcionalidades-sem-dependencia)
  - [Acessar Aplicativo](#acessar-aplicativo)
- [Funcionalidades Com Depêndencias](#funcionalidades-com-dependencia)
  - [Efetuar Cadastro](#efetuar-cadastro)
  - [Efetuar Login](#efetuar-login)
  - [Efetuar Logout](#efetuar-logout)
  - [Visualizar Tarefas](#visualizar-tarefas)
  - [Visualizar Categorias](#visualizar-categorias)
  - [Filtrar Tarefas](#filtrar-tarefas)
  - [Filtrar Categorias](#filtrar-categorias)
  - [Cadastrar Tarefa](#cadastrar-tarefa)
  - [Cadastrar Categoria](#cadastrar-categoria)
  - [Cadastrar Subtarefa](#cadastrar-subtarefa)
  - [Cadastrar Subcategoria](#cadastrar-subcategoria)
  - [Editar Tarefa](#editar-tarefa)
  - [Editar Categoria](#editar-categoria)
  - [Excluir Tarefa](#excluir-tarefa)
  - [Excluir Categoria](#excluir-categoria)
  - [Completar Tarefa](#completar-tarefa)

<a id="funcionalidades-sem-dependencia"></a>

## Funcionalidades Sem Depêndencias

<a id="acessar-aplicativo"></a>

- Acessar Aplicativo:  
  O usuário deve ser capaz de acessar o aplicativo através de uma URL.

<a id="funcionalidades-com-dependencia"></a>

## Funcionalidades Com Depêndencias

<a id="efetuar-cadastro"></a>

- Efetuar Cadastro:  
  O usuário deve ser capaz de efetuar um cadastro, depois de
  [Acessar Aplicativo](#acessar-aplicativo).

<a id="efetuar-login"></a>

- Efetuar Login:  
  O usuário deve ser capaz de efetuar login no aplicativo, depois de
  [Efetuar Cadastro](#efetuar-cadastro)

<a id="efetuar-logout"></a>

- Efetuar Logout:
  O usuário deve ser capaz de efetuar logout no aplicativo, depois de
  [Efetuar Login](#efetuar-login)

<a id="visualizar-tarefas"></a>

- Visualizar Tarefas:  
  O usuário deve ser capaz de visualizar suas tarefas, depois de
  [Efetuar Login](#efetuar-login). Nesse caso, tarefas e subtarefas são iguais.
  Subtarefas serão colocadas em forma de Accordion na listagem.
  Tarefas com subtarefas, devem exibir a informação: subtarefas concluídas / 
  subtarefas totais.

<a id="visualizar-categorias"></a>

- Visualizar Categorias:  
  O usuário deve ser capaz de visualizar suas categorias, depois de 
  [Efetuar Login](#efetuar-login). Nesse caso, categorias e subcategorias são
  iguais. Subcategorias serão colocadas em forma de Accordion na listagem.

<a id="filtrar-tarefas"></a>

- Filtrar Tarefas:  
  Enquanto [Visualizar Tarefas](#visualizar-tarefas), o usuário deve ser capaz
  de filtrar as tarefas. A filtragem pode ser feita por um campo de busca, em
  conjunto com opções para filtrar por nome da tarefa ou nome da categoria.
  Outra opção de filtro, é para tarefas completas e tarefas incompletas.
  Nesse caso, tarefas e subtarefas são iguais.

<a id="filtrar-categorias"></a>

- Filtrar Categorias:  
  Enquanto [Visualizar Categorias](#visualizar-categorias), o usuário deve ser
  capaz de filtrar as categorias. A filtragem pode ser feita por um campo de
  busca, categorias podem ser filtradas apenas por nome da categoria.
  Nesse caso, categorias e subcategorias são iguais.

<a id="cadastrar-tarefa"></a>

- Cadastrar Tarefa:  
  O usuário deve ser capaz de cadastrar uma tarefa, depois de
  [Visualizar Tarefas](#visualizar-tarefa)

<a id="cadastrar-categoria"></a>

- Cadastrar Categoria:  
  O usuário deve ser capaz de cadastrar uma categoria, depois de 
  [Visualizar Categorias](#visualizar-categorias) ou enquanto
  [Cadastrar Tarefa](#cadastrar-tarefa)

<a id="cadastrar-subtarefa"></a>

- Cadastrar Subtarefa:  
  Enquanto [Cadastrar Tarefa](#cadastrar-tarefa) o usuário, poderá definir a
  tarefa como subtarefa de outra tarefa. Apenas tarefas raiz (que não tem pai)
  podem receber uma tarefa como subtarefa.

<a id="cadastrar-subcategoria"></a>

- Cadastrar Subcategoria:
  Enquanto [Cadastrar Categoria](#cadastrar-categoira) o usuário, poderá definir
  a categoria como subcategoria de outra categoria. Apenas categorias raiz 
  (que não tem pai) podem receber uma categoria como subcategoria.

<a id="editar-tarefa"></a>

- Editar Tarefa:  
  Enquanto [Visualizar Tarefas](#visualizar-tarefas), o usuário deve ser capaz
  de editar uma tarefa, depois de [Cadastrar Tarefa](#cadastrar-tarefa). Nesse
  caso, tarefas e subtarefas são iguais.

<a id="editar-categoria"></a>

- Editar Categoria:  
  Enquanto [Visualizar Categorias](#visualizar-categorias), o usuário deve ser
  capaz de editar uma categoria, depois de [Cadastrar Categoria](#cadastrar-categoria).
  Nesse caso, categorias e subcategorias são iguais.

<a id="excluir-tarefa"></a>

- Excluir Tarefa:  
  Enquanto [Visualizar Tarefas](#visualizar-tarefas), o usuário deve ser capaz
  de excluir uma tarefa, depois de [Cadastrar Tarefa](#cadastrar-tarefa). Nesse
  caso, tarefas e subtarefas são iguais. Ao excluir uma tarefa que contém 
  subtarefas, as subtarefas também devem ser excluídas. Toda exclusão deve
  ser confirmada, para evitar acidentes. 

<a id="excluir-categoria"></a>

- Excluir Categoria:  
  Enquanto [Visualizar Categorias](#visualizar-categorias), o usuário deve ser
  capaz de excluir uma categoria, depois de
  [Cadastrar Categoria](#cadastrar-categoria). Nesse caso, categorias e
  subcategorias são iguais. Ao excluir uma categoria que contém subcategorias,
  as subcategorias também devem ser excluídas. Toda exclusão deve ser confirmada,
  para evitar acidentes.

<a id="completar-tarefa"></a>

- Completar Tarefa:  
  Enquanto [Visualizar Tarefas](#visualizar-tarefas), o usuário deve ser capaz
  de completar uma tarefa, depois de [Cadastrar Tarefa](#cadastrar-tarefa). Nesse
  caso, tarefas e subtarefas são iguais. Uma tarefa que contenha subtarefas, só
  pode ser completada depois que todas as subtarefas forem completadas.
# Modelagem de Classes
Documento onde as classes que fazem parte do domínio da aplicação, são modeladas.

Nessa etapa, prefiro já deixar as classes com nome, atributos e métodos em
inglês, pois é assim que ficarão no código.

## Indice
- [User (Usuário)](#user)  
  - [Atributos](#user-attributes)  
  - [Métodos](#user-methods)  
- [Category (Categoria)](#category)  
  - [Atributos](#category-attributes)  
  - [Métodos](#category-methods)  
- [Task (Tarefa)](#task)  
  - [Atributos](#task-attributes)  
  - [Métodos](#task-methods)  

----

## Classes

---

<a id="user"></a>

- **User (Usuário)**:  

  <a id="user-attributes"></a>

  - **Atributos**:  
    - Id : Integer  
    - Name (Nome) : String
    - Last Name (Sobrenome) : String
    - Email : String
    - Password Hash (Hash da senha) : String

  <a id="user-methods"></a>

  - **Métodos**:  
    - getToken() : String  
      Método que retorna uma string contendo um Token de autenticação JWT.
    - checkPassword(password) : Boolean  
      Método que recebe uma senha (password) e retorna uma booleana contendo a
      validação da senha do usuário.

----

<a id="category"></a>

- **Category (Categoria)**:  

  <a id="category-attributes"></a>

  - **Atributos**:  
    - Id : Integer  
    - Name (Nome) : String
    - Parent (Pai) : Category

  <a id="category-methods"></a>

  - **Métodos**:  
    - getChildrens() : [Category, ...]  
      Método que retorna um array contendo as categorias filhas.

----

<a id="task"></a>

- **Task (Tarefa)**:  

  <a id="task-attributes"></a>

  - **Atributos**:  
    - Id : Integer  
    - Name (Nome) : String
    - Description (Descrição) : String
    - Parent (Pai) : Task
    - Is Completed (Está Completada) : Boolean

  <a id="task-methods"></a>

  - **Métodos**:  
    - getChildrens() : [Task, ...]  
      Método que retorna um array contendo as tarefas filhas.
    - complete() : Boolean  
      Método que completa uma tarefa. Caso existam tarefas filhas incompletas,
      a tarefa não é completada e o método retorna false. Caso não existam
      tarefas filhas, ou tarefas filhas incompletas, a tarefa é completada e o
      método retorna true.
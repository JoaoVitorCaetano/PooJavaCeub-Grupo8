```mermaid
classDiagram
  class Pessoa {
    - nome: string
    - idade: int
    + cumprimentar(): void
  }

  class Aluno {
    - matrícula: string
    + assistirAula(): void
  }

  class Professor {
    - salário: float
    + darAula(): void
  }



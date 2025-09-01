```mermaid
classDiagram
  class Usuario {
    +cpf: string
    +nome: string
    +email: string
    +senha: string
    +alterarSenha(novaSenha: string): void
    +obterEmail(): string
    +obterInformacoesDoPedido(): int   
  }

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

class Cliente {
+endereco: string
+telefone: string
 +numeroPedido: int
+realizarPedido(): void }
 

class Funcionario {
+cargo: string
+salario: double
 +registrarVenda(): void
 +registrarCliente(): void }

 

Usuario <|-- Cliente
Usuario <|-- Funcionario

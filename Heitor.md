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
+salario: float
 +registrarVenda(): void
 +registrarCliente(): void }

 

Usuario <|-- Cliente
Usuario <|-- Funcionario

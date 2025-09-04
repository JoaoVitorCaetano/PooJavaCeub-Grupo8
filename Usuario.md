```mermaid
classDiagram
  class Usuario {
    +cpf: string
    +nome: string
    +email: string
    +senha: string
    +alterarSenha(novaSenha: string): void
    +obterEmail(): string
     
  }

class Cliente {
+endereco: string
+telefone: string
+status: string  
+numeroPedido: int
+obterInformacoesDoPedido(): string  
+realizarPedido(): void 
 +cancelarPedido(numeroPedido: int): boolean

}

class Funcionario {
    +cargo: string
    +dataContratacao: Date
    +setor: string
    +salario: double
    +registrarVenda(): void
    +registrarCliente(): void
    +consultarCliente(cpf: string): Cliente
    +encaminharClienteParaSetor(cliente: Cliente, setor: string): void
    +responderDuvidaCliente(cliente: Cliente, duvida: string): string
}



 

Usuario <|-- Cliente
Usuario <|-- Funcionario

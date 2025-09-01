````mermaid
classDiagram
  class Fornecedor {
    +nome: String
    +cnpjOuCpf: String
    +endereco: String
    +telefone: String
    +exibirInfo(): String
    +validarDocumento(doc: String): bool
    +entreContato(): void
}

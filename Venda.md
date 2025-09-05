```mermaid
  classDiagram

  class Venda{
    +idVenda: int
    +dataHora: DateTime
    +formaPagamento: String
    +Desconto: double

    +calcularTotal(): double
    +aplicarDesconto(valor: double): void
    + finalizarVenda(): void
    + cancelarVenda(): void
    + emitirNotaFiscal(): NotaFiscal
  }

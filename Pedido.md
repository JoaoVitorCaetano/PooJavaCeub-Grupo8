```mermaid
classDiagram
  class Pedido {
    +idPedido: int
    +status: String
    +prazoEntrega: Date
    + adicionarItem(item: ItemPedido): void
    + removerItem(item: ItemPedido): void
    + atualizarStatus(novoStatus: String): void
    + confirmarPedido(): void
    + cancelarPedido(): void
}

```mermaid
  classDiagram

  class Instrumento{
    +nome : string
    +marca : string
    +modelo : string
    +material : string
    +preco : float
    +peso : float
    +afinação : int
    +Origem: string

    +tocar() : string
    +afinar() : string
    +informacoes() : string
    +calcular_preco_desconto : float
}

```

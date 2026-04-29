#Revisão - semana 10

## Cenário 1
Atores

Receita Federal
Sistema

Caso de uso
Consultar estoque
Verificar status da transportadora
Enviar dados para a receita federal


## Cenário 2

Atores

Cliente
Cozinheiro
Sistema

Caso de uso

Cliente -> Fazer o pedido
Cliente -> Realizar o pagamento
Sistema -> Exibir o pedido
Sistema ->Atualizar sistema de fidelidade

## Cenário 3

Sensor -> app -> servidor -> alerta

usar mermaid

## Cenário 4

Fluxograma

solicita acesso -> há uma reserva? -> se sim: destranca a porta -> se não: Não abre a porta

```mermaid
flowchart TD
    A[Aproxima o celular] -->
    C{Há reserva ativa?}
    C -->|Sim| D[Destrancar porta]
    C -->|Não| E[Não abre a porta]
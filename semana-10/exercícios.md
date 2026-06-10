# Exercícios de Diagramas UML

## Cenário 1 – Logística de E-commerce Global

### Diagrama de Casos de Uso

```mermaid
flowchart LR

Cliente((Cliente))
Estoque((Sistema de Estoque))
Transportadora((Transportadora))
Receita((Receita Federal))

Sistema[E-commerce]

Cliente --> Sistema
Sistema --> Estoque
Sistema --> Transportadora
Sistema --> Receita
```

---

## Cenário 2 – Totem de Autoatendimento em Fast-Food

### Diagrama de Casos de Uso

```mermaid
flowchart LR

Cliente((Cliente))
Cozinheiro((Cozinheiro))
Fidelidade((Sistema de Fidelidade))

Pedido((Realizar Pedido))
Pagamento((Efetuar Pagamento))
Preparar((Visualizar Pedido))
Pontos((Atualizar Fidelidade))

Cliente --> Pedido
Cliente --> Pagamento

Cozinheiro --> Preparar

Pagamento --> Pontos
Fidelidade --> Pontos
```

---

## Cenário 3 – Sistema de Telemedicina

### Diagrama de Sequência

```mermaid
sequenceDiagram

participant Sensor
participant App
participant Servidor
participant Medico

Sensor->>App: Envia dados cardíacos

alt Alteração detectada
    App->>Servidor: Solicita histórico
    Servidor-->>App: Retorna histórico
    Servidor->>Medico: Envia alerta
end
```


---

## Cenário 4 – Sistema de Controle de Acesso Inteligente

### Diagrama de Atividades

```mermaid
flowchart TD

A[Usuário aproxima celular] --> B[App valida reserva]
B --> C{Reserva ativa?}

C -- Sim --> D[Enviar comando para fechadura]
D --> E[Destrancar porta]

C -- Não --> F[Acesso negado]
```

---

## Cenário 5 – Marketplace de Serviços Domésticos

### Diagrama de Casos de Uso

```mermaid
flowchart LR

Cliente((Cliente))
Profissional((Profissional))

Buscar((Buscar Profissional))
Filtrar((Filtrar por Localização e Disponibilidade))
Contratar((Contratar Serviço))
Pagar((Liberar Pagamento))
Avaliar((Avaliar Profissional))

Cliente --> Buscar
Cliente --> Contratar
Cliente --> Pagar

Profissional --> Contratar

Buscar -. include .-> Filtrar
Pagar -. extend .-> Avaliar
```


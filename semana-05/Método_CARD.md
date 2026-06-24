# Aplicativo de Cardápio Virtual - Restaurante

## 1. Descrição do Sistema

O sistema será um **cardápio virtual para restaurante**, acessado por QR Code nas mesas ou via link. O objetivo é permitir que clientes visualizem os pratos, façam pedidos diretamente pelo celular e acompanhem o status do pedido em tempo real.

O sistema também reduz erros de comunicação entre cliente e garçom, agiliza o atendimento e facilita a atualização de preços e itens do cardápio.

---

## 2. Método CARD (Capturar, Aprovar e Refinar)

### 2.1 Capturar (Histórias de Usuário)

A partir das necessidades do cliente (restaurante), foram levantadas as seguintes histórias:

- Visualizar cardápio com categorias e imagens dos pratos
- Ver detalhes dos pratos (ingredientes, preço, tempo de preparo)
- Fazer pedido diretamente pelo celular
- Personalizar pedido (ex: tirar ingrediente, ponto da carne)
- Acompanhar status do pedido (recebido, em preparo, pronto)
- O garçom receber pedidos em painel administrativo
- O restaurante atualizar cardápio sem precisar reimprimir menus
- Cliente avaliar pedido após consumo

---

### 2.2 Histórias de Usuário

#### US01 — Visualizar cardápio
Como cliente, eu quero visualizar o cardápio digital com categorias e imagens para escolher meu pedido com facilidade.

---

#### US02 — Ver detalhes do prato
Como cliente, eu quero ver detalhes dos pratos (ingredientes, preço e tempo estimado de preparo) para tomar uma decisão informada.

---

#### US03 — Realizar pedido
Como cliente, eu quero fazer pedidos diretamente pelo celular para agilizar o atendimento sem depender do garçom.

---

#### US04 — Personalizar pedido
Como cliente, eu quero personalizar meu pedido (ex: retirar ingredientes ou ajustar preparo) para adequar a refeição às minhas preferências.

---

#### US05 — Acompanhar status do pedido
Como cliente, eu quero acompanhar o status do meu pedido para saber quando ele está sendo preparado ou pronto.

---

#### US06 — Painel de pedidos
Como funcionário do restaurante, eu quero receber os pedidos em um painel para organizar a preparação dos pratos.

---

#### US07 — Gerenciar cardápio
Como administrador do restaurante, eu quero adicionar, editar e remover itens do cardápio para manter as informações sempre atualizadas.

---

#### US08 — Avaliação do pedido
Como cliente, eu quero avaliar meu pedido após o consumo para fornecer feedback ao restaurante.

---

### 2.3 Aprovar

As histórias foram validadas considerando:
- Valor direto para o cliente (experiência do usuário)
- Valor operacional para o restaurante (eficiência)
- Viabilidade técnica para implementação em sistema web/mobile

Todas as histórias são relevantes e alinhadas ao objetivo do sistema.

---

### 2.4 Refinar

As histórias foram mantidas em nível macro (sem detalhamento técnico), porém podem ser refinadas futuramente em:
- Critérios de aceitação
- Regras de negócio
- Fluxos de interação
- Integração com sistema de pagamento (se necessário)
- Integração com cozinha (KDS - Kitchen Display System)

---

## 3. Conclusão

O uso de histórias de usuário permite manter o foco no valor entregue ao cliente e facilita a evolução do sistema. O método CARD ajuda a organizar o backlog inicial de forma simples, validando rapidamente as necessidades reais do restaurante antes do desenvolvimento.
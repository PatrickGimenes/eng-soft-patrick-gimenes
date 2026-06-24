# Sistema de Gestão de Hotel - Hotel Bela Vista

## 1. Requisitos Funcionais (RF)

### Reservas e Hóspedes

**RF1** - O sistema deve permitir cadastrar reservas informando dados do hóspede (nome e documento/CPF).

**RF2** - O sistema deve permitir consultar reservas rapidamente através do CPF ou documento do hóspede.

**RF3** - O sistema deve evitar reservas duplicadas para o mesmo quarto no mesmo período.

**RF4** - O sistema deve permitir o check-in do hóspede, associando-o a um quarto disponível.

**RF5** - O sistema deve permitir o check-out do hóspede, finalizando sua estadia.

---

### Controle de Quartos

**RF6** - O sistema deve exibir um mapa visual com todos os quartos do hotel.

**RF7** - O sistema deve indicar o status dos quartos por cores:
- Livre  
- Ocupado  
- Em limpeza  

**RF8** - O sistema deve permitir que a camareira atualize o status de limpeza dos quartos.

**RF9** - O sistema deve associar cada quarto a um tipo (simples, família, luxo) e seu respectivo valor.

---

### Consumo e Comandas

**RF10** - O sistema deve permitir registrar consumos realizados pelo hóspede (frigobar, lanches e bebidas).

**RF11** - O sistema deve permitir que funcionários registrem consumos manualmente por número de quarto.

**RF12** - O sistema deve permitir o registro e acompanhamento da comanda do hóspede.

**RF13** - O sistema deve somar automaticamente os consumos à conta final no momento do check-out.

---

### Pagamentos e Relatórios

**RF14** - O sistema deve calcular automaticamente o valor da estadia com base no tipo de quarto e período.

**RF15** - O sistema deve gerar o valor total da estadia no check-out.

**RF16** - O sistema deve gerar relatórios financeiros diários, semanais e mensais.

**RF17** - O sistema deve apresentar relatórios de ocupação e consumo do hotel.

---

## 2. Requisitos Não Funcionais (RNF)

### Desempenho e Usabilidade

**RNF1** - O sistema deve responder rapidamente às consultas de reservas e hóspedes.

**RNF2** - O sistema deve ser simples e intuitivo para uso por funcionários sem treinamento técnico.

**RNF3** - O sistema deve suportar uso intenso em horários de pico (check-in/check-out).

---

### Interface

**RNF4** - O sistema deve apresentar um mapa visual dos quartos com uso de cores para status.

**RNF5** - A interface deve ser clara e legível em monitores padrão de recepção.

---

### Segurança e Confiabilidade

**RNF6** - O sistema deve garantir a integridade dos dados de reservas e consumos.

**RNF7** - O sistema deve restringir o acesso apenas a usuários autorizados.

---

### Disponibilidade

**RNF8** - O sistema deve estar disponível durante todo o horário de funcionamento do hotel.

---

## 3. Casos de Uso (UC)

### UC01 - Realizar Reserva
**Ator:** Funcionário da recepção  
**Descrição:** Cadastrar uma nova reserva com dados do hóspede e período de estadia.

---

### UC02 - Consultar Reserva por CPF
**Ator:** Funcionário da recepção  
**Descrição:** Localizar rapidamente uma reserva utilizando CPF ou documento.

---

### UC03 - Realizar Check-in
**Ator:** Funcionário da recepção  
**Descrição:** Associar hóspede a um quarto disponível no momento da chegada.

---

### UC04 - Realizar Check-out
**Ator:** Funcionário da recepção  
**Descrição:** Finalizar estadia e calcular automaticamente o valor total (diária + consumo).

---

### UC05 - Visualizar Mapa de Quartos
**Ator:** Funcionário / Gerente  
**Descrição:** Visualizar todos os quartos com status em cores (livre, ocupado, limpeza).

---

### UC06 - Atualizar Status de Limpeza
**Ator:** Camareira  
**Descrição:** Atualizar status do quarto após limpeza.

---

### UC07 - Registrar Consumo
**Ator:** Funcionário  
**Descrição:** Registrar itens consumidos pelo hóspede durante a estadia.

---

### UC08 - Gerar Relatórios
**Ator:** Gerente  
**Descrição:** Visualizar relatórios de faturamento, ocupação e consumo.
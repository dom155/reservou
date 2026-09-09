# 🍽️ Reservou

Aplicação web desenvolvida como projeto acadêmico para gerenciamento de reservas em restaurantes.

O sistema permite que o usuário visualize a disponibilidade de mesas, selecione uma data, escolha uma mesa, defina horário, quantidade de pessoas e realize uma reserva de forma interativa.

O projeto também possui gerenciamento de reservas utilizando uma API local com JSON Server.

---

## 🚀 Tecnologias utilizadas

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![JSON](https://img.shields.io/badge/JSON-000000?style=flat&logo=json&logoColor=white)

---

## 📌 Funcionalidades

- Visualização de disponibilidade por data
- Navegação entre meses através de calendário
- Seleção interativa de mesas
- Escolha de horário para reserva
- Definição da quantidade de pessoas
- Opção de estacionamento
- Confirmação da reserva
- Consulta de reservas existentes
- Criação de novas reservas
- Atualização de reservas
- Exclusão de reservas
- Persistência dos dados através de API local

---

## 🪑 Sistema de Reservas

A aplicação possui uma interface para seleção de mesas do restaurante.

O usuário pode:

1. Selecionar uma data disponível
2. Escolher uma mesa
3. Definir o horário
4. Informar a quantidade de pessoas
5. Escolher se deseja estacionamento
6. Confirmar a reserva

Após a confirmação, os dados da reserva são armazenados através da API local.

---

## 🔄 CRUD de Reservas

O projeto implementa operações CRUD utilizando JavaScript e JSON Server.

As principais operações são:

```text
GET    → Consultar reservas
POST   → Criar uma nova reserva
PUT    → Atualizar uma reserva
DELETE → Excluir uma reserva

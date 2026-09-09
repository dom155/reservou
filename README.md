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

```

A API utilizada pelo projeto é executada localmente no endereço:

```text
http://localhost:3000/reservas
```

---

## 🗂️ Estrutura do projeto

```text
reservou/
│
├── DB/
│   └── db.json
│
├── css/
│   └── arquivos de estilização
│
├── img/
│   └── imagens utilizadas no projeto
│
├── pages/
│   ├── index.html
│   └── reservas.html
│
├── script/
│   ├── crud.js
│   ├── interface.js
│   └── script.js
│
└── README.md
```

---

## ⚙️ Funcionamento

O frontend da aplicação foi desenvolvido utilizando HTML, CSS e JavaScript.

As informações das reservas são armazenadas em um arquivo JSON, que funciona como banco de dados local através do JSON Server.

O fluxo da aplicação funciona da seguinte maneira:

```text
Usuário
   ↓
Interface Web
   ↓
JavaScript
   ↓
API REST
   ↓
JSON Server
   ↓
db.json
```

---

## ▶️ Como executar o projeto

Para executar o projeto localmente, é necessário ter o Node.js instalado.

### 1. Clone o repositório

```bash
git clone https://github.com/dom155/reservou.git
```

### 2. Acesse a pasta do projeto

```bash
cd reservou
```

### 3. Instale o JSON Server

```bash
npm install -g json-server
```

### 4. Inicie a API

```bash
json-server --watch DB/db.json --port 3000
```

A API estará disponível em:

```text
http://localhost:3000/reservas
```

### 5. Abra a aplicação

Abra o arquivo:

```text
pages/index.html
```

no navegador.

Também é possível utilizar uma extensão como **Live Server** no Visual Studio Code para executar a aplicação.

---

## 🎯 Objetivo do projeto

O projeto foi desenvolvido com o objetivo de aplicar conhecimentos de desenvolvimento web em um cenário próximo de uma aplicação real.

Durante o desenvolvimento foram trabalhados conceitos como:

- Manipulação do DOM
- Eventos em JavaScript
- Consumo de API REST
- Requisições HTTP
- CRUD
- Manipulação de JSON
- Organização de arquivos
- Desenvolvimento de interfaces
- Persistência de dados

---

## 🎓 Contexto

Projeto acadêmico desenvolvido durante minha graduação em **Sistemas de Informação na PUC Minas**.

A proposta foi desenvolver uma aplicação web que permitisse aplicar conhecimentos de HTML, CSS e JavaScript juntamente com integração de dados através de uma API local.

---

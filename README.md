# 👥 Angular Material Clients Manager

> Sistema de Gestão de Clientes (CRUD) Full-SPA desenvolvido com a robustez do **Angular 18** e a elegância do **Angular Material**.

![Angular Badge](https://img.shields.io/badge/Angular-18-DD0031?style=for-the-badge&logo=angular&logoColor=white)
![Material Badge](https://img.shields.io/badge/Angular_Material-UI-3F51B5?style=for-the-badge&logo=angular&logoColor=white)
![BrasilAPI Badge](https://img.shields.io/badge/API-BrasilAPI-009C3B?style=for-the-badge&logo=brazil&logoColor=white)

---

## 💻 Sobre o Projeto

Este projeto é uma **Single Page Application (SPA)** focada em demonstrar as melhores práticas de desenvolvimento Front-End moderno.

Mais do que um simples cadastro, a aplicação implementa um ecossistema reativo onde a experiência do usuário é prioridade. O sistema utiliza **LocalStorage** para persistência de dados (simulando um Backend) e consome a **BrasilAPI** para fornecer dados geográficos reais e atualizados do IBGE.

### 🎯 Destaques Técnicos
* **Componentização Inteligente:** Separação clara entre responsabilidades de Cadastro e Consulta.
* **Integração de APIs:** Consumo de dados externos (REST) para popular selects dinâmicos (Estados/Cidades).
* **UX Profissional:** Uso extensivo de componentes do Angular Material (Tables, Dialogs, Snackbars, Form Fields).

---

## ✨ Funcionalidades

* ✅ **CRUD Completo:** Criação, Leitura, Atualização e Remoção de clientes.
* ✅ **Busca de Endereço Dinâmica:** Integração com a **BrasilAPI**. Ao selecionar um Estado (UF), o sistema busca automaticamente os municípios correspondentes via HTTP.
* ✅ **Persistência Local:** Os dados são salvos no `LocalStorage` do navegador, mantendo o cadastro mesmo após recarregar a página.
* ✅ **Interface Responsiva:** Tabelas com paginação e formulários adaptáveis.

---

## 📸 Telas do Projeto

### 🗂️ Tela de Consulta (Dashboard)
Visualização de dados em tabela estilizada com ações rápidas.
![Tela de Consulta](image-1.png)

### 🧾 Formulário de Cadastro
Formulário com validação e carregamento dinâmico de cidades.
![Tela de Cadastro](image.png)

---

## 🚀 Tecnologias Utilizadas

* **Framework:** [Angular v18](https://angular.io/) (Core)
* **UI Kit:** [Angular Material](https://material.angular.io/) (Design System)
* **Linguagem:** TypeScript 5.5
* **Reatividade:** RxJS (Observables e Subjects)
* **Estilização:** SCSS (Sass)
* **Dados Externos:** [BrasilAPI](https://brasilapi.com.br/) (Fonte de dados do IBGE)

---

## ⚙️ Instalação e Execução

Siga os passos abaixo para rodar o projeto localmente:

### Pré-requisitos
* Node.js (LTS v18 ou superior)
* Angular CLI instalado globalmente (`npm install -g @angular/cli`)

### Passo a Passo

1. **Clone o repositório:**
   ```bash
   git clone [https://github.com/Welberrr/Academic_Crud-Angular-Material.git](https://github.com/Welberrr/Academic_Crud-Angular-Material.git)
2. Acesse o diretório:

Bash

cd Academic_Crud-Angular-Material

3. Instale as dependências:

Bash

npm install

4. Execute o servidor:

Bash

ng serve

5. Acesse: Abra seu navegador em http://localhost:4200/

# 📱 Sistema de Gerenciamento de Reservas (Front-end Mobile)
### Aplicação em React Native para Interação com a API de Reservas

## 🌟 Sobre o Projeto

Este repositório contém o código-fonte da aplicação **mobile** desenvolvida em **React Native** para o Sistema de Gerenciamento de Reservas.

O Front-end é responsável por:
1.  **Consumir** a API RESTful do Back-end (construída em Spring Boot).
2.  **Gerenciar** a autenticação via JWT.
3.  Fornecer a **interface de usuário** para Alunos, Professores e Administradores realizarem e gerenciarem suas reservas de equipamentos e salas.

---

## 🛠️ Tecnologias Utilizadas

| Categoria | Tecnologia | Detalhes |
| :--- | :--- | :--- |
| **Framework** | **React Native** | Desenvolvimento de aplicações nativas para Android e iOS. |
| **Linguagem** | **JavaScript** | - |

### Repositório do Back-end
* O código da API (Spring Boot) está em: [Janetoerick/reservas-backend](https://github.com/Janetoerick/WEBII) (Ajuste este link se for diferente)

---

## 🔑 Funcionalidades Chave

A aplicação mobile permite aos usuários:

* **Autenticação Segura (JWT):** Login para os perfis Admin, Professor e Aluno.
* **Visualização de Recursos:** Listar equipamentos e salas disponíveis.
* **Agendamento:** Criar e modificar Reservas Individuais e Grupais (com fluxo específico por perfil).
* **Gestão de Perfil:** Visualizar histórico e cancelar reservas.
* **Administração (somente Admin):** Interfaces para CRUD (Criação, Leitura, Atualização, Deleção) de Usuários, Equipamentos e Salas.

---

## 🚀 Instalação e Execução

Para rodar o projeto em seu ambiente de desenvolvimento, siga os passos abaixo:

### Pré-requisitos
* **Node.js e npm/Yarn**
* **Expo CLI** ou **React Native CLI** (Dependendo da sua configuração)
* **Android Studio / Xcode** ou Emulador de preferência

### Configuração do Ambiente

1.  **Clone o Repositório:**
    ```bash
    git clone https://github.com/Janetoerick/Sistema-de-reserva-front-end.git
    cd Sistema-de-reserva-front-end
    ```

2.  **Instale as Dependências:**
    ```bash
    npm install
    # ou
    yarn install
    ```

3.  **Configuração da API (Backend):**
    * Certifique-se de que o **Back-end (Spring Boot)** esteja rodando e acessível.

4.  **Execute a Aplicação:**
    * **Para Emulador/Dispositivo:**
        ```bash
        npm start
        # ou
        yarn start
        ```
    * Siga as instruções exibidas no terminal (usualmente pressionando `a` para Android ou `i` para iOS via Expo).

---

## 🎥 Apresentação do Sistema

Você pode conferir a demonstração e apresentação completa do sistema no vídeo abaixo:

* **Apresentação em Vídeo:** [Assista à Apresentação do Sistema](https://youtu.be/ncVo2c9saAQ)
  
---


## 👤 Autor e Contato

Este projeto foi desenvolvido por:

* **Nome:** Janeto Erick
* **GitHub:** https://github.com/Janetoerick
* **E-mail:** janetoerick18@gmail.com

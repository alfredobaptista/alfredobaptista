<h1 align="center">Olá, sou o Alfredo Baptista 👋</h1>

<p align="center">
  <strong>Backend Developer | Java • Spring Boot • System Design • System Integration</strong>
</p>

<p align="center">
  Finalista de Ciências da Computação na Universidade Agostinho Neto 
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/alfredobaptista/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:baptistaalfredo81@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <a href="https://leetcode.com/u/freddy_223/" target="_blank">
    <img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" alt="LeetCode" />
  </a>
</p>

---

## 👨‍💻 Sobre Mim

Sou **finalista de Ciências da Computação na Universidade Agostinho Neto**, com foco no desenvolvimento **Back-End utilizando Java e Spring Boot**.

Tenho interesse em construir sistemas que sejam não apenas funcionais, mas também **bem estruturados, resilientes e preparados para crescer**, explorando na prática conceitos de arquitectura de software, sistemas distribuídos, performance e escalabilidade.

Nos meus projectos tenho trabalhado principalmente com:

* ☕ **Java & Spring Boot**
* 🔌 **APIs REST & integração entre sistemas**
* 🗄️ **PostgreSQL, Redis & MongoDB**
* 📨 **RabbitMQ & processamento assíncrono**
* 🐳 **Docker & Docker Compose**
* 🏗️ **Clean Architecture & Ports & Adapters**
* 🛡️ **Resiliência, idempotência e controlo de concorrência**
* 🧪 **JUnit 5, Mockito & Testcontainers**
* 📐 **System Design & arquitectura de sistemas**

Paralelamente, estou a aprofundar conhecimentos em **MuleSoft, Anypoint Platform e DataWeave**, com foco em **Integração de Sistemas e arquitecturas empresariais**.

---

## 🚀 Projectos em Destaque

### 🔗 URL Shortener

**Java 21 · Spring Boot · PostgreSQL · Redis · RabbitMQ · Docker · k6**

<a href="https://github.com/alfredobaptista/url-shortener">
  github.com/alfredobaptista/url-shortener
</a>

Implementação própria de um serviço de **encurtamento de URLs**, desenvolvida a partir de um desafio de System Design.

O projecto explora problemas relacionados com **performance, caching, concorrência, processamento assíncrono e escalabilidade**.

**Principais aspectos:**

* Clean Architecture / Ports & Adapters
* Cache-Aside com Redis
* Rate limiting distribuído com Redis + Lua
* Analytics assíncrono com RabbitMQ
* Consumer assíncrono dedicado para processamento de eventos
* Geração de códigos Base62
* Expiração e eliminação de URLs
* Testes automatizados com JUnit 5 e Mockito
* Testes de carga com k6
* Containerização com Docker

O projecto inclui também uma análise do comportamento do sistema sob diferentes níveis de concorrência e uma evolução arquitectural para **escalabilidade horizontal**.

---

### 🔔 Reliable Notification Platform

**Java 21 · Spring Boot · RabbitMQ · PostgreSQL · Docker · Testcontainers**

<a href="https://github.com/alfredobaptista/notification-platform">
  github.com/alfredobaptista/notification-platform
</a>

Plataforma de notificações **assíncronas e multicanal**, desenvolvida com foco em **arquitectura orientada a eventos, desacoplamento e resiliência**.

**Principais aspectos:**

* Clean Architecture + Hexagonal Architecture
* Processamento assíncrono com RabbitMQ
* Canais independentes de Email, SMS e Push
* Strategy Pattern para processamento por canal
* Retry e Dead Letter Queue (DLQ)
* Idempotência através de `idempotency-key`
* Integração com provedores externos
* PostgreSQL para persistência
* Testes de integração com Testcontainers
* Observabilidade com Actuator e Micrometer
* Docker e Docker Compose

A arquitectura permite adicionar novos canais e integrações sem alterar a lógica central da aplicação.

---

### 💳 Resilient Payment Gateway

**Java 21 · Spring Boot · PostgreSQL · Redis · Resilience4j · OpenFeign · Docker**

<a href="https://github.com/alfredobaptista/resilient-payment-gateway">
  github.com/alfredobaptista/resilient-payment-gateway
</a>

Gateway de pagamentos desenvolvido para explorar problemas de **resiliência, consistência e idempotência** em sistemas transaccionais.

* Idempotência utilizando Redis
* Protecção contra transacções duplicadas
* Circuit Breaker com Resilience4j
* Retry para falhas transitórias
* Comunicação entre serviços com OpenFeign
* Persistência transaccional com PostgreSQL

---

### 🏦 Banking Application

**Java 21 · Spring Boot · PostgreSQL · Spring Security · JWT · Docker**

<a href="https://github.com/alfredobaptista/bankApplication">
  github.com/alfredobaptista/bankApplication
</a>

Aplicação bancária desenvolvida para explorar **segurança, transacções, concorrência e consistência de dados**.

* Operações transaccionais sobre contas
* Pessimistic Locking
* Controlo de concorrência
* Consistência dos saldos
* Autenticação com JWT
* Autorização baseada em RBAC
* PostgreSQL e Docker

---

### 🎓 Sistema de Correcção de Exames — UAN

**Python · OpenCV · OMR · APIs REST**

Projecto institucional desenvolvido para a **Universidade Agostinho Neto**, com o objectivo de automatizar a correcção de exames.

* Processamento de imagens com OpenCV
* Detecção e interpretação de marcações OMR
* Automatização da correcção
* Integração através de APIs REST
* Exportação dos resultados

> 🔒 Projecto institucional. O código não está disponível publicamente.

---

## 🧠 Áreas de Interesse

<div align="center">

| Backend Engineering |     System Design     |     System Integration    |
| :-----------------: | :-------------------: | :-----------------------: |
|      APIs REST      | Sistemas distribuídos | Integração entre sistemas |
|     Resiliência     |        Caching        |      APIs & serviços      |
|      Mensageria     |     Escalabilidade    |          MuleSoft         |
|     Concorrência    |      Performance      |     Anypoint Platform     |
|     Persistência    |      Event-Driven     |         DataWeave         |

</div>

---

## 🛠️ Tecnologias

### Backend

<div align="center">
  <img src="https://skillicons.dev/icons?i=java,spring,python,nodejs,typescript,express" height="45" alt="Backend technologies" />
</div>

### Bases de Dados & Mensageria

<div align="center">
  <img src="https://skillicons.dev/icons?i=postgres,mongodb,redis,rabbitmq" height="45" alt="Database and messaging technologies" />
</div>

### DevOps & Ferramentas

<div align="center">
  <img src="https://skillicons.dev/icons?i=docker,git,github,maven,postman" height="45" alt="DevOps and development tools" />
</div>

### Arquitectura & Qualidade

**Clean Architecture · Ports & Adapters · SOLID · Clean Code · Design Patterns · JUnit 5 · Mockito · Testcontainers**

### Integração

**REST APIs · MuleSoft · Anypoint Platform · DataWeave**

> MuleSoft, Anypoint Platform e DataWeave encontram-se actualmente **em formação**.

---

## 📚 Formação

### 🎓 Licenciatura em Ciências da Computação

**Universidade Agostinho Neto (UAN)**
2022 — 2027

### Formação Complementar

* **Spring Boot Expert: JPA, REST, JWT, OAuth2 com Docker e AWS** — Udemy
* **MuleSoft 4.X Complete Guide For Beginners — Hands On Projects** — Udemy *(Em curso)*
* **Docker Essentials** — LINUXtips
* **Bootcamp Santander — Back-End com Java** — 78h
* **CI&T — Back-End com Java & AWS** — 72h
* **RabbitMQ Training Course** — CloudAMQP

---

## 🌱 Actualmente

```text
🔭 Desenvolvendo projectos Back-End com Java e Spring Boot
📐 A aprofundar System Design e arquitectura de sistemas
📨 A explorar sistemas orientados a eventos e mensageria
⚡ A estudar performance, caching e escalabilidade
🔗 A aprofundar Integração de Sistemas com MuleSoft
🌐 A estudar Anypoint Platform e DataWeave
🐳 A trabalhar com Docker e ambientes conteinerizados
💳 Interessado em sistemas financeiros e arquitecturas transaccionais
```

---

## 📊 GitHub Stats

<div align="center">

  <img src="https://github-readme-stats.vercel.app/api?username=alfredobaptista&show_icons=true&include_all_commits=true&count_private=true&theme=dracula&hide_border=false" height="170" alt="GitHub statistics" />

  <img src="https://github-readme-stats.vercel.app/api/top-langs?username=alfredobaptista&layout=compact&langs_count=6&theme=dracula&hide_border=false" height="170" alt="Top languages" />

</div>

---

## 📫 Contactos

<div align="center">

<a href="https://www.linkedin.com/in/alfredobaptista/">
  <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
</a>

<a href="mailto:baptistaalfredo81@gmail.com">
  <img src="https://img.shields.io/badge/Email-Contact-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
</a>

</div>

---

<p align="center">
  <i>Construindo sistemas Back-End com foco em arquitectura, integração, resiliência e escalabilidade.</i>
</p>

<p align="center">
  Luanda, Angola
</p>


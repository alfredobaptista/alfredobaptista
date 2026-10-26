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
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <a href="https://leetcode.com/u/freddy_223/" target="_blank">
    <img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" alt="LeetCode" />
  </a>
</p>

---

## 👨‍💻 Sobre Mim

Sou finalista de **Ciências da Computação na Universidade Agostinho Neto**, com foco no desenvolvimento Back-End utilizando **Java e Spring Boot**.

Interesso-me pela construção de sistemas bem estruturados, fiáveis e preparados para crescer. Nos meus projectos, procuro aplicar princípios de arquitectura de software e explorar problemas relacionados com persistência, concorrência, consistência de dados, processamento assíncrono e resiliência.

Tenho trabalhado principalmente com:

- ☕ **Java e Spring Boot** — desenvolvimento de aplicações Back-End.
- 🔌 **APIs REST** — desenho, implementação e integração de serviços.
- 🗄️ **PostgreSQL, Redis e MongoDB** — persistência, caching e modelação de dados.
- 📨 **RabbitMQ** — mensageria e processamento assíncrono.
- 🏗️ **Clean Architecture, Hexagonal Architecture e SOLID** — organização e separação de responsabilidades.
- 🛡️ **Idempotência, retries e controlo de concorrência** — tratamento de falhas e operações transaccionais.
- 🧪 **JUnit 5, Mockito e Testcontainers** — testes e validação de aplicações.
- 🐳 **Docker e Docker Compose** — containerização e ambientes de desenvolvimento.
- 🟨 **Node.js, TypeScript e Express.js** — desenvolvimento de APIs em projectos complementares.

Paralelamente, estou a aprofundar conhecimentos em **MuleSoft, Anypoint Platform e DataWeave**, com interesse na integração de sistemas e em arquitecturas empresariais.

Procuro oportunidades para aplicar os meus conhecimentos, colaborar com equipas de desenvolvimento e continuar a evoluir como engenheiro de software.

---

## 🚀 Projectos em Destaque

### 🔗 URL Shortener

**Java 21 · Spring Boot · PostgreSQL · Redis · Docker · k6**

Repositório: [github.com/alfredobaptista/url-shortener](https://github.com/alfredobaptista/url-shortener)

Serviço de encurtamento e redireccionamento de URLs, desenvolvido a partir de um desafio de System Design, com foco em performance, caching, persistência e escalabilidade.

**Principais aspectos:**

- Clean Architecture e separação entre domínio, aplicação e adaptadores.
- Redis com estratégia Cache-Aside para optimizar os redireccionamentos.
- PostgreSQL para persistência dos URLs.
- Geração de códigos curtos com Base62 e SecureRandom.
- Testes de carga com k6 para avaliar o comportamento sob concorrência.
- Docker e Docker Compose para execução do ambiente local.

**Benchmark local:** aproximadamente 3.422 req/s, com 50 VUs e 0% de erros no cenário testado.

> Os resultados são específicos do ambiente e da configuração utilizados nos testes, não constituindo uma garantia de desempenho em produção.

### 🔔 Reliable Notification Platform

**Java 21 · Spring Boot · RabbitMQ · PostgreSQL · Docker · Testcontainers**

Repositório: [github.com/alfredobaptista/notification-platform](https://github.com/alfredobaptista/notification-platform)

Plataforma de notificações assíncronas e multicanal, desenvolvida para explorar o desacoplamento de componentes, o processamento orientado a eventos e o tratamento de falhas.

**Principais aspectos:**

- Clean Architecture e Ports & Adapters.
- Processamento assíncrono com RabbitMQ.
- Organização dos canais de Email, SMS e Push.
- Strategy Pattern para separar o processamento por canal.
- Mecanismos de retry e Dead Letter Queue (DLQ).
- Idempotência através de `Idempotency-Key`.
- PostgreSQL para persistência dos dados.
- Testes de integração com Testcontainers.
- Observabilidade através do Spring Boot Actuator.
- Containerização com Docker e Docker Compose.

O projecto explora formas de tornar o processamento de notificações mais resiliente e facilitar a extensão da aplicação com novos canais.

### 💳 Resilient Payment Gateway

**Java 21 · Spring Boot · PostgreSQL · Redis · Resilience4j · Docker**

Repositório: [github.com/alfredobaptista/resilient-payment-gateway](https://github.com/alfredobaptista/resilient-payment-gateway)

Projecto Back-End orientado para o estudo de sistemas transaccionais, com foco na prevenção de operações duplicadas e no tratamento de falhas em integrações de pagamento.

**Principais aspectos:**

- Idempotência para reduzir o risco de processamento duplicado.
- Redis para suportar mecanismos de controlo de idempotência.
- PostgreSQL para persistência transaccional.
- Circuit Breaker com Resilience4j.
- Retry para tratamento de falhas transitórias.
- Docker para facilitar a execução do ambiente.

O objectivo é compreender como proteger operações financeiras contra falhas e como melhorar a fiabilidade de serviços que dependem de outros sistemas.

### 💰 Finance API

**Node.js · TypeScript · Express.js · PostgreSQL · Prisma · JWT**

Repositório: [github.com/alfredobaptista/finance-backend](https://github.com/alfredobaptista/finance-backend)

API REST desenvolvida no âmbito do Desafio Back-End da Kinvo, para gestão de transacções financeiras, autenticação de utilizadores e consulta de saldo.

**Principais aspectos:**

- Organização inspirada na arquitectura hexagonal.
- Persistência com PostgreSQL e Prisma.
- Suporte a uma implementação de persistência em memória.
- Autenticação com JWT.
- Consulta de transacções com filtros por data e paginação.
- Separação de responsabilidades entre domínio e infraestrutura.

### 🎓 Sistema de Correcção de Exames — UAN

**Python · OpenCV · OMR · APIs REST**

Projecto institucional desenvolvido no contexto da Universidade Agostinho Neto, orientado para a automatização da correcção de exames.

**Principais aspectos:**

- Processamento de imagens com OpenCV.
- Detecção e interpretação de marcações através de OMR (*Optical Mark Recognition*).
- Automatização do processo de correcção.
- Integração através de APIs REST.
- Exportação dos resultados.

> 🔒 Projecto institucional. O código-fonte não está disponível publicamente.

---

## 🧠 Áreas de Interesse

<div align="center">

| Backend Engineering | System Design | System Integration |
|:---:|:---:|:---:|
| APIs REST | Sistemas distribuídos | Integração entre serviços |
| Persistência de dados | Concorrência | APIs empresariais |
| Testes automatizados | Caching e performance | MuleSoft |
| Mensageria assíncrona | Resiliência | Anypoint Platform |
| Arquitectura de software | Escalabilidade | DataWeave |

</div>

---

## 🛠️ Tecnologias e Ferramentas

### Backend

<div align="center">
  <img src="https://skillicons.dev/icons?i=java,spring,python,nodejs,typescript,express" height="45" alt="Tecnologias Back-End" />
</div>

### Bases de Dados e Mensageria

<div align="center">
  <img src="https://skillicons.dev/icons?i=postgres,mongodb,redis,rabbitmq" height="45" alt="Bases de dados e mensageria" />
</div>

### DevOps e Ferramentas

<div align="center">
  <img src="https://skillicons.dev/icons?i=docker,git,github,maven,postman" height="45" alt="Ferramentas de desenvolvimento" />
</div>

### Arquitectura e Qualidade

**Clean Architecture · Hexagonal Architecture · Ports & Adapters · SOLID · Clean Code · Design Patterns · JUnit 5 · Mockito · Testcontainers**

### Integração de Sistemas

**REST APIs · MuleSoft · Anypoint Platform · DataWeave**

> MuleSoft, Anypoint Platform e DataWeave encontram-se actualmente em formação.

---

## 📚 Formação

### 🎓 Licenciatura em Ciências da Computação

**Universidade Agostinho Neto (UAN)**

2022 — 2027 · Em curso

### Formação Complementar

- **Spring Boot Expert: JPA, REST, JWT, OAuth2 com Docker e AWS** — Udemy.
- **MuleSoft 4.X Complete Guide For Beginners — Hands On Projects** — Udemy *(em curso)*.
- **Docker Essentials** — LINUXtips.
- **Bootcamp Santander — Back-End com Java** — 78 horas.
- **CI&T — Back-End com Java & AWS** — 72 horas.
- **RabbitMQ Training Course** — CloudAMQP.

---

## 🌱 Actualmente

- 🔭 A desenvolver projectos Back-End com Java e Spring Boot.
- 📐 A aprofundar arquitectura de software e System Design.
- 📨 A explorar mensageria, processamento assíncrono e sistemas distribuídos.
- ⚡ A estudar performance, caching, concorrência e escalabilidade.
- 🐳 A trabalhar com Docker e ambientes conteinerizados.
- 🔗 A aprofundar integração de sistemas com MuleSoft e DataWeave.
- 💳 A explorar desafios de consistência e fiabilidade em sistemas transaccionais.

---

## 📊 GitHub Stats

<div align="center">
  <img
    src="https://github-readme-stats.vercel.app/api?username=alfredobaptista&show_icons=true&include_all_commits=true&count_private=true&theme=dracula&hide_border=false"
    height="170"
    alt="Estatísticas do GitHub"
  />
  <img
    src="https://github-readme-stats.vercel.app/api/top-langs?username=alfredobaptista&layout=compact&langs_count=6&theme=dracula&hide_border=false"
    height="170"
    alt="Linguagens mais utilizadas"
  />
</div>

---

## 📫 Contactos

<div align="center">
  <a href="https://www.linkedin.com/in/alfredobaptista/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:baptistaalfredo81@gmail.com">
    <img src="https://img.shields.io/badge/Email-Contact-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <a href="https://leetcode.com/u/freddy_223/" target="_blank">
    <img src="https://img.shields.io/badge/LeetCode-Profile-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" alt="LeetCode" />
  </a>
</div>

---

<p align="center">
  <i>Construindo, testando e aprendendo — um projecto de cada vez.</i>
</p>

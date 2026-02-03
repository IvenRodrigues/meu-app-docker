# 🐳 Dockerized Node.js App

Este é um projeto prático para demonstrar a containerização de uma aplicação **Node.js** conectada a um banco de dados **PostgreSQL**, utilizando **Docker** e **Docker Compose**.

O objetivo é criar um ambiente de desenvolvimento reproduzível, isolado e pronto para produção.

---

## 🚀 Tecnologias Utilizadas

* **Node.js** (Backend)
* **Docker** (Containerização com Multi-stage building)
* **Docker Compose** (Orquestração de App + Banco)
* **PostgreSQL** (Banco de dados)

---

## 📂 Estrutura do Projeto

```text
.
├── src/                # Código fonte da aplicação
│   ├── index.js        # Servidor HTTP
│   └── package.json    # Dependências
├── Dockerfile          # Receita da imagem Docker (Otimizada)
├── docker-compose.yml  # Configuração dos serviços (App + DB)
└── README.md           # Documentação

# 📊 Projeto de Engenharia e Análise de Dados com Docker, Python, Streamlit e PostgreSQL

Este projeto foi desenvolvido com o objetivo de demonstrar conhecimentos práticos em **engenharia de dados** e **análise de dados**, utilizando ferramentas modernas como **Docker**, **Python**, **FastAPI**, **Streamlit** e **PostgreSQL**.

---

## 🛠 Tecnologias Utilizadas

- **Python** – desenvolvimento da API e do dashboard
- **FastAPI** – criação de uma API leve e eficiente
- **Streamlit** – construção de dashboards interativos
- **PostgreSQL** – banco de dados relacional para persistência dos dados
- **Docker & Docker Compose** – orquestração dos serviços em containers isolados
- **VSCode** – IDE para desenvolvimento e organização do projeto

---

## 📁 Estrutura do Projeto

```text
DockerCompose/
├── api/                        # API em Python com FastAPI
│   ├── main.py
│   ├── Dockerfile
│   └── requirements.txt
│
├── dashboard/                  # Dashboard com Streamlit
│   ├── app.py
│   ├── Dockerfile
│   └── requirements.txt
│
├── init.sql                    # Script de inicialização do banco PostgreSQL
├── docker-compose.yml          # Arquivo de orquestração Docker
└── README.md                   # Documentação do projeto

🚀 Como Executar o Projeto
Pré-requisitos
Docker instalado (Download aqui)

Docker Compose

Passos para executar
bash
Copy
Edit
# Clone o repositório
git clone https://github.com/seu-usuario/DockerCompose.git
cd DockerCompose

# Suba os containers
docker-compose up --build
Acesso aos serviços
📊 Dashboard (Streamlit): http://localhost:8501

🧪 API (FastAPI Docs): http://localhost:8000/docs


🎯 Objetivo do Projeto
Simular um ambiente real de dados usando containers Docker

Construir uma API RESTful para servir dados estruturados

Criar um dashboard interativo com gráficos e KPIs

Praticar boas práticas de organização de projetos de dados

🧠 Possíveis Extensões
Pipeline de ETL com agendamento

Integração com ferramentas de orquestração (ex: Airflow)

Adição de autenticação na API e dashboard

Exportação de relatórios automatizados
**📌 Academia-DSA**

Um sistema web para gerenciamento de dados de uma academia (usuários, planos, agendamentos, pagamentos etc.), construído com uma arquitetura em camadas, seguindo boas práticas de organização e pensando em escalabilidade e manutenção.

Esse repositório serve como projeto de estudo/portfólio, mostrando organização de código backend + frontend, integração com banco de dados e suporte a Docker para desenvolvimento e produção.

**🧠 Visão do Projeto**

Esse projeto implementa um sistema completo para gerenciar uma academia:
```
✔ Cadastro e gerenciamento de alunos
✔ Controle de planos e pagamentos
✔ Login/autenticação
✔ Backend organizado em camadas (classes, controladores, conectores)
✔ Banco de dados estruturado em database
✔ Interfaces web em templates + static
✔ Scripts/infra para Docker (docker)
✔ Diagramas e documentação em diagramas
```
**📁 Estrutura de Pastas**
```
📦academia-DSA
 ┣ 📂classes/             # Modelos das entidades do sistema
 ┣ 📂conectores/          # Conexões com banco ou serviços externos
 ┣ 📂controladores/       # Lógica de negócio e rotas/handlers
 ┣ 📂database/            # Scripts/arquivos para inicializar banco
 ┣ 📂diagramas/           # Diagramas de arquitetura/ER
 ┣ 📂docker/              # Configurações de container/docker-compose
 ┣ 📂static/              # CSS, JS, imagens estáticas
 ┣ 📂templates/           # Views/HTML para frontend
 ┣ 📜.gitignore
 ┣ 📜README.md

```

🚀 Tecnologias

````Esse projeto usa :

Linguagem principal: Python 

Framework web: Flask / Django 

Banco de dados: Postgres / SQLite / MySQL 

Docker + Docker Compose para ambiente isolado

HTML/CSS/JS no frontend

MVC / arquitetura em camadas
```
````

**🛠 Rodando o Projeto**
```
🔹 Com Docker (recomendado)

Instale o Docker e Docker Compose

No terminal, na raiz do projeto:

docker compose up --build


Acesse: http://localhost:8000 (ou porta definida no compose)
```
```
🔹 Sem Docker

Crie um ambiente virtual:

python -m venv .venv
source .venv/bin/activate


Instale dependências:

pip install -r requirements.txt


Configure variáveis de ambiente para o banco de dados

Inicie o servidor:

python run.py


Acesse no navegador:

http://localhost:5000

```
**🧩 Banco de Dados**

```
Dentro de database/ estão os scripts de criação de tabelas e seeds iniciais.
```
**📌 Diagramas e Documentação**
```
A pasta diagramas/ contém:

Diagrama entidade-relacionamento (ER)

Fluxos de usuário

UML de classes

Esses artefatos ajudam a entender escolhas de arquitetura e relações entre as partes.
```
**🤝 Como Contribuir**
```
Fork esse repositório

Crie uma branch com sua feature/correção

Faça commits claros e concisos

Abra um pull request descrevendo sua mudança
```

**📝 Licença**

Este projeto está sob a licença MIT

# 🐍 Projeto Web com Flask

Este é um projeto web simples desenvolvido em Python com o framework **Flask**. O objetivo desta aplicação é servir como base para praticar rotas, renderização de páginas e manipulação de requisições web.

---

##  Sobre o Projeto

A aplicação consiste em um servidor web local que processa requisições HTTP e entrega respostas dinâmicas no navegador.

### ⚙️ Funcionalidades Principais:
- Server HTTP leve rodando localmente (`http://127.0.0.1:5000`).
- Rotas personalizadas para exibição de páginas ou respostas JSON.
- Módulo de desenvolvimento ativado com *debug mode* para atualização em tempo real.

---

##  Estrutura do Projeto

```text
flask3/
├── Flask/
│   ├── .venv/            # Ambiente virtual de dependências
│   ├── static/           # Arquivos estáticos (CSS, JS, Imagens)
│   ├── templates/        # Arquivos HTML renderizados pelas rotas
│   └── app.py            # Script principal do servidor Flask
├── .gitignore            # Arquivos ignorados pelo Git
└── README.md             # Documentação do projeto

# Projeto CRUD com Flask - Cadastro de Pessoas

Este é um projeto simples de aplicação web desenvolvido com Python + Flask que permite o cadastro de pessoas com as funcionalidades básicas de um sistema CRUD:

Criar - Adicionar
Ler - Visualizar
Atualizar - Editar
Deletar - Excluir

## Tecnologias Utilizadas

- [Python 3.10+](https://www.python.org/)
- [Flask](https://flask.palletsprojects.com/)
- [SQLite](https://www.sqlite.org/)
- [Bootstrap 5 (CDN)](https://getbootstrap.com/)

## Estrutura do Projeto

crud-flask

app.py # Arquivo principal Flask
form_db.db # Banco de dados SQLite
templates
layout.html # Layout base com Bootstrap
index.html # Lista de cadastros
add_user.html # Formulário de cadastro
edit_user.html # Formulário de edição


## Como Executar o Projeto

```bash
git clone https://github.com/seu-usuario/crud-flask.git
cd crud-flask

python -m venv venv
venv\Scripts\activate

pip install flask

python app.py

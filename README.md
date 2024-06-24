# Jogoteca

Aplicação web em Python utilizando Flask para gerenciar jogos e usuários.

## Funcionalidades

- **Gerenciamento de Jogos**: Adicionar, editar, listar e excluir jogos.
- **Autenticação de Usuários**: Login seguro com autenticação.
- **Upload de Imagens**: Upload de capas de jogos.
- **Segurança**: Utilização de CSRF e armazenamento seguro de senhas com Bcrypt.

## Arquivos Principais

- **config.py**: Configurações da aplicação, incluindo chave secreta, URI do banco de dados e configurações de upload.
- **helpers.py**: Funções auxiliares e definição de formulários para jogos e usuários.
- **jogoteca.py**: Arquivo principal que inicializa a aplicação Flask, configura o banco de dados e importa as views.
- **models.py**: Definição dos modelos de dados para jogos e usuários utilizando SQLAlchemy.
- **prepara_banco.py**: Script para configuração inicial do banco de dados MySQL, criação de tabelas e inserção de dados iniciais.
- **views_game.py**: Rotas e lógica de controle relacionadas aos jogos.
- **views_user.py**: Rotas e lógica de controle relacionadas aos usuários.
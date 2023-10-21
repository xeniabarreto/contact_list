# Contact List

Gerencie sua agenda de contatos onde você quiser. Use o Contact List! Projeto criado com o objetivo de aprender Ruby on Rails no curso [Ruby on Rails 5 na prática](https://www.udemy.com/ruby-on-rails-5-na-pratica).

## Requisitos Necessários:

- Ruby 2.3.0 ou Superior
- PostgreSQL
- Rails 5

## Funcionalidades

- Cadastro de usuários
- Login de Usuário
- Gerenciamento de contatos pessoais
- Customização do perfil

## Para executar o projeto:

Antes de tudo, tenha certeza de instalar todos os requisitos necessários. [Siga os passos desse link para configurar](https://gist.github.com/brunojppb/338e08da867f4cb05a8de9d9523f0ffd)

### Clone em sua máquina

```shell
git https://github.com/xeniabarreto/contac_list.git
```

### Instale as dependências

```shell
cd rails_contac_list
bundle install
```

### Configure o Banco de Dados

Copie o arquivo _config/database.exemple.yml_ e cole na mesma pasta, renomeando para _database.yml_
e configure seu bando de dados(Por default, estamos usando PostgreSQL).
Realize a criação do banco e execute as migrações

```shell
rails db:create
rails db:migrate
```

### Execute a aplicação

```shell
rails s
```

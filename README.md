# api-laravel-orm

api-laravel-orm
Este repositório contém uma API desenvolvida em Laravel 11 utilizando o ORM Eloquent para a persistência de dados.

## 🛠️ Especificações Técnicas
Linguagem: PHP 8.2+ (Requisito do Laravel 11)

Framework: Laravel 11

ORM: Eloquent (Nativo do Laravel)

Ferramenta de Build: Vite

## 📦 Dependências Principais
As dependências são gerenciadas via Composer (PHP) e NPM (Node.js):

Backend (PHP/Laravel)
laravel/framework: Core do projeto.

guzzlehttp/guzzle: Cliente HTTP.

Frontend/Assets (Node.js)
vite: Servidor de build.

tailwindcss: Framework CSS.

axios: Promessas HTTP para o navegador.

## 🚀 Como Rodar o Projeto
Siga os passos abaixo para configurar o ambiente local:

1. Configuração Inicial
Clone o repositório e acesse a pasta api:

Bash

git clone <link-do-seu-repositorio>
cd api

2. Instalação de Dependências
Instale os pacotes do PHP e do JavaScript:

Bash

composer install
npm install

3. Configuração do Ambiente
Crie o arquivo .env a partir do exemplo e gere a chave da aplicação:

Bash

cp .env.example .env
php artisan key:generate

Nota: No seu arquivo .env, configure as credenciais do seu banco de dados (Host, Porta, Usuário e Senha).

4. Banco de Dados e ORM
Execute as migrations para que o Eloquent crie as tabelas automaticamente:

Bash

php artisan migrate

5. Execução
Para rodar o projeto, você precisará de dois terminais ativos:

Terminal 1 (Servidor PHP):

Bash

php artisan serve
Terminal 2 (Compilação de Assets):

Bash

npm run dev

A aplicação estará disponível em http://localhost:8000.




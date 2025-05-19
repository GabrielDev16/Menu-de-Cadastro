# Sistema de Cadastro de Usuários

Um sistema web completo para cadastro e visualização de usuários com integração a API externa.

## Funcionalidades

- Cadastro de novos usuários com validação de campos
- Visualização de todos usuários cadastrados em formato de tabela
- Integração com API REST para persistência dos dados

## Tecnologias Utilizadas

- HTML5
- CSS3
- JavaScript (ES6)
- Fetch API para comunicação com backend

## Estrutura do Projeto

## Como Executar

1. Clone o repositório ou faça download dos arquivos
2. Abra os arquivos HTML diretamente no navegador:
   - `cadastro.html` para cadastrar novos usuários
   - `tabela.html` para visualizar os usuários cadastrados

## Endpoints da API

- POST `https://inforpiaui.com.br/aula/criar_usuario.php` - Cria novo usuário
- GET `https://inforpiaui.com.br/aula/listar_usuarios.php` - Lista todos usuários

## Campos do Formulário

O formulário de cadastro inclui:
- Nome completo
- Email
- CPF (somente números)
- Data de nascimento
- Endereço completo (CEP, logradouro, número, bairro, cidade, estado)
- Senha

## Personalização

Para customizar o projeto:

1. Modifique os arquivos CSS para alterar o design
2. Edite os arquivos HTML para adicionar/remover campos
3. Atualize as URLs da API no JavaScript caso necessário

## Requisitos

- Navegador moderno (Chrome, Firefox, Edge)
- Conexão com internet para acessar a API

## Licença

Este projeto está licenciado sob a MIT License.

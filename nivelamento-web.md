# Documento de Requisitos - Sistema de Vendas

## 1. Objetivo do Projeto

Desenvolver um sistema web de vendas para aprendizado de desenvolvimento full-stack, focando em práticas de programação e colaboração em equipe.

## 2. Escopo do Sistema

- **Front-end**: Interface web para interação do usuário
- **Back-end**: API para processamento de dados

## 3. Funcionalidades Principais

### 3.1 Front-end
- Página inicial com produtos em destaque
- Cadastro de Produtos (nome, descrição, preço, imagem)
- Cadastro de Clientes (nome, e-mail, telefone)
- Carrinho de Compras
- Perfil do cliente
- Validação de formulários

### 3.2 Back-end (API RESTful)
- Endpoints para Produtos:
  - `GET /produtos`
  - `POST /produtos`
  - `PUT /produtos/{id}`
  - `DELETE /produtos/{id}`

- Endpoints para Clientes:
  - `GET /clientes`
  - `POST /clientes`
  - `PUT /clientes/{id}`
  - `DELETE /clientes/{id}`

- Endpoints de Vendas:
  - `GET /vendas`
  - `POST /vendas`

## 4. Divisão de Equipes

### 4.1 Equipe Frontend
- Desenvolvimento da interface da aplicação
- Implementação das funcionalidades do cliente
- Integração com a API
- Testes no aplicativo

### 4.2 Equipe backend
- Desenvolvimento dos endpoints
- Implementação da lógica de negócios
- Modelagem do banco de dados
- Documentação da API

## 5. Boas Práticas
- Versionamento com Git/GitHub
- Commits semânticos

## 6. Critérios de Avaliação
- Funcionalidade das implementações
- Qualidade do código
- Integração front-end e back-end
- Colaboração no GitHub

## 7. Entregáveis
1. Código-fonte no GitHub
2. README de instalação
3. Documentação técnica básica
4. Apresentação do sistema

## 8. Considerações Finais
Projeto focado no aprendizado prático de desenvolvimento web e práticas colaborativas.

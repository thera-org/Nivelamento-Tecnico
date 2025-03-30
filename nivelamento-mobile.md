# Documento de Requisitos - Sistema de Vendas Mobile

## 1. Objetivo do Projeto
Desenvolver um aplicativo mobile de vendas para aprendizado de desenvolvimento mobile e back-end, focando em práticas de programação e colaboração em equipe.

## 2. Escopo do Sistema
- **Front-end Mobile:** Aplicativo nativo ou híbrido para interação do usuário
- **Back-end:** API para processamento de dados e integração

## 3. Funcionalidades Principais

### 3.1 Fron-end
- Página inicial com produtos em destaque
- Cadastro de Produtos (nome, descrição, preço, imagem)
- Cadastro de Clientes (nome, e-mail, telefone)
- Carrinho de Compras
- Perfil do cliente
- Modo offline para navegação básica

### 3.2 Back-end (API RESTful)
- Endpoints para Produtos:
    - `GET /produtos`
    - `GET /produtos/{id}`
    - `GET /produtos/categoria/{id}`
    - `POST /produtos`
    - `PUT /produtos/{id}`
    - `DELETE /produtos/{id}`

- Endpoints para Clientes:
    - `GET /clientes`
    - `GET /clientes/{id}`
    - `POST /clientes`
    - `POST /clientes/login`
    - `PUT /clientes/{id}`
    - `DELETE /clientes/{id}`

- Endpoints de Vendas:
    - `GET /vendas`
    - `GET /vendas/{id}`
    - `GET /vendas/cliente/{id}`
    - `POST /vendas`
    - `PUT /vendas/{id}/status`

## 4. Divisão de Equipes

### 4.1 Equipe Frontend
- Desenvolvimento da interface do aplicativo
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

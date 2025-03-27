# Documento de Requisitos - Sistema de Vendas

## 1. Introdução

### 1.1 Objetivo do Projeto

Desenvolver um sistema web completo para vendas de produtos, com foco no aprendizado de desenvolvimento web, práticas de programação e colaboração em equipe. O projeto visa proporcionar aos alunos uma experiência prática no desenvolvimento de uma aplicação full-stack, abordando conceitos fundamentais de front-end, back-end, versionamento e integração de sistemas.

## 2. Escopo do Projeto

### 2.1 Visão Geral do Sistema

O sistema será composto por duas aplicações principais:
- **Front-end**: Interface web para interação do usuário
- **Back-end**: API para processamento de dados e regras de negócio

### 2.2 Público-Alvo

- Alunos em processo de aprendizado de desenvolvimento web
- Usuários finais interessados em realizar compras online

## 3. Requisitos Funcionais

### 3.1 Front-end (Interface Web)

#### 3.1.1 Página Inicial
- Exibição de produtos em destaque
- Layout responsivo e intuitivo
- Design clean e moderno

#### 3.1.2 Cadastro de Produtos
- Formulário com os seguintes campos:
  - Nome do produto
  - Descrição detalhada
  - Preço
  - Upload de imagem
- Validação de campos em tempo real
- Feedback visual para sucesso/erro no cadastro

#### 3.1.3 Cadastro de Clientes
- Formulário para registro de clientes com:
  - Nome completo
  - E-mail
  - Telefone
- Validação de campos obrigatórios
- Tratamento de erros e mensagens de feedback

#### 3.1.4 Carrinho de Compras
- Adicionar produtos
- Remover produtos
- Calcular valor total
- Finalizar compra
- Integração com back-end para processamento

### 3.2 Back-end (API RESTful)

#### 3.2.1 Endpoints de Produtos
- `GET /produtos`: Listar todos os produtos
- `POST /produtos`: Cadastrar novo produto
- `PUT /produtos/{id}`: Atualizar produto
- `DELETE /produtos/{id}`: Excluir produto

#### 3.2.2 Endpoints de Clientes
- `GET /clientes`: Listar todos os clientes
- `POST /clientes`: Cadastrar novo cliente
- `PUT /clientes/{id}`: Atualizar cliente
- `DELETE /clientes/{id}`: Excluir cliente

#### 3.2.3 Endpoints de Vendas
- `GET /vendas`: Listar todas as vendas
- `POST /vendas`: Registrar nova venda
- Vincular cliente e produtos na venda

## 4. Requisitos Técnicos

### 4.1 Tecnologias Recomendadas

#### Front-end
- **Framework**: Next.js com React
- **Linguagem**: TypeScript
- **Estilização**: Tailwind CSS
- **Gerenciamento de Estado**: React Hooks
  - `useState`
  - `useEffect`
  - Hooks customizados

#### Back-end
- **Framework**: Java Spring Boot
- **Linguagem**: Java
- **Banco de Dados**: Recomendado H2 (banco em memória) ou PostgreSQL

### 4.2 Boas Práticas

#### Desenvolvimento
- Programação Orientada a Objetos
- Princípios SOLID
- Tratamento de exceções
- Validação de dados

#### Versionamento
- Utilizar Git e GitHub
- Branches para features
- Pull requests
- Commits semânticos

## 5. Requisitos de Usabilidade

### 5.1 Interface
- Design responsivo
- Compatível com dispositivos móveis
- Feedback visual para ações do usuário
- Mensagens claras de erro e sucesso

### 5.2 Experiência do Usuário
- Navegação intuitiva
- Carregamento rápido
- Campos de formulário autoexplicativos
- Validações em tempo real

## 6. Critérios de Avaliação

### 6.1 Aspectos Técnicos
- Funcionalidade das implementações
- Qualidade do código
- Integração front-end e back-end
- Uso correto de padrões de projeto

### 6.2 Colaboração
- Uso efetivo do GitHub
- Commits organizados
- Trabalho em equipe
- Documentação do projeto

## 7. Entregáveis

1. Código-fonte completo no GitHub
2. README com instruções de instalação
3. Documentação técnica básica
4. Apresentação do sistema funcionando

## 8. Considerações Finais

O projeto visa proporcionar uma experiência prática de desenvolvimento web, focando no aprendizado de tecnologias modernas e práticas de programação colaborativa.

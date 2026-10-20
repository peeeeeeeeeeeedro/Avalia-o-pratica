# Avalia-o-pratica
Simulação de Avaliação Prática – Sistema de Biblioteca Escolar

## Cenário

Uma escola precisa informatizar sua biblioteca para controlar livros, usuários e empréstimos. Sua equipe deverá desenvolver um sistema completo contendo frontend, backend, banco de dados e documentação técnica.
# Entregas Obrigatórias

---
## 1. Lista de Requisitos Funcionais

**Tempo estimado:** 10 minutos

Elabore um documento contendo no mínimo 8 requisitos funcionais.

### Exemplos

- O sistema deve permitir autenticação de usuários.
- O sistema deve permitir cadastrar livros.
- O sistema deve permitir consultar livros.
- O sistema deve permitir editar livros.
- O sistema deve permitir excluir livros.
- O sistema deve registrar empréstimos.
- O sistema deve registrar devoluções.
- O sistema deve gerar relatórios de empréstimos.

---
## 2. Diagrama Entidade Relacionamento (DER)

**Tempo estimado:** 10 minutos

Crie o DER contendo pelo menos as seguintes entidades:

### Usuário

- id_usuario
- nome
- email
- senha

### Livro

- id_livro
- titulo
- autor
- categoria
- quantidade

### Empréstimo

- id_emprestimo
- data_emprestimo
- data_devolucao
- id_usuario
- id_livro

---
## 3. Script de Criação e População do Banco de Dados

**Tempo estimado:** 10 minutos

Desenvolva o script SQL contendo:

### Criação das tabelas

- Usuario
- Livro
- Emprestimo

### Inserção de dados

- 3 usuários
- 5 livros
- 5 empréstimos

---
## 4. Interface de Autenticação de Usuários (Login)

**Tempo estimado:** 20 minutos

Desenvolva uma tela contendo:

### Campos

- E-mail
- Senha

### Botões

- Entrar
- Limpar

### Regras

- Validar campos obrigatórios.
- Exibir mensagem para acesso inválido.
- Permitir acesso mediante autenticação.

---
## 5. Interface Principal do Sistema

**Tempo estimado:** 20 minutos

Desenvolva uma página principal contendo:

### Dashboard

- Quantidade de livros cadastrados
- Quantidade de empréstimos ativos
- Quantidade de usuários

### Menu

- Livros
- Empréstimos
- Relatórios
- Sair

---
## 6. Interface de Cadastro de Livros

**Tempo estimado:** 45 minutos

Desenvolva uma tela contendo:

### Campos

- Título
- Autor
- Categoria
- Quantidade disponível

### Funcionalidades

- Cadastrar
- Alterar
- Excluir
- Pesquisar

### Validações

- Campos obrigatórios
- Quantidade maior ou igual a zero

---

## 7. Interface de Gestão de Empréstimos

**Tempo estimado:** 45 minutos

Desenvolva uma tela contendo:

### Campos

- Usuário
- Livro
- Data do empréstimo
- Data prevista para devolução

### Funcionalidades

- Registrar empréstimo
- Registrar devolução
- Consultar histórico

### Regras

- Não permitir empréstimo de livro sem estoque disponível.
- Atualizar quantidade automaticamente.

---

## 8. Descritivo de Casos de Teste de Software

**Tempo estimado:** 10 minutos

Criar pelo menos 5 casos de teste.

### Exemplos

| ID | Cenário | Resultado Esperado |
| --- | --- | --- |
| CT01 | Login válido | Acesso liberado |
| CT02 | Login inválido | Mensagem de erro |
| CT03 | Cadastro de livro | Livro salvo |
| CT04 | Empréstimo com estoque | Empréstimo registrado |
| CT05 | Empréstimo sem estoque | Operação bloqueada |

---

## 9. Lista de Requisitos de Infraestrutura

**Tempo estimado:** 10 minutos

### Hardware

- Processador Dual Core ou superior
- 4 GB RAM
- 20 GB armazenamento

### Software

- Navegador Web
- MySQL ou PostgreSQL
- Servidor Web

### Rede

- Internet
- Rede local da escola

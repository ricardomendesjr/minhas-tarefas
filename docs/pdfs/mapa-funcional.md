# PDFS — Mapa Funcional

**Produto:** Minhas Tarefas  
**Versão:** 0.1  
**Estado:** Rascunho

## 1. Objetivo

Apresentar a decomposição funcional do aplicativo Minhas Tarefas, identificando os módulos e as funcionalidades previstas.

## 2. Estrutura funcional

### MOD-01 — Cadastro de Tarefas

Responsável pelas operações de manutenção dos registros de tarefas.

- **FUN-01.01.01 — Criar tarefa**
- **FUN-01.01.02 — Editar tarefa**
- **FUN-01.01.03 — Excluir tarefa**

### MOD-02 — Organização de Tarefas

Responsável pela consulta e organização das tarefas registradas.

- **FUN-02.01.01 — Consultar lista de tarefas**
- **FUN-02.01.02 — Filtrar tarefas por situação**
- **FUN-02.01.03 — Definir prioridade**

### MOD-03 — Acompanhamento de Tarefas

Responsável pelo controle da execução e acompanhamento das tarefas.

- **FUN-03.01.01 — Concluir tarefa**
- **FUN-03.01.02 — Reabrir tarefa**
- **FUN-03.01.03 — Visualizar resumo das tarefas**

## 3. Convenção de identificação

- MOD: identifica um módulo.
- FUN: identifica uma funcionalidade.
- Os códigos possuem três segmentos numéricos para permitir subdivisões futuras.

Os identificadores devem permanecer estáveis ao longo do desenvolvimento.

## 4. Dependências preliminares

- As funcionalidades de edição, exclusão, conclusão e reabertura dependem da existência de tarefas cadastradas.
- Os filtros dependem da disponibilidade da consulta às tarefas.
- O resumo depende da disponibilidade das informações de situação das tarefas.

## 5. Observações

Esta estrutura representa a versão inicial do escopo funcional.

As regras de negócio, fluxos e critérios de aceitação serão documentados individualmente nas fichas PDFS.

A estrutura poderá evoluir conforme os requisitos forem refinados.

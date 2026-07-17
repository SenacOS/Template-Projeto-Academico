---
name: "📋 Tarefa"
about: "Unidade de trabalho técnica, vinculada a um Módulo/Epic maior via Sub-issue"
title: "[TASK] "
labels: ["task"]
---

## // Descrição
<!-- Descreva de forma objetiva o que esta tarefa implementa -->

**Módulo Relacionado:**
<!-- Use o recurso nativo "Create sub-issue" / "Parent issue" na sidebar do GitHub para vincular esta tarefa ao Módulo/Epic correspondente. O campo abaixo é só um atalho de contexto rápido para quem está lendo. -->
Sub-issue de: #(número da issue-pai, se aplicável)

## // Critérios de Aceitação
- **Critério 1:**
- **Critério 2:**
- **Critério 3:**

## // Checkpoint de Desenvolvimento
- [ ] **Data Contract:** Estruturas de entrada/saída de dados definidas (DTOs, interfaces, schemas).
- [ ] **Business Logic:** Regra de negócio implementada na camada de serviço.
- [ ] **Controller/Endpoint:** Rota exposta com o verbo HTTP adequado.
- [ ] **Database Schema:** Migration/alteração de schema, se aplicável.
- [ ] **Security:** Regras de acesso configuradas, se aplicável.
- [ ] **Integration Test:** Fluxo validado de ponta a ponta (Postman, testes automatizados, etc.).
- [ ] **Validation:** Retorno/comportamento conferido conforme os critérios de aceitação.

**Status:** _(em andamento / concluída / bloqueada)_
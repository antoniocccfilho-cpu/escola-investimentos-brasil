---
description: "Inventário funcional com evidências, limitações e critérios de aceite."
icon: list-check
---

# Funcionalidades

## O que a aplicação propõe

A experiência inclui navegação por cursos, módulos e aulas, interações didáticas, atividades e acompanhamento do aprendizado. O diagnóstico de **03/11/2026** documentou apenas parte dessa experiência em pré-visualização.

## Inventário por grau de verificação

| Recurso | Evidência disponível | Situação documental |
| --- | --- | --- |
| Início e biblioteca/catálogo | Telas observadas na pré-visualização | **Observado visualmente** |
| Acesso ao player da Saga — aulas 1 e 4 | Navegação pontual e capturas | **Observado**, sem auditoria de cada tela |
| Saga do Dinheiro (4 aulas, 61 telas) | Inventário informado pelo construtor | **Inventariado**, sujeito à conferência |
| Aula 4 — Juros e o Poder do Tempo | Player abre com 10 telas | **Integrada no ambiente observado; revisão pedagógica pendente** |
| Login, contas e proteção de rotas | Descritos no material de setembro | **Revalidação ponta a ponta pendente** |
| Meu Progresso e percentuais | Dados demonstrativos no diagnóstico | **Não representam progresso real** |
| Conhecimento e Prática | Catálogo visível; ações incompletas observadas | **Parcial/demonstração** |
| Assistente de IA dentro do app | Proposta futura, não observada | **Planejado** |
| Persistência individual de progresso | Sem comprovação em teste real | **Não verificada** |

## Pendências funcionais conhecidas

- **F01 — navegação:** o botão “Continuar trilha” levou a “Aula não encontrada” em 03/11; a correção foi relatada, mas deve ser testada na versão final.
- **F02 — indicadores:** percentuais exibidos devem ser marcados como demonstração até existir progresso persistido.
- **F03/F04 — práticas e conhecimento:** ações e contadores precisam corresponder ao que realmente abre e executa.
- **F09/F11 — catálogo:** reconciliar totais de módulos, IDs de aulas e placeholders com o inventário real.

Os códigos F01–F11 estão descritos no [registro de evidências](11-evidencias-visuais.md).

## Critério de aceite de uma funcionalidade

{% stepper %}
{% step %}
### Descrever o comportamento

Qual ação o usuário realiza? Qual resultado esperado?
{% endstep %}
{% step %}
### Testar no ambiente identificado

Registrar data, versão, perfil de teste, dispositivo e passos.
{% endstep %}
{% step %}
### Guardar a evidência

Captura, vídeo, resultado de teste ou log sem dados privados.
{% endstep %}
{% step %}
### Classificar

**Funcional**, **parcial**, **demonstrativa**, **bloqueada** ou **planejada**, com responsável e pendência.
{% endstep %}
{% endstepper %}

{% hint style="info" %}
A auditoria geral simulando um aluno permanece reservada para **após a produção das aulas**, conforme decisão de Antônio. Testes pontuais para documentar funcionalidades e corrigir problemas não substituem essa auditoria.
{% endhint %}

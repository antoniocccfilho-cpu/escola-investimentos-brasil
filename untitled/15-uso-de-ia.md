---
description: "Protocolo de documentação de prompts, revisão e validação humana."
icon: robot
---

# Uso de inteligência artificial e revisão humana

## Objetivo

Usar IA para apoiar produção didática, análise de inconsistências, programação assistida e documentação — sempre com revisão humana, testes e evidências.

## Fluxo de trabalho registrado

1. Antônio define a missão e os limites do escopo.
2. Agentes produzem propostas e pareceres, identificando premissas e riscos.
3. Antônio delibera e aprova o que será implementado.
4. A plataforma Base44 recebe o escopo aprovado.
5. A equipe verifica os resultados e registra erros, correções e evidências.
6. O conhecimento obtido retorna ao Drive e, depois de revisado, à documentação pública.

Em 03/11, a produção da Escola operou com uma equipe reduzida, incluindo ChatGPT, Gemini e Base44. Isso não significa que todo agente ou automação citada na arquitetura esteja efetivamente conectado ao app.

## Registro de erros e aprendizado reutilizável

| Campo | Pergunta a responder |
| --- | --- |
| Contexto | Em qual página, versão e ambiente ocorreu? |
| Sintoma | O que aconteceu? Qual era o esperado? |
| Causa | Qual foi a causa demonstrada? O que ainda é hipótese? |
| Correção | Qual arquivo, conteúdo ou decisão foi alterado? |
| Teste | A correção foi reproduzida e validada? |
| Prevenção | Qual orientação uma futura IA deve ler para evitar reincidência? |

{% hint style="warning" %}
Saídas de IA são propostas ou evidências de execução conforme sua origem; não equivalem automaticamente a aprovação humana, implementação funcional ou validação pedagógica.
{% endhint %}

## Privacidade e integridade acadêmica

- Priorizar dados fictícios em exemplos e demonstrações.
- Não publicar números de matrícula, endereços de e-mail dos estudantes ou credenciais.
- Registrar ferramenta, objetivo, prompt, resultado, revisão humana e fonte.
- Identificar o autor humano responsável pela decisão final.

**Fonte:** Constituição do Conselho DAVINCI; Índice 99; Documentação central A3; Documento 07 (Drive interno).